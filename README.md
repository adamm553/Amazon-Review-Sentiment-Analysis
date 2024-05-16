# Amazon Alexa Review Sentiment Analysis

This Python code performs sentiment analysis on Amazon Alexa product reviews using machine learning techniques. The dataset used contains reviews, ratings, and feedback labels. The primary goal is to classify reviews as positive or negative based on their sentiment.

## Description

This code loads the dataset, explores its contents, preprocesses the text data, builds machine learning models, evaluates their performance, and tunes hyperparameters to improve accuracy. It utilizes popular libraries such as Pandas, Scikit-learn, NLTK, Matplotlib, and Seaborn for data manipulation, analysis, visualization, and model building.

## Key Features

- **Data Loading and Exploration:** The code loads the dataset, checks its structure, and explores various attributes such as ratings, feedback, and review length.

- **Text Preprocessing:** It preprocesses the text data by removing special characters, converting text to lowercase, removing stopwords, and performing stemming.

- **Model Building:** The code builds machine learning models such as RandomForestClassifier, XGBClassifier, and DecisionTreeClassifier to classify reviews into positive or negative sentiments.

- **Model Evaluation:** It evaluates model performance using metrics like accuracy, confusion matrix, and cross-validation scores.

- **Model Tuning:** The code tunes hyperparameters of the RandomForestClassifier using GridSearchCV to improve model accuracy.

## Contributors

- Adam Piątek (https://github.com/adamm553)


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
