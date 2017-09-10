Face tools

Language: Python 3

Targe platform: Raspberry Pi, Ubuntu, OSX

Libraries: Dlib



# Face detection using Dlib
0. Install Dlib
 
1. Run the example code:
    ```bash
    python3 face_detector.py [IMAGE-FILE-NAME]
    ```
    
# Facial landmark detection using Dlib

0. Install Dlib
1. Get a pre-trained model: 
    ```bash 
    wget http://dlib.net/files/shape_predictor_68_face_landmarks.dat.bz2
    bunzip2 shape_predictor_68_face_landmarks.dat.bz2 
    ```
 
2. run the example code 
    ```bash
    python3 face_landmark_detection.py shape_predictor_68_face_landmarks.dat [IMAGE_FILE_NAME]
    ```

# Other Dlib python examples

https://github.com/davisking/dlib/tree/master/python_examples


