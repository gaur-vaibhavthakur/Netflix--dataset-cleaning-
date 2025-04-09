#  Netflix Data Cleaning Project

This project focuses on cleaning the Netflix Movies and TV Shows dataset as part of an internship task. The goal was to preprocess the data, handle missing values, and prepare it for future analysis.

---

##  Project Structure


Netflix_Data_Cleaning:-

1-Netflix_Data_Cleaning.ipynb (Jupyter notebook with cleaning steps)

2-README.md (project / task details)

3- cleaned_netflix .csv( cleaned dataset  )

4-netflix_titles.csv ( original raw dataset)
 



---

## 🧼 Cleaning Steps Performed

- Removed duplicate records
- Standardized column names (converted to lowercase and snake_case)
- Converted `date_added` to datetime format (`dd-mm-yyyy`)
- Handled missing values:
  - `country` → filled with `'Unknown'` 
  - `rating` → filled with most frequent value (mode)
  - `director` & `cast` → filled with `'Not Specified'`
  - `date_added` → filled with most frequent date (mode)
  -`duration '-> filled with most frequent time (mode)

## preview of  cleaned data

-> All data is check for missing values agian after cleaning to ensure data Inconsitency and Integrity
---

##  Tools Used

- Python 
- Pandas 
- Jupyter Notebook 

---

##  How to Use

1. Clone the repository:
   ```bash
   git clone https://https://github.com/gaur-vaibhavthakur/Netflix-data--cleaning.git




 About Me
Hi, I’m Vaibhav Thakur data analyst enthusiast currently exploring real-world datasets.
This was part of my internship learning experience.

 Email: [gaur.vaibhavthakur@gmail.com]
