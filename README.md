# Weather Forecasting — SVM, ANN, RNN

This project focuses on predicting weather conditions using three machine learning models: **Support Vector Machines (SVM)**, **Artificial Neural Networks (ANN)**, and **Recurrent Neural Networks (RNN)**. It explores how traditional and deep learning techniques can be applied to forecast weather more accurately.

---

## 📁 Repository Structure

```
Weather-Forecasting---SVM-ANN-RNN/
│
├── datasets/                # Weather dataset used (optional/private)
├── code.ipynb              # Main Jupyter notebook with all models (SVM, ANN, RNN)
├── requirements.txt         # Python dependencies
├── README.md               # Project overview and instructions
└── LICENSE                 # Open source license (MIT, etc.)
```

---

## 🚀 Models Used

- **SVM (Support Vector Machine)**: Suitable for classification problems using historical weather data features.
- **ANN (Artificial Neural Network)**: Multi-layer perceptron trained on meteorological data.
- **RNN (Recurrent Neural Network)**: Ideal for sequential weather data (e.g., temperature time series).

---

## 📊 Dataset

The dataset includes historical weather records such as:

- **Temperature** (°C/°F)
- **Humidity** (%)
- **Wind Speed** (km/h or mph)
- **Precipitation** (mm or inches)
- **Pressure** (hPa or mmHg)
- **Date & Time** features

*Note: If you're using a specific public dataset, you can link to it here.*

---

## 🛠️ How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ahmedraza9332/Weather-Forecasting---SVM-ANN-RNN.git
   cd Weather-Forecasting---SVM-ANN-RNN
   ```

2. **Install required libraries:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Open the notebook in Jupyter:**
   ```bash
   jupyter notebook code.ipynb
   ```

4. **Run the notebook:**
   - The notebook contains all three models (SVM, ANN, RNN) implemented sequentially
   - Execute cells in order from top to bottom
   - Data preprocessing, model training, and evaluation are all included

---

## 📌 Dependencies

- Python 3.7+
- NumPy
- Pandas
- Scikit-learn
- TensorFlow / Keras
- Matplotlib
- Seaborn
- Jupyter Notebook

Create a `requirements.txt` file with:
```
numpy>=1.19.0
pandas>=1.2.0
scikit-learn>=0.24.0
tensorflow>=2.4.0
matplotlib>=3.3.0
seaborn>=0.11.0
jupyter>=1.0.0
```

---

## 🔍 Results

Each section of the notebook evaluates its respective model using:

- **Accuracy** - Overall prediction correctness
- **Confusion Matrix** - Classification performance visualization
- **RMSE** (Root Mean Square Error) - For regression-based predictions
- **MAE** (Mean Absolute Error) - Average prediction error
- **R² Score** - Coefficient of determination

Graphs and metrics are included for performance comparison between all three models.

---

## 🎯 Model Performance Comparison

| Model | Accuracy | RMSE | Training Time |
|-------|----------|------|---------------|
| SVM   | TBD      | TBD  | TBD          |
| ANN   | TBD      | TBD  | TBD          |
| RNN   | TBD      | TBD  | TBD          |

*Results will be updated after running experiments*

---

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

## ✍️ Author

**Ahmed Raza**
- GitHub: [@ahmedraza9332](https://github.com/ahmedraza9332)
- LinkedIn: [Connect with me](https://linkedin.com/in/your-profile)

---

## 📚 References

- [Scikit-learn Documentation](https://scikit-learn.org/)
- [TensorFlow Documentation](https://www.tensorflow.org/)
- [Weather Prediction Research Papers](https://scholar.google.com/scholar?q=weather+prediction+machine+learning)

---

⭐ **If you found this project helpful, please give it a star!**
