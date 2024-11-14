### IBM-DATA-SCIENCE-COURSE

# Weather Prediction Classification Models

## Overview of the Project

In this project, we will implement several **classification algorithms** to predict the likelihood of rain the next day based on weather data. The goal is to create a model using various classification algorithms, train it with our dataset, and evaluate its performance on testing data using various evaluation metrics.

### Algorithms Used:
- **Linear Regression**
- **K-Nearest Neighbors (KNN)**
- **Decision Trees**
- **Logistic Regression**
- **Support Vector Machine (SVM)**

### Evaluation Metrics:
- **Accuracy Score**
- **Jaccard Index**
- **F1-Score**
- **LogLoss**
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **R2-Score**

---

## About the Dataset

The dataset used in this project was gathered from the **Australian Government's Bureau of Meteorology**. The original data source is available [here](http://www.bom.gov.au/climate/dwo/).

The dataset includes weather-related observations collected daily from **2008 to 2017** and is available in the `weatherAUS.csv` file. This dataset contains additional columns like 'RainToday' and the target column 'RainTomorrow', which are used for the classification task.

The data is accessed from the **Rattle repository** via [this link](https://bitbucket.org/kayontoga/rattle/src/master/data/weatherAUS.RData).

### Dataset Fields:

| Field             | Description                                                     | Unit                | Type   |
|-------------------|-----------------------------------------------------------------|---------------------|--------|
| **Date**          | Date of the observation in YYYY-MM-DD format                    | Date                | Object |
| **Location**      | Location of the observation                                     | Location            | Object |
| **MinTemp**       | Minimum temperature                                             | Celsius             | Float  |
| **MaxTemp**       | Maximum temperature                                             | Celsius             | Float  |
| **Rainfall**      | Amount of rainfall                                              | Millimeters         | Float  |
| **Evaporation**   | Amount of evaporation                                           | Millimeters         | Float  |
| **Sunshine**      | Amount of bright sunshine                                       | Hours               | Float  |
| **WindGustDir**   | Direction of the strongest wind gust                            | Compass Points      | Object |
| **WindGustSpeed** | Speed of the strongest wind gust                                | Kilometers/Hour     | Object |
| **WindDir9am**    | Wind direction averaged for 10 minutes before 9am               | Compass Points      | Object |
| **WindDir3pm**    | Wind direction averaged for 10 minutes before 3pm               | Compass Points      | Object |
| **WindSpeed9am**  | Wind speed averaged for 10 minutes before 9am                   | Kilometers/Hour     | Float  |
| **WindSpeed3pm**  | Wind speed averaged for 10 minutes before 3pm                   | Kilometers/Hour     | Float  |
| **Humidity9am**   | Humidity at 9am                                                 | Percentage (%)      | Float  |
| **Humidity3pm**   | Humidity at 3pm                                                 | Percentage (%)      | Float  |
| **Pressure9am**   | Atmospheric pressure at 9am (reduced to mean sea level)        | Hectopascal         | Float  |
| **Pressure3pm**   | Atmospheric pressure at 3pm (reduced to mean sea level)        | Hectopascal         | Float  |
| **Cloud9am**      | Fraction of the sky obscured by cloud at 9am                    | Eights              | Float  |
| **Cloud3pm**      | Fraction of the sky obscured by cloud at 3pm                    | Eights              | Float  |
| **Temp9am**       | Temperature at 9am                                              | Celsius             | Float  |
| **Temp3pm**       | Temperature at 3pm                                              | Celsius             | Float  |
| **RainToday**     | Whether it rained today (Yes/No)                                | Yes/No              | Object |
| **RainTomorrow**  | Whether it will rain tomorrow (target variable)                | Yes/No              | Float  |

