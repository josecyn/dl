# Kaggle projects

In this folder I have the [Kaggle](https://www.kaggle.com/competitions) and [Signate](https://signate.jp/competitions) projects I play with.

Most of them are __image recognition__ projects using Keras and Tensorflow: 

* __DogsVsCats__: try to identify dogs and cats. I did this project using very few data and using image augmentation.

* __TC / nonTC__: Tropical storm or not? Binary classification using, once again, very few data. TIF files made me develop my own keras generator.

* __iMaterialize__: multiclass classification identifies furniture objects among 128 classes. The organisation only provided the links to images. For that reason, I decided to download just a few for each class and use image augmentation. 


In the __Taxi Fare__ the goal is to predict the price of the taxi ride based on pick up and drop off location and datetime. 
I implemented this project using __XGBoost__. 
I focused on creating some new features. For example: is the taxi trip from or to the airport?