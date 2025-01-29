# Facial Expression Recognition






## Objective
This project is a facial expression recognition system that detects human emotions using a deep learning model. The model is trained to recognize seven different facial expressions: Angry, Disgust, Fear, Happy, Neutral, Sad, and Surprise.

## Features

- Real-time facial expression detection using OpenCV.
- Pre-trained deep learning model for emotion recognition.
- Uses Haar cascades for face detection.
- Processes grayscale images resized to 48x48 pixels.
- Outputs the detected emotion as a label on the video feed.


## Installation

To set up and run this project, follow these steps

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/facial-expression-recognition.git
cd facial-expression-recognition
```

### 2. Install dependencies
Make sure you have Python installed (preferably Python 3.7 or higher). Install the required dependencies using:

```bash
pip install -r requirement.txt
```

### 3. Download model files
Ensure you have the following model files in the project directory:
- `emotiondetector.json` (Model architecture)

-  `emotiondetector.h5`(Model weights)

If these files are missing, place the trained model files in the project folder.


## Usage
Run the facial expression recognition script:

```bash
python emotionread.py
```
This will start the webcam and display a real-time video feed with detected emotions.

    
## Dependencies
The following Python libraries are required (listed in requirement.txt):
- TensorFlow

- Keras

- Pandas

- NumPy

- Jupyter Notebook

- tqdm

- OpenCV (opencv-contrib-python)
## Authors

- [@Abhishekkashayap](https://www.github.com/Abhishekkashayap)
- [@Hraj24](https://www.github.com/Hraj24)
- [@Sagnik-SB](https://www.github.com/Sagnik-SB)

## License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/)
