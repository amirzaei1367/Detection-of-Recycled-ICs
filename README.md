# Detection-of-Recycled-ICs
Using a stack-model to identify a target chip as new or recycled.

### How it works: ###
Just set the path for root directory **root_path**, and set the name of input file **in_file** and a file name for storing statistics of the used model **res_file**.  

### Possible Improvements: ###
* Right now my focus was on **StackingCVRegressor**, it can be improved in order to consider only the best regressors.
* Maybe a better preprocessing improves performance. As is now features have been normalized and zero features have also been removed.
* it worth to do more hyper-parameter tuning in order to obtain a better performance.
