# AI_Project_Crop_Yield_Prediction

This is a Crop Yield Predictor project that aims to predict the suitable crops for different weather and soil conditions. The project involves data analysis, visualization, and machine learning techniques to make crop yield predictions based on various factors.

## Dataset

The dataset used for this project is stored in a CSV file named `data.csv`. It contains information about different crops and their corresponding components of soil and weather, such as Nitrogen (N), Phosphorous (P), Potassium (K), temperature, humidity, pH level, and rainfall.

## Data Exploration and Visualization

The project begins with data exploration and visualization to understand the distribution of various components in the dataset. The following plots are created:

- Histograms for Nitrogen, Phosphorous, Potassium, temperature, humidity, pH level, and rainfall.
- Categorization of crops into different seasonal categories (Summer Crops, Winter Crops, Monsoon Crops) based on specific weather conditions.

## Crop-wise Soil and Weather Components

An interactive function is created to summarize the required components of soil and weather for different crops. By selecting a crop from the available options, you can view the maximum, minimum, and average values of each component required for that specific crop.

## Elbow Method and KMeans Clustering

The Elbow Method is used to find the optimal number of clusters for KMeans clustering. After determining the number of clusters, KMeans clustering is performed to group similar crops based on their components of soil and weather.

## Cluster Analysis

The crops are grouped into different clusters based on their similarities in required soil and weather components. The clusters are presented along with the crops they contain.

## Crop Yield Prediction

To predict the crop yield, the dataset is split into training and testing sets. A Logistic Regression model is trained on the training data to predict the crop category. The performance of the model is evaluated using classification report and confusion matrix.

## Prediction of Crops

The trained model is then used to predict the crop category for a sample input of components of soil and weather.

Feel free to explore the code, modify the hyperparameters, or use your own dataset to experiment with different machine learning models and improve the crop yield prediction.

## Author

This Crop Yield Predictor project is authored by [Samadrita_Kar].
