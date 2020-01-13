## The classification and regression tree project
[https://itstud.hiof.no/\~rolando/ML/project1\_eng.pdf](https://itstud.hiof.no/~rolando/ML/project1_eng.pdf)

### Criterias for selecting dataset
* Given in course description above
* Medical oriented, spectrocopy oriented
* n \> P
* Both categorical and numerical predictors
* Dataset to be used for classification, regression and neural nets
* Consider pre-processing steps and normal distribution skewness challenge
* Consider PCA pre-processing steps for spectral data
* Not too big with respect to computational efficiency
* Open and referencable, thrustworthy and usable
* 
### Candidate public datasets
1. [https://www.kaggle.com/dileep070/heart-disease-prediction-using-logistic-regression](https://www.kaggle.com/dileep070/heart-disease-prediction-using-logistic-regression)
	* Pros: Nice dataset for decision trees and for regression problems, contains both categorial and regression problems
	* Cons: No spectral data (would be nice to evaluate)
2. [https://www.kaggle.com/uciml/pima-indians-diabetes-database](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
	* Pros: Nice dataset for decision trees and for pre-processing learning, understandable data
	* Cons: No spectral data (would be nice to evaluate)
3. [https://www.kaggle.com/andriitrelin/cells-raman-spectra](https://www.kaggle.com/andriitrelin/cells-raman-spectra)
	* Pros: Spectral data, learn pre-processing/dimension reduction tasks
	* Cons: Not easy categorial task
4. [https://www.kaggle.com/shayanfazeli/heartbeat](https://www.kaggle.com/shayanfazeli/heartbeat)
	* Pros: Suitable for neural nets
	* Pros: Not immediately ready for decision trees
5. [https://www.kaggle.com/sulianova/cardiovascular-disease-dataset#cardio\_train.csv](https://www.kaggle.com/sulianova/cardiovascular-disease-dataset#cardio_train.csv)
	* Pros: Pure categorial data suitable for decision trees
	* Cons: Relatively simple case presumably not suitable for neural net part of the project. No references.
6. [https://www.kaggle.com/stephengoldie/big-databiopharmaceutical-manufacturing#100\_Batches\_IndPenSim\_V3.csv](https://www.kaggle.com/stephengoldie/big-databiopharmaceutical-manufacturing#100_Batches_IndPenSim_V3.csv)
	* Pros: Candidate for neural nets, both numerical (spectra) and presumable categorial data
	* Cons: Data for each process step, should collect batchwise data. If not readily available, this is a huge job

### Methods
* Pair plot: [https://towardsdatascience.com/visualizing-data-with-pair-plots-in-python-f228cf529166](https://towardsdatascience.com/visualizing-data-with-pair-plots-in-python-f228cf529166)
* Correleation matrix: [https://stackoverflow.com/questions/29432629/plot-correlation-matrix-using-pandas](https://stackoverflow.com/questions/29432629/plot-correlation-matrix-using-pandas)
* Heatmap, confusion matrix