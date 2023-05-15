# Crop Recommendation System

🌱📊🔍

![brown field near tree during daytime](https://images.unsplash.com/photo-1500382017468-9049fed747ef?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxzZWFyY2h8NXx8ZmFybXxlbnwwfHwwfHw%3D&w=1000&q=80)

## Introduction
This project focuses on building a Crop Recommendation System to assist farmers in selecting suitable crops for cultivation based on various factors such as soil type, climate, and historical crop performance. The system aims to optimize crop yields and increase agricultural productivity.

## Dataset
The preprocessed dataset for this project is available [here](https://github.com/Devansh-45/CRS/tree/master/Data-processed) .

## Dependencies
The following libraries were used in this project:
- NumPy 🧮
- Pandas 🐼
- Seaborn 🌊
- Matplotlib 📊
- Logistic Regression 📈
- Decision Tree 🌳
- Random Forest 🌲
- Support Vector Machine (SVM) 📉
- Naive Bayes 📚
- Flask 🌐
- PyTorch 🔥

## Methodology
1. Data Preprocessing: The dataset was preprocessed, including handling missing values, encoding categorical variables, and scaling numerical features.

2. Exploratory Data Analysis: Visualizations and statistical analysis were performed to gain insights into the dataset, such as identifying correlations between different variables and exploring patterns in crop performance.

3. Model Training: Several classification algorithms, including Logistic Regression, Decision Tree, Random Forest, SVM, and Naive Bayes, were employed to build crop recommendation models. These models were trained on historical data to predict suitable crops based on given inputs.

4. Model Evaluation: The performance of each model was evaluated using appropriate metrics such as accuracy, precision, recall, and F1 score. Cross-validation and hyperparameter tuning techniques were employed to optimize the models.

5. Deployment: A Flask web application was developed to provide an interactive interface for farmers to input relevant factors (e.g., soil type, climate) and receive crop recommendations based on the trained models.

## Usage
1. Clone the repository:
	git clone [Repository](https://github.com/Devansh-45/CRS/tree/master)

2. Install the required dependencies:
	'''
	pip install -r requirements.txt
	'''
3. Prepare the dataset. Download the stock market dataset from Kaggle and place it in the project directory.

4. Train the models:
This will train the time series models on the historical stock price data.

5. Run the Flask web application:
Access the web application at `http://localhost:5000` in your web browser.

Feel free to customize the project or modify the code to suit your specific needs. If you encounter any issues or have questions, please don't hesitate to reach out for support.

## Results
The project provides predictions for future stock prices based on historical data and time series analysis. The models aim to capture patterns and trends in the stock market, assisting users in making informed decisions.

## Future Enhancements
Here are some ideas to further enhance the project:

- Implement more advanced time series models, such as Prophet or deep learning architectures like Transformer.
- Incorporate additional data sources, such as news sentiment or macroeconomic indicators, to improve prediction accuracy.
- Enhance the web application with interactive charts and customizable settings.

## Contributors
- [Devansh Desai](https://github.com/Devansh-45)

Contributions to this project are welcome. Feel free to open issues or submit pull requests.

## License
This project is licensed under the [MIT License](LICENSE).
