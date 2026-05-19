# 📊 BMI Prediction & Analysis

Exploratory Data Analysis on a 500-person dataset — visualizing BMI distribution, gender breakdowns, and health category classifications using Python.

---

## 🔍 About the Project

This project analyzes a dataset of **500 individuals** (male & female) to understand BMI distributions across different health categories. The goal was to practice data wrangling, visualization, and classification using real-world style data.

**BMI Categories used:**

| Index | Status |
|-------|--------|
| 0 | Extremely Weak |
| 1 | Weak |
| 2 | Normal |
| 3 | Overweight |
| 4 | Obesity |
| 5 | Extreme Obesity |

---

## 📁 Dataset

**File:** `500_Person_Gender_Height_Weight_Index.csv`

| Column | Description |
|--------|-------------|
| Gender | Male / Female |
| Height | Height in cm |
| Weight | Weight in kg |
| Index | BMI category (0–5) |

500 records, no missing values.

---

## 📈 Key Findings

- Dataset is **gender-balanced**: ~51% Female, ~49% Male
- Most individuals fall in the **Extreme Obesity** category
- BMI distribution pattern is broadly **similar across genders**
- Height and weight show a clear **positive correlation**

---

## 🛠️ Tech Stack

- **Python 3**
- **Pandas** — data loading & manipulation
- **Matplotlib** — histograms, pie charts, bar charts
- **Seaborn** — scatter plots
- **scikit-learn** — label encoding

---

## 🚀 How to Run

**1. Clone the repository**
```bash
git clone https://github.com/asgeek96/BMIPrediction.git
cd BMIPrediction
```

**2. Install dependencies**
```bash
pip install pandas matplotlib seaborn scikit-learn
```

**3. Run the notebook**
```bash
jupyter notebook BMI_predict.ipynb
```

> Make sure `500_Person_Gender_Height_Weight_Index.csv` is in the same folder as the notebook.

---

## 📊 Visualizations

The notebook produces the following charts:

- **BMI Histogram** — distribution of BMI values across all 500 people
- **Gender Donut Chart** — Male vs Female split
- **BMI Category Donut Chart** — overall health category breakdown
- **Female vs Male BMI Comparison** — side-by-side category breakdown by gender
- **Height vs Weight Scatter Plot** — colored by BMI status

---

## 👤 Author

**Anubhav Srivastava**  
[GitHub](https://github.com/asgeek96) · [LinkedIn](https://www.linkedin.com/in/asgeek)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
