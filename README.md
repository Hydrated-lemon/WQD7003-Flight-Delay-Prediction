# Prediction and Analysis of Flight Delay
This repository contains the code and resources for the project "Prediction of Flight Delay" conducted by Group 3 for the WQD7003: Data Analytics course at the University of Malaya. The relevant Python Notebook is given by `WQD7003_Flight_Delay_Prediction.ipynb`

This project aims to predict and analyze flight delays using data from the U.S. Department of Transportation's (DOT) Bureau of Transportation Statistics and weather data from the National Weather Service. By understanding the contributing factors and predicting delays, we aim to improve air travel reliability and efficiency.

## Team Members
- Lai Yuen Seng (22076493)
- Nur Iffatull Najihah Anuar (17155569)
- Tan Ai Fen (22115538)
- Lin Liy Yee (17007181)
- Lai Jie Xun (22093275)

## Motivation
Flight delays disrupt schedules, cause stress and anxiety, and lead to economic losses for airlines, airports, and passengers. By predicting potential delays, travelers can better manage their schedules, and airlines can optimize operations and improve customer satisfaction.

## Objectives
1. Explore factors contributing to flight delays through exploratory data analysis (EDA).
2. Build a regression model to predict departure delays for flights departing from Dallas/Fort Worth International Airport (DFW), incorporating weather data.

## Dataset
The dataset used in this project is titled “2015 Flight Delays and Cancellations,” available from Kaggle and provided by the U.S. DOT's Bureau of Transportation Statistics at https://www.kaggle.com/datasets/usdot/flight-delays?select=flights.csv. It includes:
- `airlines.csv`: Contains IATA airline codes and names.
- `airports.csv`: Contains airport details including IATA codes, names, and geographical coordinates.
- `flights.csv`: Contains flight summary information including delays, cancellations, and other relevant details.

Additionally, the folder `2015_DFW_Weather.zip` contains weather data at DFW in the year of 2015, obtained from the National Weather Service.

## Methodology
We used the CRISP-DM (Cross-Industry Standard Process for Data Mining) methodology, which includes the following phases:
1. **Business Understanding**: Identifying the business objectives and requirements.
2. **Data Understanding**: Collecting and exploring the dataset.
3. **Data Preparation**: Cleaning and preparing the data for modeling.
4. **Modeling**: Developing regression models to predict flight delays.
5. **Evaluation**: Assessing the models' performance using metrics such as Mean Squared Error (MSE) and R-squared.
6. **Deployment**: Beyond the scope of this project.

## Data Pre-processing
Data pre-processing steps include:
- **Data Cleaning**: Handling missing values and anomalies.
- **Data Transformation**: Encoding categorical variables and scaling numerical features.
- **Feature Selection**: Identifying relevant features for the model.

## Modeling
Several regression models were built and evaluated to predict departure delays. The inclusion of weather data was considered to improve model accuracy.

## Evaluation
The models were evaluated using performance metrics such as Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared.

## References
- [U.S. DOT's Bureau of Transportation Statistics](https://www.transtats.bts.gov/)
- [National Weather Service](https://www.weather.gov/)
- [CRISP-DM methodology](http://www.crisp-dm.org/)

## Conclusion
This project provides insights into the factors contributing to flight delays and demonstrates the potential of predictive modeling to enhance air travel reliability. By incorporating weather data, we aim to improve the accuracy of delay predictions and support better decision-making for travelers and airlines.
