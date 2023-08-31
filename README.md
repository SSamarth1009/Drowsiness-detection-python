# Drowsiness Detection Project

This project is aimed at detecting drowsiness in individuals using facial landmarks and computer vision techniques. The program utilizes Python and several libraries, including `imutils`, `dlib`, and `cv2`.

## Project Overview

Drowsiness while driving can be dangerous, and this project aims to address this issue by identifying signs of drowsiness through facial expressions. The script uses the 68 face landmarks shape predictor model from the provided dataset.

## Requirements

- Python (3.x recommended)
- Required libraries: `imutils`, `dlib`, `cv2`, `numpy`

You can install the required libraries using the following command:

pip install imutils dlib opencv-python-headless numpy


## Usage

1. Clone this repository:
git clone https://github.com/yourusername/drowsiness-detection.git
cd drowsiness-detection


2. Download the shape predictor model:
Download the shape predictor model from [here](https://www.kaggle.com/datasets/sergiovirahonda/shape-predictor-68-face-landmarksdat) and place it in the project directory.

3. Run the drowsiness detection script:
python drowsiness_detection.py



4. The script will capture your webcam feed and analyze facial landmarks in real-time.

## Project Structure

- `drowsiness_detection.py`: The main script that captures webcam feed and detects drowsiness.
- `shape_predictor_68_face_landmarks.dat`: The shape predictor model downloaded from the provided Kaggle dataset.

## Acknowledgements

- The shape predictor model dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/sergiovirahonda/shape-predictor-68-face-landmarksdat).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
Remember to replace yourusername with your actual GitHub username in the repository URL and ensure that the file paths and names match your project's structure. Additionally, make sure to include any specific setup instructions or usage details that might be relevant to your project.


