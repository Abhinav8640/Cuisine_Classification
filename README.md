# 🍽️ Restaurant Cuisine Classification using Machine Learning

A machine learning project that classifies restaurant cuisines using restaurant-related features such as location, ratings, online delivery availability, table booking, and other attributes. The project uses a **Random Forest Classifier** to predict the cuisine category of a restaurant.

---

## 📌 Project Overview

This project aims to classify restaurants into the two most common cuisine categories found in the dataset. Various restaurant features are preprocessed and encoded before training a Random Forest model for classification.

The trained model is evaluated using multiple classification metrics to measure its performance.

---

## 🚀 Features

- Data preprocessing and cleaning
- Selection of the top two most frequent cuisine categories
- Label encoding for categorical features
- One-hot encoding for target labels
- Random Forest Classification
- Train-Test Split with Stratified Sampling
- Performance evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - Classification Report

---

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn

---

## 📂 Dataset

The dataset should include restaurant information such as:

- Restaurant ID
- Restaurant Name
- Country Code
- City
- Address
- Locality
- Currency
- Has Table Booking
- Has Online Delivery
- Is Delivering Now
- Rating Color
- Rating Text
- Aggregate Rating
- Votes
- Average Cost for Two
- Price Range
- Cuisines

---

## ⚙️ Machine Learning Workflow

1. Load the dataset.
2. Select the top two most frequent cuisine categories.
3. Encode categorical features using Label Encoding.
4. Convert cuisine labels into one-hot encoded vectors.
5. Remove unnecessary columns.
6. Split the dataset into training and testing sets.
7. Train a Random Forest Classifier.
8. Evaluate model performance using classification metrics.

---

## 📊 Model Configuration

- **Algorithm:** Random Forest Classifier
- **Number of Trees:** 1000
- **Max Features:** Square Root (`sqrt`)
- **Class Weight:** Balanced Subsample
- **Random State:** 42
- **Parallel Processing:** Enabled (`n_jobs = -1`)

---

## 📈 Evaluation Metrics

The model reports:

- Accuracy
- Precision
- Recall
- F1 Score
- Detailed Classification Report

Example Output:

```
Accuracy : 95.84 %
Precision : 95.84 %
Recall : 95.84 %
F1 Score : 95.84 %

Classification Report

              precision    recall    f1-score   support

Cuisine A       0.96       0.95       0.95       420
Cuisine B       0.95       0.96       0.95       405

accuracy                               0.96       825
```

---

## 📁 Project Structure

```
Restaurant-Cuisine-Classification/
│
├── Dataset.csv
├── cuisine_classifier.py
├── README.md
└── requirements.txt
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/restaurant-cuisine-classification.git
```

Move to the project directory:

```bash
cd restaurant-cuisine-classification
```

Install the required libraries:

```bash
pip install pandas scikit-learn
```

Run the project:

```bash
python cuisine_classifier.py
```

---

## 📌 Libraries Used

- pandas
- scikit-learn

---

## 🔮 Future Enhancements

- Support classification for all cuisine categories instead of only the top two.
- Perform feature selection to improve model performance.
- Compare different machine learning algorithms such as XGBoost, LightGBM, and CatBoost.
- Build a web application using Flask or Streamlit.
- Add data visualization for better insights.
- Deploy the trained model as an API.

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repository, improve the project, and submit a pull request.

---

## 📄 License

This project is intended for educational and learning purposes.

---

⭐ If you found this project helpful, consider giving it a star on GitHub!
