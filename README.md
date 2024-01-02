# ML-Project


This project encompassed a broad range of tasks, including regression analysis, data preprocessing, visualization, and classification. In the regression analysis phase, statistical methods were employed to establish the connection between a dependent variable and independent variables with the objective of comprehending and forecasting the dependent variable's value based on predictor variables.

Data preprocessing encompassed actions such as loading the dataset, eliminating irrelevant columns, addressing missing data by substituting them with the mode of corresponding features, and generating bar plots and pie charts to visualize interest rates in relation to different parameters.

Categorical attributes were transformed into numerical values through the use of the "get_dummies" function from the Pandas library. A heatmap was also constructed to explore associations among various features.

Subsequently, the dataset was divided into training and test sets in an 80/20 ratio. A linear regression model was trained on the training data and assessed using metrics like Mean Squared Error (MSE) and R2 score. The model's performance was also tested on the test data, with corresponding MSE and R2 scores being reported. Additionally, an alternative regression model was tested and compared to the linear regressor.

Transitioning to the classification phase, the project's focus shifted to building and training a model capable of classifying composers based on notes and velocities extracted from MIDI files. MIDI files were extracted from the provided root directory, and a mapping was created to associate composer names with numerical values. Notes and velocities were converted into fixed-sized vectors to make them compatible with machine learning algorithms.

Scatter plots were employed to visualize the average velocity and pitch of each song, with composers represented by different colors. The length consistency of features and labels was verified, and the data was split into training and test datasets, with a test size of 0.2.

Finally, a classification model was selected based on its suitability for the task, and this model was trained and evaluated using the f1_score metric on the test features.

In summary, this project entailed an extensive exploration of regression analysis, data preprocessing, visualization, and classification tasks, showcasing a variety of techniques and models to extract insights and make predictions from the provided dataset.
