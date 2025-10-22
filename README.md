# 🎬 Netflix Data Cleaning, Analysis, and Visualization using Python

This project is part of my **Data Science Internship**.  
It involves **data cleaning, analysis, and visualization** of a Netflix dataset using Python.

---

## 🧩 Project Overview

Netflix is a popular streaming service offering a vast library of movies, TV shows, and original content.  
The dataset includes content from **2008 to 2021** and contains details like type, title, director, cast, country, release year, rating, and more.

The goal of this project is to:
- Clean and preprocess the dataset
- Explore and visualize patterns in Netflix content
- Derive meaningful insights using Python

---

## 🧰 Tools & Technologies Used

- **Python** 🐍  
- **Jupyter Notebook**  
- **Pandas** – Data manipulation  
- **NumPy** – Numerical analysis  
- **Matplotlib & Seaborn** – Data visualization  
- **WordCloud** – Text visualization  

---

## 📊 Dataset Information

**Source:** Cleaned version of Netflix dataset (2008–2021)  
**File:** `netflix1.csv`  

**Columns include:**
- `show_id`, `type`, `title`, `director`, `cast`, `country`, `date_added`,  
  `release_year`, `rating`, `duration`, `listed_in`, `description`

---

## 🔍 Project Workflow

1. **Import Required Libraries**
2. **Load the Dataset**
3. **Data Cleaning**
   - Handle missing values  
   - Remove duplicates  
   - Drop unnecessary columns  
   - Extract useful features (like year)
4. **Exploratory Data Analysis (EDA)**
   - Movies vs TV Shows count  
   - Content per country  
   - Release year distribution  
   - Ratings distribution  
5. **Data Visualization**
   - Using Matplotlib and Seaborn
6. **WordCloud**
   - For popular titles and descriptions
7. **Insights & Conclusion**

---

## 📓 Jupyter Notebook

The notebook file `netflix_analysis.ipynb` contains:
- All Python code for data cleaning and analysis  
- Visualization outputs and comments  

---

## 📈 Sample Insights

- Netflix has **more movies than TV shows**.  
- The **United States** contributes the most content.  
- Most content was added between **2017–2020**.  
- The most frequent ratings are **TV-MA** and **TV-14**.

---

## 🧾 Requirements

Create a virtual environment and install dependencies:
```bash
pip install -r requirements.txt


requirements.txt:

pandas
numpy
matplotlib
seaborn
wordcloud

🪄 How to Run

Clone the repository:

git clone https://github.com/yourusername/netflix-data-analysis-project.git


Navigate into the folder:

cd netflix-data-analysis-project


Open Jupyter Notebook:

jupyter notebook


Run netflix_analysis.ipynb cell by cell.

📊 Visualizations

Include screenshots (optional):

images/
  ├── movies_vs_tvshows.png
  ├── top_countries.png
  ├── release_year_distribution.png
  ├── ratings_distribution.png
  └── wordcloud.png

📚 Conclusion

This project demonstrates:

How to clean and explore real-world datasets

How to visualize insights effectively

How to prepare a dataset for further machine learning or dashboarding (e.g., Tableau)

🧑‍💻 Author

Name: Akshay Mudavath
Role: Data Science Intern
Year: 2025
Tools Used: Python, Jupyter, Tableau
Email: mudavathakki4@gmail.com

🪪 License

This project is licensed under the MIT License
.


---

## 📜 STEP 4: requirements.txt

Create a file named `requirements.txt` with:


pandas
numpy
matplotlib
seaborn
wordcloud


---

## 💻 STEP 5: Add and Push to GitHub

Run these commands in your project folder:

```bash
git init
git add .
git commit -m "Add Netflix Data Cleaning and Analysis Project with documentation"
git branch -M main
git remote add origin https://github.com/<your-username>/netflix-data-analysis-project.git
git push -u origin main

🪶 Commit Message
Add complete Netflix Data Cleaning and Analysis Project

- Added netflix_analysis.ipynb with full code
- Included dataset (netflix1.csv)
- Added README.md and requirements.txt
- Added detailed project overview and documentation

🎉 Final Output in GitHub

Your GitHub repo will show:

netflix-data-analysis-project/
│
├── netflix_analysis.ipynb
├── netflix1.csv
├── README.md
├── requirements.txt
└── images/
![Screenshot_22-10-2025_192141_localhost](https://github.com/user-attachments/assets/f761c628-aa01-4860-a433-d33c40be621a)
![Screenshot_22-10-2025_192123_localhost](https://github.com/user-attachments/assets/e8fa135e-20e0-430e-8ceb-10978fccf594)
![Screenshot_22-10-2025_19218_localhost](https://github.com/user-attachments/assets/ba8fc970-e298-4a84-ad4f-a333a05b9883)
![Screenshot_22-10-2025_192052_localhost](https://github.com/user-attachments/assets/20576455-0a25-4520-b20e-9b0560e32ee1)
![Screenshot_22-10-2025_192038_localhost](https://github.com/user-attachments/assets/8c5b97f9-aabf-4583-b92c-6f1d4f72e71b)
![Screenshot_22-10-2025_192019_localhost](https://github.com/user-attachments/assets/1b886ac2-1df3-449a-84b3-50d48a33e0bc)
![Screenshot_22-10-2025_191957_localhost](https://github.com/user-attachments/assets/d0894877-b1e5-40dd-8f82-7f5e98490a27)
**
