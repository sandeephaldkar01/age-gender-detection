 # Age and Gender Detection using OpenCV (Offline in VS Code)

This project detects the age and gender of a person using pre-trained deep learning models with OpenCV.

---

## Step 1: Install Python

1. Download Python from [https://www.python.org/downloads](https://www.python.org/downloads)
2. Run the installer and *check the box that says “Add Python to PATH”*
3. Open Command Prompt and verify installation:
   ```bash
   python --version


---

Step 2: Install Visual Studio Code (VS Code)

1. Download from https://code.visualstudio.com


2. Install and open VS Code.




---

Step 3: Install VS Code Extensions

Open VS Code and install the following extensions:

Python (by Microsoft)

Jupyter (by Microsoft)


Use the Extensions icon on the left sidebar.


---

Step 4: Open the Project

1. Extract the ZIP file you received.


2. Open VS Code → Go to File > Open Folder → Select the extracted folder.


3. Make sure the following files are present:

detection.ipynb

age_net.caffemodel

gender_net.caffemodel

age_deploy.prototxt

gender_deploy.prototxt

opencv_face_detector.pbtxt

opencv_face_detector_uint8.pb





---

Step 5: Create and Activate a Virtual Environment (Optional but Recommended)

Open terminal in VS Code (Ctrl + backtick or Terminal > New Terminal), then run:

python -m venv venv

Activate it (Windows):

venv\Scripts\activate


---

Step 6: Install Required Packages

In the terminal, run:

pip install opencv-python numpy


---

Step 7: Run the Notebook

1. In the Explorer sidebar, double-click detection.ipynb


2. It will open in notebook format with Run buttons.


3. Click the Run button next to each code cell to execute the code step by step.




---

Notes

Do NOT use Google Colab or online Jupyter; this project runs fully offline.

Make sure all required model files are in the same folder.

If any module is missing, install it using pip install <module-name>



---

Happy Coding!

---
