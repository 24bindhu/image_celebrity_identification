## Celebrity Image Recognition

This project demonstrates a celebrity image recognition system using machine learning techniques. The system identifies celebrities from a set of pre-trained images and matches them to input images.

# Features

- Detects and recognizes celebrity faces from a given dataset.
- Uses facial recognition and image processing libraries.
- Implements a classification model to identify celebrities accurately.
- Displays results with matching confidence scores.

# How It Works

1. The model is trained using a dataset containing images of specific celebrities.
2. Input images are processed, and facial features are extracted.
3. The extracted features are compared with the dataset, and the most probable match is identified.
4. The output displays the name of the celebrity along with the confidence score.

# Technologies Used

- Python
- OpenCV
- Face recognition library
- NumPy
- Pandas

# Requirements

To run the project, install the following dependencies:

```bash
pip install opencv-python face-recognition numpy pandas

**How to Run**
1. Install the required libraries: `pip install -r requirements.txt`.
2. Run the application with: `python main.py`.

**Potential Improvements**
Expand the dataset with more celebrity images to improve accuracy.
Optimize the model for faster processing.
Add a GUI for a more user-friendly experience.



