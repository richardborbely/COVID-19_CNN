# COVID-19 vs Clean chest X-ray classification using a CNN

A modified MobileNet model is used to classify COVID-19 infected chest radiographs. Evaluation of the network shows a 100% accuracy, and 1.0 AUC score.
Class activation maps seem to show a reasonable distinction between the COVID-19 and Clean classes. More datapoints should be acquired and included to produce a more reliable model.

To run the jupyter notebook, which contains the project:
  - Download a 64bit version of Python
  
  - Open CMD at .ipynb location
  
  - Acquire necessary libraries: "pip install tensorflow keras scikit-learn scipy Pillow pandas matplotlib jupyter"
  
  - Run "jupyter notebook" and open the project
  
To import the model:
  - Run "Load session model" cell with "_Covid19_transfer" session parameter
  
  - Run "Import session model" cell



.

COVID-19 images acquired from: https://github.com/ieee8023/covid-chestxray-dataset

Clean images from: https://nihcc.app.box.com/v/ChestXray-NIHCC
