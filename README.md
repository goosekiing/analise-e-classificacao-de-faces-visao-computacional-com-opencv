# Análise e Classificação de Faces: Visão Computacional com OpenCV

This repository contains a project focused on face analysis and classification using the OpenCV and dlib libraries.

## Project Overview

### Part 1: Face Detection with OpenCV
A simple project that uses an OpenCV classifier (available at [OpenCV Haarcascades](https://github.com/kipr/opencv/tree/master/data/haarcascades)) to detect faces in images.

### Part 2: Face Recognition with OpenCV
This part involves the identification of 50 individuals with 15 images of each person's face. These images undergo preprocessing to standardize their sizes and convert them to a single color channel (grayscale). The preprocessed images are then used in Eigenface, Fisherfaces, and LBPH classification models available in the OpenCV library to identify individuals, achieving an accuracy of approximately:
- **Eigenface:** 72%
- **Fisherfaces:** 52%
- **LBPH:** 79%

### Part 3: Facial Landmark Detection with dlib
Using the dlib library to detect 68 facial landmarks, which outline the contours of the face, mouth, nose, eyes, and eyebrows. With these landmarks, relationships such as the opening of the eyes or mouth can be tracked in real-time videos, useful for facial expression recognition and image filter applications.

### Exercises
The project includes the resolution of three exercises proposed during the course:
1. Capturing images of the user's face, training a model to recognize it, and using a computer-connected camera (webcam) for real-time facial recognition.
2. Using the webcam to identify the user's facial landmarks in real-time.
3. Tracking the user's mouth opening to count the number of yawns performed while the code is running.

## Course Details
This project was completed as part of the 'Computer Vision with OpenCV' course on Alura. For more information about the course, visit [Alura](https://cursos.alura.com.br/formacao-visao-computacional-opencv).

## Objectives Achieved
- Be capable of extracting regions of interest from an image.
- Normalize and preprocess image datasets.
- Build classifiers for face recognition.
- Validate the accuracy of the constructed model for real-world applications.
- Extract facial regions based on landmarks.
- Create applications that analyze different conditions of each facial component.

## Technologies Used
- Python (v3.8.10)
- Jupyter Notebook
- OpenCV (cv2 v3.4.8)
- Matplotlib
- Numpy
- Scikit-learn
- Shutil
- Scipy
- Dlib (v19.22.99)
- Io
- IPython
- PIL

## Project Structure
The directory structure of the project is as follows:
```
analise-e-classificacao-de-faces-visao-computacional-com-opencv/
│
├── data/ (data files directory)
├── ex_04.ipynb
├── ex_05.ipynb
├── ex_06.ipynb
├── project-10.ipynb
├── project-11.ipynb
├── project-12.ipynb
└── README.md
```

## Setup Instructions
1. Clone the repository:
   ```sh
   git clone https://github.com/goosekiing/analise-e-classificacao-de-faces-visao-computacional-com-opencv.git
   ```
2. Navigate to the project directory:
   ```sh
   cd analise-e-classificacao-de-faces-visao-computacional-com-opencv
   ```
3. Create a virtual environment and activate it:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```
4. Install the required libraries:
   ```sh
   pip install opencv-python==3.4.8 matplotlib numpy scikit-learn shutil scipy dlib==19.22.99 ipython pillow
   ```

## Running the Notebooks
1. Open Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
2. Run the notebooks (`ex_04.ipynb`, `ex_05.ipynb`, `ex_06.ipynb`, `project-10.ipynb`, `project-11.ipynb`, `project-12.ipynb`) to see the different parts of the project in action.

## Facial Landmark Predictor
The project uses the `shape_predictor_68_face_landmarks` file to identify facial landmarks. This file is not included in the repository but can be downloaded from [here](https://github.com/italojs/facial-landmarks-recognition/blob/master/shape_predictor_68_face_landmarks.dat).

## Language
The language used in this project is Brazilian Portuguese (pt-br).

## Author
GitHub Username: [goosekiing](https://github.com/goosekiing)
