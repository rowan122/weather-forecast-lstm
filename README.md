# 🌤️ Weather Forecasting using LSTM

A deep learning project using LSTM (Long Short-Term Memory) networks to predict future weather conditions from historical data.

---

## 🧠 Objective

To build and train an LSTM model capable of forecasting weather trends (e.g., temperature) based on time-series data.

---

## 📊 Dataset

- Format: CSV
- Time-indexed weather observations
- Columns: `Date`, `Temperature`, `Humidity`, `Wind Speed`, etc.

---

## 🧰 Tools & Libraries

- Python
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn
- TensorFlow / Keras

---

## 🧪 Model Architecture

- LSTM Layer(s) with return sequences
- Dropout layer
- Dense output layer
- Loss Function: MSE
- Optimizer: Adam

---

## 📈 Results

The model was evaluated on test data using Mean Squared Error and visually inspected using plots.

![Prediction Plot](prediction_plot.png)

---

## 📁 Files

- `weather_lstm.ipynb`: Model training and evaluation
- `weather_data.csv`: Dataset file
- `prediction_plot.png`: Output chart comparing predicted vs actual values

---

## 🚀 How to Run

1. Open the notebook `weather_lstm.ipynb`
2. Run all cells to preprocess data, train the model, and view results
3. Customize parameters or test on other datasets

---

## 👩‍💻 Author

Rowan Ibrahiem  
[LinkedIn](https://www.linkedin.com/in/rowan-ibrahiem-ba7571277) | [Email](mailto:rowanibrahiem@gmail.com)

---

## ⚠️ Note

This project is for educational/portfolio use only. The dataset used is publicly available or simulated.
