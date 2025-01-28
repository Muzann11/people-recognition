# Famous People Classification
## Classifying Famous People Using Images and Machine Learning

This project focuses on classifying images of famous people into one of five categories using a Logistic Regression model. The dataset used consists of images of people to be classified, processed with face and eye detection techniques to extract relevant features. The primary objective is to accurately identify the person in an image based on facial features and patterns.

## Project Overview
The dataset contains images of five famous individuals, with each image preprocessed to detect faces and eyes using Haar Cascade classifiers. After preprocessing, the images are transformed into grayscale and wavelet decomposition is applied to extract additional features for improved classification.

## Project Goals
1. Build a classification model using Logistic Regression to identify the person in an image.
2. Implement face and eye detection to preprocess images for feature extraction.
3. Utilize wavelet decomposition (W2D) for enhanced feature representation.
4. Evaluate the model's performance using metrics like accuracy and classification report.
5. Automate the preprocessing pipeline to ensure consistency across the dataset.

## Project Goals
1. Build a classification model using Logistic Regression to identify the person in an image.
2. Explore other classification models, including Support Vector Machine (SVM) and Random Forest to compare performance.
3. Implement face and eye detection to preprocess images for feature extraction.
4. Utilize wavelet decomposition (W2D) for enhanced feature representation.
5. Evaluate all models' performances using metrics like accuracy and classification reports, selecting the best-performing model.
6. Automate the preprocessing pipeline to ensure consistency across the dataset.


## Key Features
- **Face and Eye Detection**: Haar Cascade classifiers are used to detect faces and eyes, ensuring that only images with clearly identifiable faces are included.
- **Wavelet Decomposition**: Extracts additional features from images to improve classification accuracy.
- **Logistic Regression Model**: Selected for its simplicity and effectiveness in handling the dataset.
- **Dataset Preprocessing**: Automates cropping and resizing of images to standard dimensions (32x32) for uniformity.
- **Performance Metrics**: The model achieved an accuracy of **93%**, demonstrating its effectiveness.

## Key Insights
- Preprocessing steps such as face and eye detection, combined with wavelet decomposition, significantly enhance the model's performance.
- The Logistic Regression model effectively classifies the images with high accuracy.
- This project highlights the importance of feature engineering and preprocessing in image classification tasks.

## Future Improvements
1. Explore deep learning models like CNNs for improved accuracy and scalability.
2. Expand the dataset to include more famous individuals.
3. Enhance preprocessing to handle low-quality or obscured images.

## Inspired By
This project is based on a tutorial from YouTube Codebasics. The original GitHub repository can be found here: https://github.com/codebasics/py/tree/master/DataScience/CelebrityFaceRecognition

Feel free to provide feedback or suggestions for improvement. You can reach me at Email: mfauzanfauzan123@gmail.com and Linkedin: https://www.linkedin.com/in/muhammad-fauzan-6b650528a
