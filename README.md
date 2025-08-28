Rock vs Mine Prediction 🎯

This project uses Machine Learning to classify sonar signals as either Rock or Mine objects, based on frequency features captured from sonar data. It applies Logistic Regression for binary classification and evaluates performance with metrics such as accuracy, confusion matrix, and classification report.

📂 Project Structure
rock_vs_mine/
│
├── rock_vs_mine.ipynb     # Jupyter Notebook containing the full code
├── sonar data.csv         # Dataset used for training and testing
└── README.md              # Project documentation

🚀 Features

Loads and preprocesses the Sonar dataset

Splits data into training and testing sets

Implements a Logistic Regression model

Evaluates model accuracy and classification performance

Includes prediction examples for custom input

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

scikit-learn

📊 Dataset

The dataset sonar data.csv contains:

60 numeric features representing energy patterns of sonar signals

Target label:

R → Rock

M → Mine

⚡ Installation and Usage
1️⃣ Clone the repository
git clone https://github.com/sufyan-github/rock_vs_mine_prediction-ml-project.git
cd rock-vs-mine

2️⃣ Install dependencies
pip install pandas numpy matplotlib scikit-learn

3️⃣ Run the notebook
jupyter notebook rock_vs_mine.ipynb

📈 Model Training Workflow

Import dependencies

Load and inspect the dataset

Preprocess and split data

Train Logistic Regression model

Evaluate using accuracy and classification metrics

Test predictions on custom input
