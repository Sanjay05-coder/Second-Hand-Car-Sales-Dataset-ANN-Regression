Second Hand Car Price Prediction using Artificial Neural Networks (ANN)

This project focuses on predicting house prices using an Artificial Neural Network (ANN) built with TensorFlow and Keras. The model learns from various car features to estimate property prices accurately. The data is preprocessed using Min–Max normalization, and the model is trained, validated, and evaluated using standard regression metrics.

The dataset is first cleaned and normalized so that all features are scaled between 0 and 1 using manual Min–Max scaling. The target variable (car price) is also scaled in the same way to help the ANN train efficiently. After prediction, the results are inverse-transformed back to the original scale to interpret the prices in real-world units.

The dataset is divided into training and testing sets to evaluate the model’s performance objectively. The ANN consists of multiple dense layers with ReLU activation functions, and linear activation function since this is a regression problem. The model is compiled using the Adam optimizer with Mean Squared Error (MSE) as the loss function .
