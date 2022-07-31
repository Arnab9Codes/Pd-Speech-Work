Steps followed for noise reduction:
-----------------------------------

1)Noise were removed in the proposed manner:
    i.  Select features with skewness between -1 and 1
    ii. Select features with kurtosis between -1 and 1
    (This results in features that are approximately gausian for given sample space

2)here 2 hypothesis has been tested and depending on p=0.05 confidence features were selected

After reduction we ger feature set FH, follwed by generation of binary and trinary combination of features extracted from FH

Hypothesis testing:
-------------------
    Hypothesis 1: Features do not significantly contribute to PD positive and PD negative.
    ------------
    Based on rejection with 95% confidence, FPD feature set with 95 features were selected.

    Follwed by generation of binary and trinary combination of features extracted from FPD (FPD95.csv)
    
    
    
    hypotheis 2: gender does not matter for Pd positive patients.
    -----------
    Based on rejection with 95% confidence, FG feature set with 70 features were selected.
    
    
