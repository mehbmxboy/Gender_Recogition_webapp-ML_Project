<h1> Machine Learning Project -Human Gender Classification using Facial Recognition </h1>

This is a machine learning project that uses Support Vector Machines (SVM) and Haar Cascade Classifiers to classify gender based on facial recognition. The frontend of the project application is built using Flask. All the trained models are kept in the models folder. The user can upload a photo into the application and the resulting output will show the gender and highlighted face.

This project was completed as the final year project for an engineering bachelor's degree.

Installation

To run this project, follow these steps:
<ul>
    <li>Clone the repository to your local machine.</li>
    <li>Run the Flask application: </li> `$ python3 main.py `  
</ul>
The project has the following modules:
<ul>
    <li>Data Collection: This module collects facial images of people for training the model. The images are collected using a web camera and saved in a directory.</li>
    <li>Data Preparation: This module preprocesses the collected images for training the model. The preprocessing steps include face detection, face alignment, and normalization.</li>
    <li>Model Training: This module trains the SVM model using the preprocessed images.</li>
    <li>Model Testing: This module tests the trained model on the test data set and evaluates its performance.</li>
    <li>Application: This module provides a graphical user interface (GUI) for the end-users to interact with the model. The GUI captures an image from a web camera, performs face detection, aligns and normalizes the face, and predicts the gender using the trained SVM model.</li>
</ul>
Usage
<ul>
    <li>Open the web application in your browser at http://localhost:5000/.</li>
    <li>Click on the Upload Photo button to upload an image of a person's face.</li>
    <li>Once the image is uploaded, the gender of the person and the highlighted face will be displayed.</li>
</ul>
Model Training

The models used in this project are stored in the models folder.

Credits

This project was completed as a final year project for an engineering bachelor's degree. It was developed by Satyam Shah. The project was developed using the following libraries:
<ul>
    <li>Flask</li>
    <li>OpenCV</li>
    <li>NumPy</li>
    <li>Scikit-learn</li>
    <li>Pandas</li>
</ul>
Future Improvemets

The app can be improved to support videos too.
The user eperience of the application can be improved.
API can be designed based on the application.
