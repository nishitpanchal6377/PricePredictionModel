# Car Price Prediction

## 📌 Project Overview
This project predicts the selling price of used cars based on various features like the car's name, year of manufacture, kilometers driven, fuel type, seller type, transmission type, and ownership history. It utilizes multiple machine learning algorithms to compare their performance.

## 🚀 Technologies Used
- **Python**
- **Pandas** (Data manipulation)
- **Matplotlib & Seaborn** (Data visualization)
- **Scikit-Learn** (Machine learning models and preprocessing)

## 📂 Dataset
The dataset used for this project is **cardekho_data.csv**, which contains details about used cars, including:
- `Car_Name`
- `Year`
- `Present_Price`
- `Kms_Driven`
- `Fuel_Type`
- `Seller_Type`
- `Transmission`
- `Owner`
- `Selling_Price` (Target variable)

## ⚙️ Installation and Setup
### 1️⃣ Clone the repository:
```bash
git clone https://github.com/your-username/Car-Price-Prediction.git
cd Car-Price-Prediction
```

### 2️⃣ Install dependencies:
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Jupyter Notebook:
```bash
jupyter notebook
```
Open the `.ipynb` file and run the cells.

## 📊 Data Preprocessing
1. **Handling Missing Values:** Checked for null values and handled them accordingly.
2. **Encoding Categorical Data:** Used `LabelEncoder` to convert categorical features into numerical values.
3. **Feature Scaling:** Applied `StandardScaler` to normalize the input data.
4. **Splitting Data:** Divided the dataset into training (80%) and testing (20%) sets.

## 🔍 Machine Learning Models Used
The following regression models were trained and evaluated:
- **Linear Regression**
- **Lasso Regression**
- **Ridge Regression**
- **ElasticNet Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **Support Vector Regressor (SVR)**
- **K-Nearest Neighbors (KNN) Regressor**

## 📈 Model Performance
Each model's accuracy was calculated using the `.score()` method on the test data.

## 🔮 Making Predictions
To predict the selling price of a new car, create a DataFrame with the car's attributes, apply the same preprocessing steps, and use the trained model for prediction.

Example:
```python
new_data = pd.DataFrame([["rola", 2025, 5.59, 27000, "Petrol", "Dealer", "Manual", 0]], columns=x_train.columns)
dt.predict(new_data)  # Using Decision Tree Regressor
```

## 🤝 Contributing
1. Fork this repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make changes and commit (`git commit -m "Added new feature"`).
4. Push the branch (`git push origin feature-branch`).
5. Create a pull request.

## 📜 License
This project is open-source and available under the **MIT License**.

---
Feel free to contribute and improve the project! 🚀

