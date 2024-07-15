# Brain AVM Classification Project

## Dataset

### Dataset Details
This dataset contains 7084 images of human brain MRI images which are classified into 2 classes:
- avm
- non-avm

### Data Pre-processing
After splitting them into train-val-test datasets with 70-20-10 ratio, we had 
- 4678 for training 
- 1338 for validation
- 668 for testing

### Augmentation
After cropping our images, augmentation was needed to improve our accuracy.
We used rotation, horizontal and vertical flip, brigthness change, shear, zooming as techniques. 

## Model

### Pre-trained Model Selection
To perform image classification with higher accuracy, we used pre-trained models from keras's application module.
VGG16, VGG19, ResNet50v2, MobileNetv2 and EfficientNetB0 are the pre-trained models that we trained and compared by their accuracy.









