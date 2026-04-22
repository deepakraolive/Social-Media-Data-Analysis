📊 YouTube Content Data Analysis

🚀 This project focuses on analyzing YouTube content performance across different countries using Data Science techniques such as EDA, Visualization, Hypothesis Testing, and Linear Regression.

🎯 Project Objective

To answer key questions like:

Which type of content performs best in different countries?
Is there a relationship between views and likes?
Does content category significantly impact engagement?
Can we predict engagement using statistical models?
🛠️ Tech Stack
Python 🐍
Pandas
Matplotlib & Seaborn
Scipy (Hypothesis Testing)
Statsmodels (Linear Regression)
Google Colab
⚠️ Important Note (Dataset Access)

Due to file size limitations, the dataset is NOT included in this repository.

👉 You must download it manually and upload it to your Google Drive before running the notebook.

📂 Dataset Download

Download from Google Drive:
🔗 https://drive.google.com/file/d/1uElckvZ0xG7Zu_iyTdOX_DmzF2j1aVBw/view?usp=sharing

▶️ How to Run the Project (Step-by-Step)
1️⃣ Open the Notebook

Click here:
🔗 https://colab.research.google.com/drive/1OSyqNV1Ks6HL1gC-I3qvcLlplbU0jq0X?usp=sharing

2️⃣ Upload Dataset to Google Drive
Download dataset from above link
Upload it to your Google Drive
Note the file path (example):
/content/drive/MyDrive/YourFolder/filename.csv
3️⃣ Mount Google Drive in Colab

Run this cell:

from google.colab import drive
drive.mount('/content/drive')
4️⃣ Update File Path in Code

Find this line in the notebook:

file_path = "/content/drive/MyDrive/.../your_file.csv"

👉 Replace with your actual dataset path

5️⃣ Run the Notebook
Click “Run All”
The notebook will:
Load data
Perform EDA
Generate visualizations
Run hypothesis testing
Build linear regression model
📊 Key Analysis Performed
🔹 Exploratory Data Analysis (EDA)
Understanding dataset structure
Handling missing values
Feature exploration
🔹 Visualization
Content performance across countries
Category-wise engagement
Views vs Likes relationship
🔹 Hypothesis Testing
Tested whether content category affects engagement
Result: Statistically significant impact
🔹 Linear Regression
Predicted likes using views
R² ≈ 0.71 → Strong relationship
📈 Key Insights
Content preference varies by country 🌍
Music & Entertainment dominate in developed regions
Lifestyle content performs well in specific regions
Views strongly influence likes, but not entirely
💡 Real-World Applications
Content Strategy Optimization
Regional Audience Targeting
Social Media Marketing Insights
Data-driven Decision Making
🤝 Connect with Me

If you found this useful or have suggestions, feel free to connect!

⭐ If you like this project

Give it a ⭐ on GitHub and share your feedback!
