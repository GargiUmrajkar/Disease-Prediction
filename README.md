
# Disease Prediction from Symptoms

This project is dedicated to leveraging machine learning techniques to predict potential diseases based on various symptoms. 

## Explored Algorithms

In this project, we delve into several machine learning algorithms to analyze their effectiveness in disease prediction. The algorithms include:

1. Naive Bayes
2. Decision Tree
3. Random Forest
4. Gradient Boosting

## Data Resources

### Source-1

The primary dataset utilized in the `main.py` script is sourced from the following URL:

```
https://www.kaggle.com/kaushil268/disease-prediction-using-machine-learning
```

Comprising 133 columns, 132 represent symptoms experienced by patients, while the final column is dedicated to the prognosis.

### Source-2

An alternative dataset used in the Jupyter notebook can be found at:

```
https://impact.dbmi.columbia.edu/~friedma/Projects/DiseaseSymptomKB/index.html
```

This dataset is organized into three columns:

```
Disease | Count of Disease Occurrence | Symptom
```

You may manually copy the table into an excel sheet or use Beautifulsoup for web scraping.


## Instructions for Use

Before initiating the demo, ensure all necessary dependencies are installed using the command below:

```
pip install -r requirements.txt
```

### Interactive Demo

To launch an interactive demonstration or share it with peers, initiate the `demo.py` script through Jupyter Notebook or Jupyter Lab as follows:

```
jupyter notebook demo.ipynb
```

### Standalone Demo

To conduct inferences on a test set or custom inputs, utilize the `infer.py` script:

```
python infer.py
```

**NOTE:** ***This initiative is intended solely for demonstration. Always consult a medical professional for any health concerns or symptoms.***
