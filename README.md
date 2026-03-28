# netflix-content-analysis
Analysis of Netflix content trends using Python (genres, countries, growth)

# 📊 Netflix Content Analysis

This project explores Netflix’s content catalog to uncover trends in genres, countries, and content growth over time using Python.

---

## 🎯 Project Objective
The goal of this analysis is to understand how Netflix’s content has evolved and what strategies it uses to attract a global audience.

---

## ❓ Key Questions
- What are the most common genres on Netflix?
- Which countries produce the most content?
- How has Netflix’s catalog grown over time?
- Are movies or TV shows growing faster?
- How do genres vary across countries?
- What is the distribution of content ratings?

---

## 📁 Dataset
- Source: Netflix dataset (Kaggle)
- Contains information about:
  - Title
  - Type (Movie / TV Show)
  - Country
  - Release year
  - Rating
  - Duration
  - Genre
  - Date added

---

## 🧹 Data Cleaning
- Removed duplicate records
- Handled missing values
- Extracted year and month from `date_added`
- Converted duration into numeric format
- Checked for invalid or unrealistic values

---

## 📊 Key Insights

- 🎬 **Dramas dominate Netflix’s catalog**, followed by documentaries and comedies  
- 🌍 **The United States leads content production**, with strong growth from India and South Korea  
- 📈 Netflix content experienced rapid growth after 2015, driven by original productions  
- 📺 **TV Shows are growing faster than Movies**, showing a shift toward long-form content  
- 🌐 Netflix is increasingly investing in **international content** to reach global audiences  

---

## 💡 Recommendations

- Invest more in high-performing genres like drama and documentaries  
- Continue expanding international content production  
- Focus on TV series, as they show higher growth and engagement potential  
- Diversify content to target different audience segments  

---

## 🛠 Tools Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## 📌 Project Structure
netflix-content-analysis/
│
├── notebook
│   ├── netflix_analysis.ipynb
├── data
│   ├── netflix_titles.csv
│   ├── processed_data.csv
├── charts  
└── README.md


---

## 🚀 Future Improvements
- Improve genre analysis by splitting multi-genre entries  
- Analyze audience preferences more deeply  
- Build an interactive dashboard (Power BI or Tableau)  

---

## 👤 Author
Hussein Tamimme  
Aspiring Data Analyst
