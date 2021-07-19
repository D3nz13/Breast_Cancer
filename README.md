# Description:  
The dataset has been downloaded from `kaggle.com`. It contains information about 569 patients with or without a breast cancer.  
# Features:  
The dataset contains 10 features that are computed for each cell nucleus:  
- radius
- texture (standard deviation of gray-scale values)
- perimeter
- area
- smoothness (local variation in radius lengths)
- compactness (perimeter^2 / area - 1.0)
- concavity (severity of concave portions of the contour)
- concave points (number of concave portions of the contour)
- symmetry
- fractal dimension  
  
Also, each feature has another feature containing value of the mean, standard error and the worst (or largest).  
# My approach:  
1) Exploratory data analysis, including feature correlation analysis  
2) Getting rid of highly correlated features  
3) Feature selection (ANOVA)  
4) Datapreprocessing  
5) Hyperparameter tuning  
  
In the end, support vector machine classifier turned out to be the best classifier, achieving the accuracy of `0.982` and the F1 score of `0.976`  
Number of `false positives: 1`  
Number of `false negatives: 1`  
