# GestuSpeak: Real-time Sign Language Detection using Machine Learning

**GestuSpeak** is an innovative project aimed at bridging communication gaps by enabling real-time sign language detection from A to Z and 0 to 1. This repository hosts the machine learning model, training code, and the necessary resources to empower seamless communication for individuals using sign language.

## Features
- *Real-time Detection:* Experience instant sign language recognition for a comprehensive set of gestures, covering the alphabet from A to Z and numbers from 0 to 1.
- *User-Friendly Interface:* An intuitive and easy-to-use interface for smooth interaction, making communication accessible to everyone.
- *Machine Learning Model:* Leveraging state-of-the-art machine learning techniques, our model ensures accurate and efficient sign language interpretation.
- *Customizable and Extensible:* Tailor the model to specific requirements or expand its capabilities by adding new signs.

## Project Directory Structure

- **GestuSpeak_Project**
  - **data**
    - **raw**
      - class1
        - image1.jpg
        - image2.jpg
        - ...
      - class2
        - image1.jpg
        - image2.jpg
        - ...
      - ...
    - **processed**
      - **train**
        - class1
          - image1.jpg
          - image2.jpg
          - ...
        - class2
          - image1.jpg
          - image2.jpg
          - ...
        - ...
      - **test**
      - **validation**
  - **models**
    - trained_model.h5
  - **notebooks**
    - exploratory_analysis.ipynb
    - model_training.ipynb
    - model_evaluation.ipynb
  - **src**
    - data_preprocessing.py
    - model.py
    - train.py
    - predict.py
  - requirements.txt
  - README.md


## Getting Started
1. **Clone the repository:** `git clone https://github.com/your-username/GestuSpeak.git`
2. **Install dependencies:** `pip install -r requirements.txt`
3. **Run the application:** `python app.py`

## Contributing
We welcome contributions from the community! Whether you're interested in improving the model,enhancing the user interface, or adding new features, your input is valuable.

## License
This project is licensed under the MIT License 

Let's make communication inclusive and accessible for everyone with **GestuSpeak**!
