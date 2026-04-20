## 🐼 Pandas Mastery for Data Science

A complete, structured, and practical guide to mastering **Pandas** for Data Science.
This repository is designed to cover everything from **basics to advanced concepts**, with hands-on notebooks and real-world workflows.

---

## 📌 What This Repository Covers

### 📥 I/O (Reading & Writing)

* `pd.read_csv()`, `pd.read_excel()`
* `df.to_csv()`, `df.to_parquet()`
* Handling large files and different formats

---

### 🔍 Exploration & Inspection

* `df.head()`, `df.info()`, `df.describe()`
* `df.shape`, `df.dtypes`
* `df.isnull().sum()`, `df.nunique()`
* `df.value_counts()`, `df.sample()`

---

### 🎯 Selection & Filtering

* Column selection: `df['col']`, `df[['a','b']]`
* `df.loc[]`, `df.iloc[]`
* Boolean filtering & `df.query()`
* `df.filter()`, `df.where()`, `df.mask()`

---

### 🧹 Data Cleaning & Transformation

* `df.dropna()`, `df.fillna()`
* `df.rename()`, `df.astype()`
* `df.drop()`, `df.duplicated()`, `df.drop_duplicates()`
* `df.replace()`, `df.apply()`, `df.map()`
* `df.assign()`, `pd.to_datetime()`
* String & datetime operations: `df.str.*`, `df.dt.*`

---

### 📊 Aggregation & Grouping

* `df.groupby()` + `.agg()`
* `df.pivot_table()`
* `df.resample()`
* `df.rolling()`

---

### 🔗 Merging & Joining

* `pd.merge()` (inner, left, right, outer joins)
* `pd.concat()` (row & column wise)
* `df.join()`

---

### 📈 Sorting & Ranking

* `df.sort_values()`, `df.sort_index()`
* `df.rank()`
* `df.nlargest()`, `df.nsmallest()`

---

### 🧩 Index Operations

* `df.set_index()`
* `df.reset_index()`
* `df.reindex()`

---

### 📉 Statistical & Mathematical Operations

* `df.mean()`, `df.sum()`, `df.median()`
* `df.std()`, `df.var()`
* `df.corr()`, `df.cov()`
* `df.cumsum()`, `df.diff()`, `df.pct_change()`
* `df.quantile()`, `df.abs()`

---

### 🏷️ Categorical & Encoding

* `pd.Categorical()`
* `pd.get_dummies()`
* `pd.cut()`, `pd.qcut()`
* `df.cat.*`

---

### ⚡ Performance & Memory Optimization

* `df.copy()`
* `pd.read_csv(chunksize)`
* `df.select_dtypes()`
* `df.convert_dtypes()`

---

## 📂 Repository Structure

```
pandas-mastery/
│
└── datasets/
├── 01_I/O (Reading & Writing)/
├── 02_exploration & inspection/
├── 03_selection filtering/
├── 04_data cleaning & transformation/
├── 05_Aggregation & Grouping/
├── 06_merging joining/
├── 07_sorting ranking/
├── 08_index operations/
├── 09_statistics & mathematical Operation/
├── 10_categorical Encoding/
├── 11_Performance & Memory Optimization/
│

```

---

## 🚀 How to Use

```Command prompt
create a environment named venv
pip install jupyter notebook
!pip install pandas numpy jupyter
jupyter notebook
```

1. Navigate to any folder
2. Open the notebook
3. Run cells step-by-step

---

## 🎯 Goal

To build **strong, practical Pandas skills** required for:

* Data Analysis
* Data Cleaning
* Feature Engineering
* Real-world Data Science projects

---

## 💡 Key Highlights

* 📘 Well-structured notebooks
* 💻 Hands-on examples for every function
* 📊 Industry-focused workflow
* 🚀 Beginner → Advanced coverage

---

## ⭐ Support

If you found this repository useful:

* ⭐ Star this repo
* 🔁 Share with others
* 💡 Use it in your projects

---

## 🚀 Next Step

Move to:

* Real-world projects
* End-to-end data analysis
* Machine Learning pipelines

👉 This is where learning turns into **placements** 💯
