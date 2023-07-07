# Short-Term Rainfall Cell Forecasting using Machine Learning Techniques
CIVE97003 Individual Research Project

## Problem Statement
Climate change has led to increased rainfall intensities, exacerbating the risk of flooding. Current forecasting models use physical or data-driven approaches, with data-driven models gaining popularity due to their ability to capture statistical relationships. Traditional statistical models like ARIMA have limitations in predicting sudden changes and skewed distributions. Machine Learning (ML) models, particularly Convolutional Neural Networks (CNNs), are proposed for rainfall forecasting using historical rainfall images. The research aims to investigate the effectiveness of CNNs trained on historical rainfall images alone and in combination with climatological data, with the latter being a novel approach. By identifying areas susceptible to high rainfall, this research can contribute to the development of accurate rainfall forecasting models and effective flood prediction systems.

## Methodology and Approach
First, preprocessing was conducted to extract the rainfall images corresponding to each of the 157 historical storm events. Each image was a 110km x 110km image, with each pixel representing a 1km x 1km grid area. Then, for any pixels within each image that are considered "anomalous", they are replaced by the spatially average rainfall intensities from the surrounding 8 pixels. This process was repeated for all 157 historical storm events.

Then, 
