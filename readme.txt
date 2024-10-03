Deep Learning Project: FCN vs CNN

Introduction to the Problem: This project focuses on predicting wine quality based on chemical properties using the WineQT dataset. The task is a regression problem, where the target is the 'quality' of the wine.

Background Information: Fully Connected Neural Networks (FCNs) are general-purpose models often used for classification and regression tasks. Convolutional Neural Networks (CNNs), typically used for spatial data, are applied here to treat the chemical properties as a 1D sequence for quality prediction.

Dataset Analysis: The WineQT dataset includes chemical properties such as acidity, residual sugar, and pH. The goal is to predict the wine's quality score. Pre-processing steps involved scaling the input features using StandardScaler to normalize the data.

Model Architectures:

    FCN: A fully connected neural network with three layers of 64, 32, and 16 neurons.
    CNN: A convolutional neural network with a 1D convolutional layer followed by two fully connected layers.

Results and Comparison: Both models were evaluated using Mean Absolute Error (MAE). The FCN consistently outperformed the CNN, achieving a lower MAE across all epochs, making it more suitable for this task.

Conclusion: The FCN model was more effective in predicting wine quality than the CNN model. Further improvements could be made by tuning hyperparameters or trying additional architectures.
