## Tennis Racket Swing Classification Model Overview

This project focuses on building a classification model to detect various types of tennis racket swings using accelerometer and gyroscope data collected from phone sensors. The model utilizes data collected through the Sensor Logger App, applies data smoothing techniques with high-pass filters, and employs a random forest classifier for training.

### Dataset Collection

Data for this project was collected using the Sensor Logger App, which records accelerometer and gyroscope data from the phone sensors. The app was configured to capture data during various types of tennis racket swings, including forehand, backhand, serve, and volley.

### Planned Preprocessing

#### Data Cleaning

Raw sensor data often contains noise and irregularities. To ensure quality, the collected data underwent cleaning processes to remove outliers and erroneous readings.

#### Data Smoothing

High-pass filters were applied to the data to smooth out noise and eliminate low-frequency components while preserving the essential swing-related movements captured by the sensors.

### Future Improvements

- Exploring advanced signal processing techniques to extract more nuanced swing features.
- Experimenting with different machine learning algorithms to potentially improve classification accuracy.
- Collecting additional labeled data to further enrich the dataset and improve model generalization.

### Usage

To utilize this classification model:

1. **Data Collection:** Use the Sensor Logger App to collect accelerometer and gyroscope data during tennis racket swings.
2. **Data Preprocessing:** Apply necessary cleaning and filtering techniques to the raw data.
3. **Feature Extraction:** Extract relevant features from the preprocessed data.
4. **Model Training:** Utilize the provided codebase to train the Random Forest classifier on your extracted features.
5. **Prediction:** Deploy the trained model to classify new instances of tennis racket swings based on sensor data.

### Acknowledgments

This project may have been made possible with the use of all traditional Python data processing libraries or any other resources used.
