# Human Activity Recognition using Machine Learning

This repository contains Python code for a deep learning model to recognize human activities using sensor data. The model combines LSTM and Convolutional layers to process sensor readings and classify activities such as walking, running, sitting, etc.

## Dataset
The dataset used for this project is the WISDM (Wireless Sensor Data Mining) dataset. It contains sensor data collected from smartphones while users perform different activities. The dataset includes accelerometer readings in three dimensions (X, Y, Z) along with corresponding activity labels.

## Code Structure
- `activity_recognition.py`: Python script containing the complete code for data preprocessing, model building, training, and evaluation.
- `WISDM_ar_v1.1_raw.txt`: Raw sensor data file (not included in this repository).
- `README.md`: This file providing an overview of the project and instructions for usage.

## Usage
1. Clone the repository:
git clone https://github.com/your_username/Activity-Recognition-Deep-Learning.git

2. Install the required dependencies:
pip install pandas scipy scikit-learn keras matplotlib

3. Run the `activity_recognition.py` script to preprocess the data, train the model, and evaluate its performance.
## References
- [WISDM Dataset](https://www.cis.fordham.edu/wisdm/)
- [Keras Documentation](https://keras.io/)
- [Scikit-Learn Documentation](https://scikit-learn.org/stable/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)

