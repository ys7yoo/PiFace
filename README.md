Face tools

Language: Python 3

Targe platform: Raspberry Pi, Ubuntu, OSX

Libraries: Dlib

# Installing Dlib

## Official guideline 

## For Ubuntu

1. Install required packages

```bash
sudo apt-get install build-essential cmake
sudo apt-get install libgtk-3-dev
sudo apt-get install libboost-all-dev
```

2. Set up your virtual environment


3. Install dlib with Python bindings

```bash
pip install dlib
```
See http://www.pyimagesearch.com/2017/03/27/how-to-install-dlib/ for more details.


## For Raspberry Pi

See http://www.pyimagesearch.com/2017/05/01/install-dlib-raspberry-pi/.




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


