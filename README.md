# LbiPlantUbi

LbiPlantUbi: The predictive model that incorporates deep learning model and natural language processing technique to predict plant ubiquitination sites. The model automatically learns features directly from raw protein sequences and integrates prediction into a single deep learning architecture.
# Requirement
	- Keras
	- Numpy
	- Sklearn
	- Pandas
# Dataset
This process yielded 7000 protein fragments from the plant data subset, with 3500 positive and 3500 negative fragments selected randomly.
	- The independent dataset: 1500 sequences were chosen at random from the total fragments (750 positive and 750 negative)
	- The training set: 5500 fragments (2750 positive and 2750 negative).
# Train model: We use Google colab pro buid this model
	- Cross validation: CV_LBiPlantUbi.ipynb
	- Train model: Model_LBiPlantUbi.ipynb
	  + Save and name the trained model as LBiPlantUbi.h5
   	  + Use LBiPlantUbi.h5 in the saved_folder for predicting
	- Independent test and predict: LBiPlantUBi_ID.ipynb
# Contact
Please feel free to contact us if you need any help: nvnui@ictu.edu.vn
