# Deepfake-Fake-Detection

## Introduction
Deepfake technology enables the creation of highly realistic AI-generated videos using techniques like Generative Adversarial Networks (GANs) and Auto Encoders. This project focuses on detecting deepfake videos using deep learning methods, specifically leveraging Convolutional Neural Networks (CNNs) and Long Short-Term Memory (LSTM) networks.

## Project Overview
The system utilizes a **Res-Next Convolutional Neural Network (CNN)** to extract frame-level features and trains an **LSTM-based Recurrent Neural Network (RNN)** to classify whether a video is real or deepfake. The model is trained on a combination of available datasets to improve real-time detection performance.

## Features
- Deepfake video detection using **CNN and LSTM**
- Frame-level feature extraction with **Res-Next CNN**
- Sequence processing with **LSTM** for temporal analysis
- Web-based interface built using **Django**
- Secure video processing with **encryption**

## Technologies Used
- **Deep Learning** (PyTorch, TensorFlow)
- **Computer Vision** (OpenCV, Face Recognition)
- **Neural Networks** (CNN, LSTM, GAN)
- **Web Framework** (Django)
- **Cloud Computing** (Google Cloud Platform)

## System Requirements
### Hardware
- **Processor**: Intel Xeon E5 2637 @ 3.5 GHz
- **RAM**: 16GB
- **Storage**: 100GB
- **GPU**: NVIDIA GeForce GTX (12GB RAM)

### Software
- **Operating System**: Windows 7+
- **Programming Language**: Python 3.0+
- **Frameworks**: PyTorch 1.4, Django 3.0
- **Libraries**: OpenCV, Face-recognition

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/deepfake-detection.git
   ```
2. Navigate to the project directory:
   ```sh
   cd deepfake-detection
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run the Django server:
   ```sh
   python manage.py runserver
   ```
5. Open your browser and go to `http://127.0.0.1:8000/` to use the application.

## Usage
1. **Upload a video** using the web interface.
2. The system processes the video frame-by-frame.
3. The trained model classifies the video as **Real or Fake**.
4. The output includes confidence scores and highlights detected deepfake artifacts.

## Results
- The model can process **1 second of video at 10 frames per second**.
- Achieves high accuracy by leveraging **Res-Next CNN and LSTM**.

## Future Enhancements
- Develop a **browser plugin** for real-time deepfake detection.
- Expand detection capabilities beyond facial deepfakes to **full-body deepfakes**.
- Improve detection accuracy with additional training datasets.

## Contributing
Feel free to contribute to this project! Fork the repository and submit a pull request with improvements.

## License
This project is licensed under the **MIT License**.

## Contact
For any queries, contact **hariprasanth7oct@gmail.com** or open an issue in the repository.

---
**GitHub Repository:** [https://github.com/your-username/deepfake-detection](https://github.com/your-username/deepfake-detection)

