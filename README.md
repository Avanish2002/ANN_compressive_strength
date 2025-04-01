This repository contains an Artificial Neural Network (ANN) model designed to predict the compressive strength of concrete based on various input features. The model is trained using Bayesian Optimization to fine-tune hyperparameters for better performance.

🚀 Features

Implements an ANN model for predicting concrete compressive strength.

Utilizes Bayesian Optimization for hyperparameter tuning.

Includes Jupyter Notebook (first.ipynb) for training and evaluation.

Saves the best-trained model as best_ann_model.h5 (not included in the repo due to file size limitations).

📂 Repository Structure

ANN_compressive_strength/
│-- first.ipynb       # Jupyter Notebook for training and evaluation
│-- best_ann_model.h5 # Trained model (not included in repo)
│-- requirements.txt  # Dependencies (if applicable)
│-- README.md         # Project documentation

📊 Dataset

The model is trained on a dataset that includes various features influencing the compressive strength of concrete, such as:

Cement content
Water content
Fine and coarse aggregate
Silica fume
Blast furnace slag
plasticizers
super plasticizers
🛠 Installation & Usage

1️⃣ Clone the Repository

git clone https://github.com/Avanish2002/ANN_compressive_strength.git
cd ANN_compressive_strength

2️⃣ Install Dependencies

Make sure you have Python 3.10+ installed, then install the required libraries:

pip install -r requirements.txt

3️⃣ Run the Jupyter Notebook

Start Jupyter Notebook and open first.ipynb:

jupyter notebook

🔍 Model Training & Evaluation

The ANN model is trained using TensorFlow/Keras.

Hyperparameters are optimized with Bayesian Optimization.

The trained model is saved as best_ann_model.h5 (excluded from the repo, but you can train your own version).

📌 Future Improvements

Implement additional feature engineering for better accuracy.

Compare ANN performance with other ML models like Random Forest or XGBoost.

Deploy the trained model using Flask/FastAPI for real-world applications.

