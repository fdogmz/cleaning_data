# cleaning_data

This repo contains data files from the project described in http://www.insideactivitytracking.com/data-science-activity-tracking-and-the-battle-for-the-worlds-top-sports-brand/.  The process for the generation of the final data set is described below


1. First the training and test data sets were merged.
2. The names of the original variables were modified removing innecesary characters (some numbers, spaces, parenthesis,...).
3. A subset of the original variables were selected considering only measurements summaring mean and standard deviation.
4. A factors column identifiying the subjects was added to the data set as well as a column identifying the correspondig activity (the original identifying numbers were transformed to factors with descriptive names).
5. The final data set was constructed grouping the subjects and activities and evaluating the mean of every variable for every group.










