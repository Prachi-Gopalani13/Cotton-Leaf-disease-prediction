# Cotton-Leaf-disease-prediction

Dataset Available: https://www.kaggle.com/janmejaybhoi/cotton-disease-dataset

## CNN for Image Classification
CNN image classifications take an input image, process it and classify it under certain categories (Eg., Dog, Cat, Tiger, Lion). Computers sees an input image as array of pixels and it depends on the image resolution. Based on the image resolution, it will see h x w x d (h = Height, w = Width, d = Dimension).

## Keras Application
#### 1. VGG16 
By default, it loads weights pre-trained on ImageNet. Each Keras Application expects a specific kind of input preprocessing. For VGG16, call tf.keras.applications.vgg16.preprocess_input on your inputs before passing them to the model.
![](screenshots/VGG16.JPG)

#### 2. ResNet152V2 
Optionally loads weights pre-trained on ImageNet. Note that the data format convention used by the model is the one specified in your Keras config at ~/.keras/keras.json.
Each Keras Application expects a specific kind of input preprocessing. For ResNetV2, call tf.keras.applications.resnet_v2.preprocess_input on your inputs before passing them to the model.
![](screenshots/resnet152v2.JPG)

#### 3. Inception v3
Optionally loads weights pre-trained on ImageNet. Note that the data format convention used by the model is the one specified in the tf.keras.backend.image_data_format().
Each Keras Application expects a specific kind of input preprocessing. For InceptionV3, call tf.keras.applications.inception_v3.preprocess_input on your inputs before passing them to the model.
![](screenshots/inceptionv3.JPG)

### Modelling Measures
Following parameters are used for measuring:
optimizer = 'adam',
loss = 'binary_crossentropy', 
metrics = 'accuracy'


