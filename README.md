# Biomarker-selection-Python

A notebook where statistical tools were used in Python to select the markers that differ between two groups.
There was made a Quantile normalization and a Maxmin scaling to preprocess the data
A PCA and a correlation analysis were applied to visualize the difference between both groups
To select the better makers, the P-value and FoldChange were calculated and set to limits:
    - p-value < 0.005 -> to ensure that the difference between both groups is statistically significant in the marker.
    - FoldChange (mean group A / mean group B) > 2 -> to ensure that there is enought large in the marker
