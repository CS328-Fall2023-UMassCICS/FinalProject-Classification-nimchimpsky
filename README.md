## Tennis Racket Swing Classification Model Overview

This project focuses on building a classification model to detect various types of tennis racket swings using accelerometer and gyroscope data collected from phone sensors. The model utilizes data collected through the Sensor Logger App, applies data smoothing techniques with high-pass filters, and employs a random forest classifier for training.

### Dataset Collection

Data for this project was collected using the Sensor Logger App, which records accelerometer and gyroscope data from the phone sensors. The app was configured to capture data during various types of tennis racket swings, including forehand, backhand, serve, and volley.

### Planned Preprocessing

#### Data Cleaning
There exists a lot of erraneous data, that can be considered a mis-prediction when collecting data for testing, such that the usage of a filter of some kind may be necessary(due to lots of hand-swinging).

#### Data Smoothing

Potentially eliminate low-frequency components while preserving the essential swing-related movements captured by the sensors.(Hypothesized)

### Future Improvements (beyond simple classification)

- Exploring advanced signal processing techniques to extract more nuanced swing features.
- Collecting additional labeled data to further enrich the dataset and improve model generalization.
- Adding statistics to maybe guage how properly one's technique is, allowing for better practice

### Usage

To utilize this classification model:

1. **Data Collection:** Use the Sensor Logger App to collect accelerometer and gyroscope data during tennis racket swings.
2. **Data Preprocessing:** Apply necessary cleaning and filtering techniques to the raw data.
3. **Feature Extraction:** Extract relevant features from the preprocessed data.
4. **Model Training:** Utilize the collected codebase to train a Random Forest classifier on extracted features.
5. **Prediction:** Deploy the trained model to classify new instances of tennis racket swings based on sensor data, in realtime hopefully.

