# Face Recognition and Features Extractor
The idea of this project is to detect faces from a source, recognize the person and extract some possible features, like: Age, Ethnicity, Sex, Emotions, etc.

So the project is segmented in three parts.

## 1 - Face Detection
- Use a pre-trained model (YOLOV8 for real time detection)
- Fine tune the model for face detection only
- Use a software to prepare the dataset for the training (RoboFlow) or use a preprocessed dataset from kaggle, as https://www.kaggle.com/datasets/sbaghbidi/human-faces-object-detection?select=faces.csv (check model compatibility)

## 2 - Face Recognition
- Use a pre-trained model (MobileNetV3 or other)
- Fine tune the model for face recognition
- Use a software to prepare the dataset for the training (RoboFlow) or label by hand.

## 3 - Features Extractor
- TBD

Useful links:
- https://link.springer.com/article/10.1007/s42979-020-00325-6
- https://www.mdpi.com/1424-8220/20/13/3765
https://www.kaggle.com/datasets/fareselmenshawii/face-detection-dataset/
