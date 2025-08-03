# 🎬 Movie Rating Prediction - CodSoft Internship (Task 2)

## 📌 Objective
Build a machine learning model to predict IMDb movie ratings based on key features like genre, director, and duration using regression techniques.

This project was created as part of the **Data Science Internship at CodSoft**.

---

## 🧾 Dataset

- **Source**: https://www.kaggle.com/datasets/adrianmcmahon/imdb-india-movies 
- **Features Used**:
  - `Genre` (categorical)
  - `Director` (categorical)
  - `Duration` (numerical, in minutes)
- **Target**:
  - `Rating` (numerical IMDb score)

---

## ⚙️ Technologies & Tools

- **Language**: Python
- **Libraries**:
  - `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`
  - `scikit-learn` (`LinearRegression`, `RandomForestRegressor`, `LabelEncoder`, `StandardScaler`)

---

## 🔁 Workflow

1. **Data Preprocessing**
   - Removed missing values
   - Cleaned `Duration` (removed "min" and converted to float)
   - Encoded categorical features using `LabelEncoder`
   - Scaled `Duration` using `StandardScaler`

2. **Model Building**
   - Trained two regression models:
     - Linear Regression
     - Random Forest Regressor (bonus enhancement)

3. **Evaluation**
   - R² Score
   - Mean Squared Error (MSE)
   - Scatter plot for actual vs predicted ratings

---

## 📈 Model Results

| Model               | R² Score                 | MSE                    |
|---------------------|--------------------------|------------------------|
| Linear Regression   | 0.023177095462295627     | 1.8160555562396012     |
| Random Forest       | -0.003123724117676252    | 1.864952597156622      |


--- 

## 📦 How to Run

1. Clone the repo or download the ZIP.
2. Open `movie_rating_prediction` in Jupyter Notebook.
3. Run all cells step-by-step.
4. (Optional) Load the saved model.

## 🔖 Tags

#codsoft #datascience #internship #machinelearning
