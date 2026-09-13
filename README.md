# YouTube Content Data Analysis

This project analyzes YouTube content performance across different countries using Data Science techniques, including Exploratory Data Analysis (EDA), data visualization, hypothesis testing, and linear regression. The goal is to identify engagement patterns across content categories and understand the relationship between views and likes.

## Project Objective

This project answers questions such as:

* Which content categories perform best in different countries?

* Is there a relationship between views and likes?

* Does content category significantly affect engagement?

* Can engagement be predicted using statistical models?

## Tech Stack

* Python

* Pandas

* Matplotlib

* Seaborn

* SciPy (Hypothesis Testing)

* Statsmodels (Linear Regression)

* Google Colab

## Dataset

The dataset is not included in this repository due to its large file size.

Download it from Google Drive and upload it to your Google Drive before running the notebook.

Dataset Link:

## How to Run

1. Open the Google Colab notebook:

2. Download the dataset from the link above.

3. Upload the dataset to your Google Drive.

4. Mount Google Drive in Colab:

   Python

   Run

   ```
   from google.colab import drive
   drive.mount('/content/drive')
   ```

5. Update the dataset path in the notebook:

   Python

   Run

   ```
   file_path = "/content/drive/MyDrive/your_folder/your_file.csv"
   ```

6. Run all cells to execute the complete analysis.

## Analysis Performed

### Exploratory Data Analysis

* Examined the dataset structure

* Handled missing values

* Explored key features

### Data Visualization

* Compared content performance across countries

* Analyzed category-wise engagement

* Visualized the relationship between views and likes

### Hypothesis Testing

* Tested whether content category significantly affects engagement.

* Result: The analysis found a statistically significant impact of content category on engagement.

### Linear Regression

* Built a regression model to predict likes using views.

* Achieved an R² value of approximately 0.71, indicating a strong relationship between views and likes.

## Key Insights

* Content preferences vary across countries.

* Music and Entertainment consistently receive high engagement in many regions.

* Lifestyle content performs particularly well in certain markets.

* Views are a strong predictor of likes, although other factors also influence engagement.

## Real-World Applications

* Content strategy optimization

* Regional audience targeting

* Social media marketing insights

* Data-driven decision making

## Feedback

Suggestions and contributions are welcome. If you found this project useful, consider giving it a star on GitHub.
