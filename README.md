# Web Authentication Anomaly Detection

## Project Overview
This repository contains projects aimed at detecting anomalies in web authentication systems using both supervised and unsupervised machine learning techniques. These projects help enhance security by identifying unusual activities that might indicate unauthorized access attempts or system failures. The current repository includes a Jupyter notebook detailing the supervised approach, with plans to add another for the unsupervised approach.

## Repository Structure
- `Supervised_AD_Analysis.ipynb`: A Jupyter notebook that implements multiple supervised learning approaches to detect anomalies in synthetic web authentication data.
- `data/`: Directory containing synthetic datasets used for training and testing the models.

## Dataset Description
The dataset used in this project consists of synthetic web authentication logs designed to simulate real-world web security scenarios. Each record in the dataset represents a single login attempt with the following features:

- **User ID**: A unique identifier for each user.
- **Timestamp**: The date and time of the login attempt.
- **Login Status**: Indicates success or failure of the login attempt.
- **IP Address**: The IP address from which the login attempt was made.
- **Device Type**: The type of device used for the login attempt (e.g., mobile, tablet, desktop).
- **Location**: Geographical location of the login attempt.
- **Session Duration**: Length of the session in seconds.
- **Failed Attempts**: Number of unsuccessful attempts prior to a successful login.
- **Behavioral Score**: A score representing the user's typical behavior patterns, used to detect deviations.

## Objectives
- **Generate a Synthetic Dataset**: To create realistic web authentication logs for model training and testing.
- **Implement Machine Learning Models**: To deploy various machine learning models that can classify activities into normal and anomalous.
- **Evaluate Model Effectiveness**: To assess the accuracy and efficiency of each model in detecting anomalies.

## How to Run the Notebook
1. **Clone the Repository**: 
   
   ```
   git clone https://github.com/HamidrezaGholamrezaei/Web_Auth_Anomaly_Detection.git
   cd Web_Auth_Anomaly_Detection
   ```

2. **Install Required Libraries** (if not already installed):
    ```
    pip install -r requirements.txt
    ```

3. **Open the Jupyter Notebook**:
- Run jupyter notebook or use Jupyter Lab to open jupyter files.

## Results and Insights
The supervised learning notebook provides the following insights:
- **Model Performance**: Details the accuracy, precision, recall, and ROC-AUC scores for models like Logistic Regression, Random Forest, SVM, and Neural Networks.
- **Feature Importance**: Discusses which features are most indicative of anomalies.
- **Predictive Power**: Demonstrates the ability of the models to distinguish between normal and anomalous behaviors effectively.

## Future Work
Unsupervised Learning Notebook: A future addition will explore unsupervised techniques to detect anomalies without labeled data.

## Contributions
Contributions to this project are welcome. Please fork the repository, make your changes, and submit a pull request. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
