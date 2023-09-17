# Financial crisis prediction
> This research aims to develop a new predictive modeling framework that uses advanced feature engineering techniques, deep learning models with attention mechanisms, that are trained on newer version of macro history data to improve the accuracy, reliability, and interpretability of financial crisis prediction models and also to explore the potential of utilizing the entire time series information. This will help policymakers, regulators, and financial institutions make better decisions and manage risk more effectively.


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)


## General Information
Financial crises have significant implications for economies, businesses, and individuals worldwide. Predicting and mitigating financial crises is a critical concern for policymakers, regulators, and financial institutions. Traditional methods and models often struggle to capture the complexities and dynamic nature of financial markets, leading to limitations in accurate crisis prediction. However, the advent of machine learning techniques has provided promising avenues to overcome these challenges.
Therefore, there is a need to develop an advanced predictive modeling framework that incorporates advanced feature engineering techniques, advanced deep learning models with attention mechanisms, this mechanism can be used to identify important features or time steps in the historical financial data that contribute significantly to predicting the occurrence of a financial crisis. This model can effectively capture the underlying patterns and dependencies that lead to financial crises. Additionally, a newer version of macro history data (Jordà et al., 2017) version 6 includes 18 advanced economic countried including ireland and some newer columns.


#### Buisness Goal
*	To investigate the potential of utilizing advanced feature engineering techniques in improving the predictive accuracy of financial crisis prediction models.

*	To develop and evaluate advanced deep learning models, such as LSTM (Long Short-Term Memory) and RNN (Recurrent Neural Network), integrated with attention mechanisms for capturing important features and time steps in historical financial data that significantly contribute to predicting the occurrence of financial crises.

*	To analyze the effectiveness of incorporating the attention mechanism in deep learning models for identifying complex patterns and dependencies that lead to financial crises.

*	To assess the impact and significance of utilizing the updated version 6 of macro history data, including data on long-run bank capital ratios, loan-to-deposit ratios, and other new features, in developing more robust financial crisis prediction models.


## Conclusions
XGBoost emerged as the most potent predictive model, setting new benchmarks in accuracy, AUC scores, and MCC, thereby highlighting the model's robustness in predicting financial crises. In terms of key predictors, this study corroborates the significance of specific variables like Consumption_to_GDP_Ratio, Interest_Rate_Spread, Investment_Fluctuation, and Economic_Growth_Rate. Their high ranking in Recursive Feature Elimination demonstrates their critical role in the predictive models, adding layers of complexity and depth to crisis prediction. This complements existing literature, which has traditionally focused on variables like credit growth and yield curves.

## Technologies Used
- Python 3
- Numpy
- Pandas
- Seaborn
- Matplotlib
- scikit-learn


## Acknowledgements
- This project was done as an research for LJMU-Masters program


## Contact
Created by <br>
<a href="https://github.com/cskn1097">@cskn1097</a> - - feel free to contact me! <br>
