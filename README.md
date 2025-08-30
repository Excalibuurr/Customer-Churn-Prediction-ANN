🏦 Customer Churn Prediction using Artificial Neural Networks (ANN)

Welcome to the Customer Churn Prediction project!  
This repository demonstrates how to leverage Artificial Neural Networks to predict customer churn in the banking sector, using Python and machine learning best practices.

---

## 📊 Project Overview

Churn prediction is crucial for businesses aiming to retain valuable customers. Here, we build and deploy a machine learning pipeline that analyzes customer data and predicts the likelihood of churn.

- **Dataset:** [`Churn_Modelling.csv`](./Churn_Modelling.csv)  
- **Model:** Artificial Neural Network (ANN)  
- **Deployment:** Python app for making predictions

---

## 🛠️ Technologies Used

- **Programming Language:** Python  
- **Libraries:** TensorFlow, Keras, scikit-learn, Pandas, NumPy, Matplotlib  
- **Deployment:** Flask (see `app.py`)  
- **Model Storage:** HDF5, Pickle for encoders and scaler

---

## 🚀 How It Works

1. **Data Preprocessing:**  
   - Categorical features encoded (see pickle files for encoders)
   - Data scaled for optimal model performance

2. **Model Architecture:**  
   - Deep ANN built with Keras/TensorFlow
   - Trained on historical customer data

3. **Prediction Pipeline:**  
   - Use `app.py` to run predictions
   - Load pre-trained model and encoders
   - Input new customer data to get churn probability

---

## 📁 Key Files

- [`experiments.ipynb`](./experiments.ipynb): Model training, evaluation, and experiments
- [`prediction.ipynb`](./prediction.ipynb): Examples of model inference
- [`app.py`](./app.py): Flask app for live predictions
- [`model.h5`](./model.h5): Saved ANN model
- [`Scaler.pkl`](./Scaler.pkl), [`label_encoder_gender.pkl`](./label_encoder_gender.pkl), [`onehot_encoder_geo.pkl`](./onehot_encoder_geo.pkl): Preprocessing artifacts
- [`requirements.txt`](./requirements.txt): Python dependencies

---

## 🌟 Features

- End-to-end ML pipeline: data preprocessing, modeling, evaluation, and deployment
- Easily extensible for other churn prediction problems
- Ready-to-use REST API for model inference

---

## 📚 License

Licensed under the GNU GPL v3.0. See [`LICENSE`](./LICENSE) for details.

---

## 👤 Author

- GitHub: [Excalibuurr](https://github.com/Excalibuurr)

---

_Explore the notebooks, try out the Flask app, or use the codebase to power your own churn prediction projects!_
