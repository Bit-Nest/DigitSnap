# Handwritten Number Recognition System

# Extension of the Digit Recognition (DeciEngine)
This project provides a Flask-based web application for real-time handwritten digit recognition using a Convolutional Neural Network (CNN) model trained on the MNIST dataset. The system allows users to upload images of handwritten digits and get predictions for the full number (e.g., "1234") instead of just individual digits.

## Features

- **Handwritten Digit Recognition:** Upload an image of a handwritten digit or number, and the system predicts the full number.
- **Full Number Detection:** The system detects and recognizes multiple digits from a single image and aggregates them to show the full number.
- **Responsive User Interface:** The application features a clean and modern UI that is fully responsive.
- **Deployed on AWS EC2:** The application is hosted on AWS EC2 for global accessibility.
- **Future Enhancements:** Planned features include alphanumeric character recognition, mobile app integration, and real-time handwriting conversion.

## Requirements

To run the project, the following Python libraries are required:

- Flask
- TensorFlow
- Pillow (for image processing)
- OpenCV (for image contour detection)
- NumPy

These dependencies are listed in `requirements.txt` and can be installed using `pip`.

## Setup and Installation

### 1. Clone the Repository

Clone the repository to your local machine:

```bash
git clone https://github.com/Ketan-Chaudhary/deci-engine.git
```

## Future Work

### Here are some planned enhancements for the system:
- Alphanumeric Character Recognition: Extend the model to recognize both numbers and letters (alphanumeric recognition).
- Mobile Application Integration: Allow users to interact with the system via a mobile app.
- Real-Time Handwriting Conversion: Implement real-time handwriting recognition, where users can draw characters directly on the screen, and the system will convert the handwriting into digital text.