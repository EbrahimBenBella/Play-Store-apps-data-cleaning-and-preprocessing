# Play Store Apps Data Cleaning and Preprocessing

## 📌 Introduction
The Google Play Store hosts a vast collection of applications, making it an essential platform for developers and businesses. Analyzing Play Store data can provide valuable insights into market trends, user behavior, and app performance. However, real-world datasets often contain missing values, inconsistencies, and outliers that must be addressed before analysis.

This project focuses on cleaning and preprocessing a dataset of Play Store apps. The goal is to ensure data accuracy, handle missing values, and extract meaningful insights that can benefit developers and stakeholders.

## 📊 Dataset Overview
The dataset consists of several attributes that describe different aspects of Play Store apps. Below are the key columns and their descriptions:

| Column Name       | Description |
|------------------|-------------|
| **Application Name** | Name of the application |
| **Category** | The category the app belongs to |
| **Rating** | Overall user rating of the app |
| **Reviews** | Number of user reviews |
| **Size** | App size in MB or KB |
| **Installs** | Number of downloads/installs |
| **Type** | Whether the app is Free or Paid |
| **Price** | The price of the app (for paid apps) |
| **Content Rating** | Targeted age group (e.g., Everyone, Teen, Mature 17+) |
| **Genres** | Additional genres the app belongs to |
| **Android Version** | Minimum required Android version |

## 🛠️ Data Cleaning Tasks
To prepare the dataset for analysis, we performed the following cleaning tasks:

✅ Fixing **Rating** inconsistencies and handling missing values  
✅ Converting **Size** into a uniform numeric format  
✅ Standardizing **Price** and handling incorrect price values  
✅ Cleaning and categorizing **Category** values  
✅ Standardizing **Android Version** format  
✅ Handling **missing values** across different columns  
✅ Detecting and treating **outliers**  
✅ Fixing any other inconsistencies found during the process  

## 🔍 Analytical Questions
After cleaning the dataset, we explored the following key questions:

1️⃣ What is the most expensive app on the Play Store?  
2️⃣ Which genre has the highest number of apps?  
3️⃣ What is the average size of free vs. paid apps?  
4️⃣ What are the top 5 most expensive apps with a perfect rating (5.0)?  
5️⃣ How many apps have received more than **50,000** reviews?  
6️⃣ What is the average price of apps, grouped by genre and number of installs?  
7️⃣ How many apps have a rating higher than **4.7**, and what is their average price?  
8️⃣ What is **Google's estimated revenue** from apps with **5,000,000+ installs** (assuming a 30% cut from sales)?  
9️⃣ What are the **maximum and minimum sizes** of free vs. paid apps?  
🔟 Is there a **correlation** between an app’s rating, number of reviews, size, and price?  
1️⃣1️⃣ How many apps exist for each type (**free/paid**) across different content ratings?  
1️⃣2️⃣ How many apps are compatible with **Android version 4.x**?  

## 📂 Deliverables
The project consists of the following deliverables:

📌 **Preprocessing Notebook**: A Jupyter notebook detailing the data cleaning steps with explanations.  
📌 **Analysis Results**: A structured report answering the analytical questions.  
📌 **GitHub Repository**: A well-documented repository with code, markdown explanations, and insights.  
📌 **LinkedIn Post**: After evaluation, the final project and notebook will be shared on LinkedIn.  


## 📢 How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/ebrahimbenbella/playstore-data-cleaning.git
   cd playstore-data-cleaning
   ```
2. Install dependencies (if required):
   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Open and run the Jupyter Notebook:
   ```bash
   jupyter notebook PlayStore_Data_Cleaning.ipynb
   ```

## 🎯 Conclusion
This project provides a structured approach to cleaning and analyzing Play Store app data. By addressing inconsistencies and extracting meaningful insights, we enable better decision-making for app developers, businesses, and researchers.

We hope this project serves as a valuable resource for data cleaning and exploratory analysis. 🚀


