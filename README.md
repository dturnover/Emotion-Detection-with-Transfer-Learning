# AAI-521-Final-Project
## VGG-16 Model
AAI-521-Final-Project VGG

VGG transfer learning was performed separately from efficientNet and there are notable differences in preprocessing and optimization. The VGG notebook maintains the original image sizes, uses tensorflow rather than pytorch and uses RMSprop for optimization.

Usage: The dataset is used for transfer learning in VGG.ipynb. The simplest way to allow the program to run is to download the dataset and include the train and test folders in the same directory as the notebook file. At that point the notebook will run smoothely.

## EfficientNet B0 Model
Convolutional neural network (CNN) model developed by Google Research. It is designed to improve upon existing CNN architectures by scaling up model capacity while maintaining high accuracy and efficient use of resources.
EfficientNet is based on a compound scaling method that scales model capacity in a more structured and efficient manner. This allows the model to achieve superior performance on a wide range of tasks, including image classification, object detection, and semantic segmentation.
One key feature of EfficientNet is its use of a novel convolutional block, called the MBConv block, which is designed to reduce the number of parameters and computational cost while maintaining high accuracy. As shown in Figure 4, The MBConv block uses depth-wise separable convolutions and squeeze-and-excitation (SE) modules to improve model capacity and efficiency. 
However, a limitation of EfficientNet-B0 is that it requires a large amount of computational resources to train and deploy. EfficientNet models are large and complex, which can make them challenging to train on standard hardware. We can view the number of trainable parameters involved in our model construction: 4,016,515.  

Usage: For the EffnetB0 model you can directly install the emotions dataset from Kaggle
