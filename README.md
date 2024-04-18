# Student Loans with Deep Learning

## Description
This project utilizes deep learning techniques to analyze and predict student loan repayment capabilities based on a variety of factors such as income, academic performance, and financial aid score. The goal is to build a predictive model that can aid financial institutions in making informed decisions about loan issuance. This could also be used to recommend suitable student loan options for students.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Installation
To run this project, you need to have Python installed along with the following libraries:
- pandas
- numpy
- scikit-learn
- tensorflow

### Steps:
1. Clone the repository:
```git clone https://github.com/sir-hobbyjog/neural-network-challenge-1.git```

2. Install the required packages:
```pip install pandas numpy scikit-learn tensorflow```

## Usage
To use this project, run the Jupyter Notebook `student_loans_with_deep_learning.ipynb`. The notebook is divided into multiple sections, each corresponding to a step in the data processing and model building pipeline:
1. Data preprocessing
2. Splitting the data into training and testing sets
3. Normalizing the data
4. Building and training the deep neural network
5. Evaluating the model performance

## Define the model
```model = Sequential([Dense(units=8, activation='relu', input_dim=number_of_features),Dense(units=1, activation='sigmoid')])```

## Compile the model
```model.compile(loss='binary_crossentropy', optimizer='adam', metrics=['accuracy'])```

## Train the model
```model.fit(X_train_scaled, y_train, epochs=50, batch_size=10)```

## Acknowledgments
The starter file and dataset were provided by EdX.
