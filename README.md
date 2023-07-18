# Drybulk density
R scripts for the spatial prediction of dry bulk density (DBD) of surface sediments.
### Main characteristics

Variable pre-selection with Boruta algorithm (Kursa & Rudnicki, 2010) and de-correlation analysis.

Spatial predictions with Quantile Regression Forests (Meinshausen, 2006) including spatial 10-fold cross validation and model tuning (mtry and final variable selection with forward feature selection).

Estimation of the area of applicability of the model (Meyer & Pebesma, 2021).

### References

Kursa, M. B., & Rudnicki, W. R. (2010). Feature Selection with the Boruta Package. Journal of Statistical Software, 36(11), 1–13. https://doi.org/10.18637/jss.v036.i11

Meinshausen, N. (2006). Quantile Regression Forests. Journal of Machine Learning Research, 7(35), 983-999. http://jmlr.org/papers/v7/meinshausen06a.html

Meyer, H., & Pebesma, E. (2021). Predicting into unknown space? Estimating the area of applicability of spatial prediction models. Methods in Ecology and Evolution, 12(9), 1620–1633. https://doi.org/https://doi.org/10.1111/2041-210X.13650