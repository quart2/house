**Multimodal Housing Price Prediction**

**Objective**

To predict housing prices by combining image features from house photos with structured tabular data using a multimodal machine learning approach.

**Methodology / Approach**
**Data Preparation**

Tabular data loaded from house_data.csv and scaled using StandardScaler.

Images (71.jpg, 72.jpg) loaded and resized to 224×224 pixels.

**Feature Extraction**

Used ResNet50 (pre-trained on ImageNet) to extract visual features from images.

Combined extracted CNN features with scaled tabular features.

**Model Training**

Fully connected layers to merge and process multimodal features.

Trained using MSE loss with Adam optimizer.

**Evaluation**

Metrics: Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).

**Key Results / Observations**

Using only 2 samples for testing gave:
MAE: 216,995.09
RMSE: 217,740.35


