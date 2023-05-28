# Face Recognition

This repository contains code for face detection and recognition using OpenCV and Python.

## Folder Structure

- **face_detection**: Contains files for face detection, including subfiles for detecting face, smile, and eyes.
  - **cascades**: Contains XML files used for cascade classifiers in face detection.
    - haarcascade_eye.xml
    - haarcascade_frontalface_default.xml
    - haarcascade_smile.xml

- **face_recognition**: Includes files related to face recognition.
  - **face_dataset**: Holds the dataset of facial images used for training and recognition.
  - **training**: Contains the Python script for training the face recognition model using the dataset.
  - **recognition**: Includes the Python script for recognizing faces using the trained model.

## Usage

1. Clone the repository to your local machine using the following command:

   ```
   git clone https://github.com/your-username/Face-Recognition.git
   ```

2. **Face Detection**: The `face_detection` folder contains multiple subfiles for face, smile, and eyes detection. You can use these files to perform face detection on images or video streams.

3. **Face Recognition**: The `face_recognition` folder contains the necessary files for face recognition.
   - **Dataset**: Add your facial images to the `face_dataset` folder for training and recognition purposes.
   - **Training**: Execute the `training.py` script to train the face recognition model using the dataset.
   - **Recognition**: Run the `recognition.py` script to recognize faces using the trained model.

Note: Before running the code, ensure that you have the required dependencies, such as OpenCV and Python, installed on your system.

## License

This project is licensed under the MIT License. Feel free to use and modify the code as per your needs.

## Acknowledgments

The code in this repository is built upon the foundations of OpenCV and various tutorials and resources available online. Special thanks to the open-source community for their contributions.

If you have any questions or suggestions, feel free to reach out or open an issue in the repository. Enjoy face recognition!

