# Tensorflow Local Custom Object Detection Model Training

## Overview
This repository provides a streamlined workflow for training a custom object detection model using TensorFlow. The dataset (train and test images) is preloaded, and required dependencies are listed in `requirements.txt`. Follow the steps below to set up the environment and start training your model.

## Prerequisites
Ensure you have the following installed before proceeding:
- **Python 3.10.7**
- **Jupyter Notebook**

## Setup Instructions

1. **Install Python 3.10.7** (if not already installed)
2. **Install Jupyter Notebook**
   ```sh
   pip install jupyter
   ```
3. **Create and activate a virtual environment**
   ```sh
   python -m venv tfod
   .\tfod\Scripts\activate  # For Windows
   ```
4. **(Optional) Deactivate the virtual environment**
   ```sh
   deactivate
   ```
5. **Install Jupyter kernel support**
   ```sh
   pip install ipykernel
   ```
6. **Install required dependencies**
   ```sh
   pip install -r requirements.txt
   ```
7. **Add the virtual environment to Jupyter**
   ```sh
   python -m ipykernel install --user --name=tfodj
   ```
8. **Launch Jupyter Notebook**
   ```sh
   jupyter notebook
   ```

## Next Steps
- Navigate to the Jupyter Notebook interface and follow the provided scripts to train your model.
- Ensure that all dependencies are installed properly before running the training scripts.
- Modify and extend the dataset as needed for better model performance.

## Contributions
Feel free to contribute by submitting pull requests or reporting issues.

## License
This project is licensed under the MIT License.

## Contact
For any issues or inquiries, please open an issue in the repository.
