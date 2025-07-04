# 🎬 Netflix Content Trends: EDA with Hypothesis Testing

This project explores Netflix's global content catalog through structured Exploratory Data Analysis (EDA), feature engineering, and statistical hypothesis testing. It uncovers how Netflix’s offerings have evolved in terms of type, genre, rating, duration, and geography.

---

## 📦 Dataset

- **Source**: [Netflix Movies and TV Shows on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Records**: ~8,800 titles
- **Time Period**: 1925 to 2021

---

## 🎯 Objectives

- Analyze distribution by type (Movie/TV Show), genre, country, and rating
- Engineer new features like `duration_mins`, `main_genre`, `year_added`
- Visualize trends in content over time
- Perform statistical tests to validate observed patterns

---

## 📊 Key Insights

- 📈 TV Shows increased sharply after 2016
- 🎭 Most common genres: Drama, Comedy, Documentary
- 🌍 US and India are the largest contributors to Netflix content
- ⏱️ Most movies are 80–100 minutes long
- 🔞 Majority of content is rated TV-MA or PG-13

---

## 🧪 Hypothesis Testing

| Hypothesis | Test Used | Result |
|------------|-----------|--------|
| Rating distribution differs between Movies and TV Shows | Chi-square test | ✅ p < 0.001 |
| Average movie duration is shorter after 2018 | Independent t-test | ✅ p < 0.05 |

---

## 🛠️ Tech Stack

- Python, Pandas, NumPy
- Seaborn, Matplotlib
- Scipy (Chi-square, t-test)
- Jupyter Notebook

---

## 📁 Repository Structure

Netflix Content Trends: EDA with Hypothesis Testing/
├── EDA_Project.ipynb               
├── report/
│   └── EDA_Project_Report.pdf      
├── requirements.txt                
├── README.md                       

---

## 🚀 Future Work

- Build a classifier to predict content type using metadata
- Perform clustering to identify genre-based content segments
- Extend the project using user behavior data for personalization (if available)

---

## 🙌 Acknowledgments

- Dataset by [Shivam Bansal](https://www.kaggle.com/shivamb) on Kaggle
- Inspired by Netflix’s growing influence on global media and data storytelling

---

⭐ If you found this project helpful or insightful, feel free to **star** this repo or connect with me!
