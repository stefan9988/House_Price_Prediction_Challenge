This project focuses on predicting housing prices in India using a provided dataset.

The Data_preprocessing.ipynb file contains code that performs data analysis and cleansing. It is divided into four main parts:

    Data Preprocessing: This section aims to gain a better understanding of the data and convert categorical features into numerical representations.

    Data Visualization: Here, the project visualizes the relationships between housing prices and other features. This includes presenting dependencies and showcasing the data distribution through histograms.

    Outlier Removal: The outlier removal part identifies and eliminates outliers from the dataset, resulting in a clean and reliable representation of the data.

    Normalization: After the outlier removal, the project executes normalization to standardize the data, making it suitable for further analysis and modeling. The cleaned and normalized data is then saved for subsequent use.


The Models.ipynb file is responsible for model development. It splits the data into training and test subsets and creates eight models specifically designed to address the regression problem. The steps involved are as follows:

    Data Splitting: The file partitions the dataset into training and test subsets, ensuring proper evaluation and validation of the models.

    Model Creation: Eight different models are developed to tackle the housing price prediction problem. Each model is tailored to address specific challenges and capture the complexity of the real estate market.

    Model Evaluation: After training the models, the project compares and presents the results of each model. 

To ensure ongoing performance evaluation, the project implements a monitoring mechanism. In this process:

    The predicted values of all models and the mean predicted value are separated into 40 identical subsets.

    Simulated monitoring is conducted on these subsets to track the models' performance over time. This helps identify any potential issues or deviations in predictive accuracy.