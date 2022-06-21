# Categorization_dogs_cats1

##Idea

Instead of training a deep network from scratch, we can actually take a pre-trained network and use it for a different task as learning of a new task relies on the previously learned tasks.
Assisting in image analysis and classification tasks including object detection with good accuracy.
We will use InceptionV3 which is a network already trained on more than a million images from the ImageNet database. Know about InceptionV3.


## Dataset Preparation
 We prepared the dataset Vegetable_Images included: <br />
  Dogs and cat included:
| test  | train | validation |
| ----- | ----- | ---------- |
| 12501  | 20000 | 5000 |
(5000 validation data taken from train data, train data have 25000)
Total train data and validation data have 12500 image cats and 12500 image dogs
## Training Model
Use the command prompt run:
```
python TrainingModel.py
```
We take the data in [train folder](https://github.com/kinn10/Categorization_dogs_cats1/tree/main/Phanloaichomeo/dogs-vs-cats/dtrain) to train the model.
Training model process will take a lot of time. So that we already trained the model and saved it to **Model1.h5** and compress in **Model1.zip** You can pass the training step and start to predict











