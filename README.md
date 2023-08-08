# Heart Disease Prediction

## Description
This code is designed to predict the presence of heart disease in individuals based on various health indicators. The dataset contains health characteristics that serve as indicators, providing insights into the health status of individuals. 
The primary challenge is to utilize these indicators to accurately predict whether a given subject has been diagnosed with any of the three age-related conditions. The task is framed as a binary classification problem, with two possible outcomes: 

- the subject has been diagnosed with one of the conditions
- the subject has not been diagnosed with any of the conditions.

The data has been meticulously curated to ensure anonymity, preserving the privacy of the individuals while still retaining the essential features required for effective prediction.

## Code
The code begins by importing necessary libraries for data analysis and modeling. It then proceeds to read the dataset, check for null values, and visualize the data. The data is then split, and various models are listed for selection. The best models are chosen based on their performance, and hyperparameters are tuned for these models. The best parameters of the best models are then used on unseen data to get accuracy scores. Additionally, the order of feature importance is determined to understand which features play a significant role in the prediction.

This code emphasizes the importance of understanding the underlying patterns within the data, which could potentially lead to better diagnostic tools or interventions for age-related conditions in the future.

[Code](Heart_Disease.ipynb)

## License

This script is open-source and licensed under the MIT License. For more details, check the [LICENSE](LICENSE) file.
