# PSTAF: Prediction System for Traffic Accident Fatalities

## Project Description
**PSTAF (Prediction System for Traffic Accident Fatalities)** is a machine learning-based project designed to predict the probability of fatalities in traffic accidents based on various factors such as vehicle count, accident location, driver status, weather conditions, and more. This project analyzes traffic accident data to help improve road safety by forecasting high-risk scenarios.

## Features
- In-depth statistical analysis of traffic accident data
- Uses logistic regression to predict possible fatalities in crashes
- Data processing and correlation heatmaps to evaluate relationships between various attributes
- Provides high accuracy in predictions (~92.99%)
- Predicts the impact of drunk driving on traffic fatalities

## Data Preprocessing
- The dataset used in this project includes 81 features connected to various vehicle and geographic aspects of accidents.
- The majority of data comes from U.S. traffic accident records, and redundant or unnecessary features (such as timestamps and case IDs) are dropped to refine the prediction models.
- Cleaned and processed data is ready for training and evaluation.

## Model Description
- **Algorithm**: The model is based on Logistic Regression, trained using a 70/30 train-test split with a dataset of 35,766 entries and 13 relevant features.
- **Prediction Features**:
   - Vehicle forms submitted
   - The number of persons involved
   - Drunk driving involvement
   - Location (city, county, latitude, longitude)
   - National Highway System (NHS) status, day of the week, and time of day.

## Performance
- **Accuracy**: 92.99%
- **MSE**: 0.133
- **R-squared**: 0.059

## Installation
To install and run this project:

1. Clone the repository.
   ```bash
   git clone https://github.com/kaltisami/pstaf.git
   ```

## Usage
1. **Load the Data**: 
   Place the accident dataset (`accident.csv`) in the project directory.
   
2. **Run the Model**:
   Run the Notebook Open the notebook file in Jupyter Notebook to explore the code and results.

3. **Predict Fatalities**: 
   The system allows you to test the prediction model by inputting new traffic accident data manually or via a file. The output will estimate the likelihood of fatality [Page 6].

The system will output the number of persons is in fatal danger based on the inputs .

## Acknowledgements
The data used in this project is derived from publicly available U.S. traffic accident reports, and the development was carried out by **Sami Kalti** .

## License
This project is licensed under the MIT License.
