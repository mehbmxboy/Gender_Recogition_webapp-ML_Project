Machine Learning Project -Human Gender Classification using Facial Recognition

This is a machine learning project that uses Support Vector Machines (SVM) and Haar Cascade Classifiers to classify gender based on facial recognition. The frontend of the project application is built using Flask. All the trained models are kept in the models folder. The user can upload a photo into the application and the resulting output will show the gender and highlighted face.

This project was completed as the final year project for an engineering bachelor's degree.

Installation

To run this project, follow these steps:

    Clone the repository to your local machine.
    Run the Flask application: python3 main.py

The project has the following modules:

    Data Collection: This module collects facial images of people for training the model. The images are collected using a web camera and saved in a directory.
    Data Preparation: This module preprocesses the collected images for training the model. The preprocessing steps include face detection, face alignment, and normalization.
    Model Training: This module trains the SVM model using the preprocessed images.
    Model Testing: This module tests the trained model on the test data set and evaluates its performance.
    Application: This module provides a graphical user interface (GUI) for the end-users to interact with the model. The GUI captures an image from a web camera, performs face detection, aligns and normalizes the face, and predicts the gender using the trained SVM model.

Usage

    Open the web application in your browser at http://localhost:5000/.
    Click on the Upload Photo button to upload an image of a person's face.
    Once the image is uploaded, the gender of the person and the highlighted face will be displayed.

Model Training

The models used in this project are stored in the models folder.

Credits

This project was completed as a final year project for an engineering bachelor's degree. It was developed by Satyam Shah. The project was developed using the following libraries:

    Flask
    OpenCV
    NumPy
    Scikit-learn
    Pandas

Future Improvemets

The app can be improved to support videos too.
The user eperience of the application can be improved.
API can be designed based on the application.
