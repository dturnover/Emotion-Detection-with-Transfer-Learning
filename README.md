# AAI-521-Final-Project VGG
VGG transfer learning was performed separately from efficientNet and there are notable differences in preprocessing and optimization. 
The VGG notebook maintains the original image sizes, uses tensorflow rather than pytorch and uses RMSprop for optimization.

Usage:
The dataset is used for transfer learning in VGG.ipynb. The simplest way to allow the program to run is to download the dataset and 
include the train and test folders in the same directory as the notebook file. At that point the notebook will run smoothely. 
