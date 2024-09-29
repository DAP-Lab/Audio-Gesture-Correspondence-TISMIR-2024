The codes which have been used to conduct our experiments are present in this folder in the form of ipynb notebooks.

Relating F0 with Kinematic Changes.ipynb contains the code for Section 3 in our paper.

The codes for Stable Note Classification experiment are present in the folder Stable_Notes_SVM_Experiment. The notebooks are numbered 1, 2, 3a and 3b according to the order in which they must be used. The first notebook (Generating Stable Note Timestamps) can be used to demarcate the start and end timestamps for stable and non-stable regions in the pitch contour using the pitch class distribution procedure explained in the paper. The second notebook (Subseq Dict Generation) can be used to generate files termed as "subsequence dictionary" files that contain the pitch and gesture data for each stable/non-stable region alongwith the ground truth label (st for stable, ns for non-stable). This is done in order to ensure ease of processing in the next task.
The notebooks 3a and 3b can be used after 1 and 2, in order to carry out the respective feature vector variant as needed for the SVM cross validation. 

The codes for Raga Phrase Detection are present in the folder Raga_Phrase_Detection_Experiment. The following files are also present:
- gmD_df3.csv: Matched timestamps and DTW costs for each SDS-query pair
- gmD_df4.csv: Matched timestamps and DTW costs for the best matching query for each SDS
- gmD_queries_chosen.csv: Timestamps, filename information for each query template
- gmD_Queries (folder): The masterfile data (pitch contour and gesture) for each query template in csv files
- functions.py: Necessary functions imported in the notebook 

