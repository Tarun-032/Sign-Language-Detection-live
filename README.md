## Sign Language Detection live

This repository contains the code for a **live sign language detector** built using deep learning with TensorFlow and OpenCV. The project focuses on recognizing five basic signs: **yes, no, thank you, hello, and I love you.**

**Features:**

* Real-time detection of the five specified signs from webcam or video feed.
* Utilizes convolutional neural networks (CNNs) trained on a custom dataset of annotated images.
* Provides visual feedback on the detected sign.

**Development Stack:**

* Python 3.9.8
* TensorFlow Object Detection API
* OpenCV
* scikit-learn
* lxml

**Project Steps:**

1. **Data Collection:** Images of each sign were collected and annotated using LabelImg.
2. **Model Training:** A CNN model was trained on the annotated dataset using TensorFlow.
3. **Inference:** The trained model was integrated with OpenCV for real-time sign detection from live video.

**Getting Started:**

1. **Clone the repository:** `git clone https://github.com/your-username/live-sign-language-detector`
2. **Set up the Anaconda environment:**
    * Create an environment with TensorFlow and other dependencies.
    * Activate the environment: `source activate env_name`
3. **Install the TensorFlow Object Detection API:**
    * Follow the instructions here: [https://github.com/tensorflow/models/tree/master/research/object_detection](https://github.com/tensorflow/models/tree/master/research/object_detection)
4. **Run the application:**
    * Modify the script based on your specific input and output setup.
    * Execute the script: `python main.py`
      

**Resources**
Anaconda: https://repo.anaconda.com/archive
Visual Studio: https://visualstudio.microsoft.com/vs...
CUDA 10.1: https://developer.nvidia.com/cuda-10....
CUDNN 7.6.5: https://developer.nvidia.com/rdp/cudn...
Protoc: https://github.com/protocolbuffers/pr...
Tensorflow Models GitHub: https://github.com/tensorflow/models

**Additional Information:**

* This project is a college project and still under development.
* Feel free to contribute or suggest improvements.
* The model accuracy could be further improved with larger datasets and advanced training techniques.



