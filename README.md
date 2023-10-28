# NonProbabilisticClassifiers
An evaluation of Non Probabilistic Classifiers and Feature Subset Selection Methods in the characterization of the popularity flag in Spotify's Track Dataset

Files:
-report.pdf: Main report of problem description, methodology, findings, conclusions and references.
-presentation.pdf: Presentation of the problem for 2023/2024 lectures in Machine Learning at  Polytechnic University of Madrid.
-Spotify_Tracks_Dataset_Processing.ipynb: Python notebook for prprocessing, data exploration, initial ML models and Wrapper approach FFS.
-Data: Folder with:
    -dataset.csv with the original data
    -clean_data.csv with preprocessed data
    -notnorm_data.csv with preprocessed data except normalization 
    -Weka Data folder the arff files employed for weka models are included:
        -knn_all.arff with all orignal variables.
        -knn_unifss.arff with variables after univariate FSS
        -knn_multfss.arff with variables after multivariate FSS