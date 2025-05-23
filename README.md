# EV-Battery-Management-System-using-Deep-Learning

# 🚗🔋 EV Battery Management System using Deep Learning

This project leverages deep learning techniques, particularly LSTM neural networks, to optimize Electric Vehicle (EV) battery performance and management. Using real-world battery charging data, the model predicts essential battery health metrics and charging behavior. It also features a user-friendly Gradio interface and integrates with Comet ML for experiment tracking and visualization.

## 🔍 Project Description

As electric vehicles grow in popularity, efficient battery management becomes critical to performance and longevity. This project implements a predictive deep learning model that monitors key EV battery parameters and predicts optimal performance patterns. The system allows users to select different EV models and visualize battery charging behaviors.

## 📁 Dataset

- Name: `ev_battery_charging_data.csv`
- Description: The dataset includes EV model identifiers, state of charge (SOC), temperature, voltage, current, and other battery parameters.
- Source: Synthetic/generated from multiple open-source datasets and monitoring logs.

## 🧠 Technologies Used

- Python
- TensorFlow / Keras (LSTM for time-series prediction)
- Scikit-learn (data preprocessing, encoding, splitting)
- Matplotlib / Seaborn (data visualization)
- Gradio (interactive web UI)
- Comet ML (experiment tracking and live HTML panel reporting)
- Google Colab (training and deployment)

## 💻 Features

- 📊 Exploratory Data Analysis and Heatmap Visualizations
- 🧹 Data Preprocessing: Label Encoding, Scaling, NaN handling
- 🔁 Deep Learning Model (LSTM) for battery behavior prediction
- 📈 Real-time performance visualization (Loss/MAE per epoch)
- 🧪 Experiment logging and HTML reporting via Comet ML
- 🌐 Gradio Interface: Select EV model, visualize top 4 features graphically

## 📦 Installation and Usage

### 1. Clone the Repository
```bash
git clone https://github.com/<your-username>/EV-Battery-Management-System-using-Deep-Learning.git
cd EV-Battery-Management-System-using-Deep-Learning

This snippet is perfect for a README screenshot — short, clear, and complete.

If you want, I can help generate a sample screenshot of the running app interface too!
MODEL B EV VEHICLE OUTPUT:

![Screenshot 2025-04-19 201651](https://github.com/user-attachments/assets/809a2052-e5a2-4fef-b81c-ac1d838a6e71)

MODEL A  EV VEHICLE OUTPUT :

![Screenshot 2025-04-19 201638](https://github.com/user-attachments/assets/d073076a-d86e-4df5-ac70-677824b7368c)

