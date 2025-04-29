Age and Gender Detection Project

This is a basic computer vision project that detects the age and gender of a person using their webcam image, based on deep learning models and OpenCV.


---

How to Run the Project

1. Clone or Download the Repository

GitHub Link: https://github.com/sandeephaldkar01/age-gender-detection

Use the green "Code" button to download as ZIP, or run this command in terminal:


git clone https://github.com/sandeephaldkar01/age-gender-detection.git

2. Install Requirements

Make sure you have Python 3.x installed. Then install the required Python libraries:

pip install opencv-python numpy

3. Run the Jupyter Notebook

jupyter notebook

Open detection.ipynb

Run all the cells one-by-one


4. Allow Webcam Access

Make sure your webcam is working. The model will use it to capture your image and predict age and gender.


---

Files in the Repository

detection.ipynb: Jupyter Notebook that runs the detection script

age_net.caffemodel / gender_net.caffemodel: Pretrained age & gender models

age_deploy.prototxt / gender_deploy.prototxt: Network definitions for the models

opencv_face_detector.pbtxt / .pb: OpenCV DNN-based face detector



---

Output

After running the notebook, the webcam window will open and display the age and gender prediction for any detected face.


---

Author

Sandeep Haldkar

This is my first machine learning project using deep learning and OpenCV.









