## **Analysis of Netflix Data Using Python**

### **Project Overview**

This project aims to analyze Netflix data using Python to gain insights into content trends, popular actors and directors, and sentiment analysis. By exploring the provided Netflix dataset, we can uncover valuable information about the platform's content offerings.

### **Dataset**

The dataset used for this analysis is available on Kaggle. It contains information about Netflix titles, including show ID, type, title, director, cast, country, date added, release year, rating, duration, listed in, and description.

### **Project Structure**

```
├── README.md
├── netflix_data_analysis.ipynb
└── netflix_data.csv
```

### **Project Methodology**

The project follows a data analysis pipeline:

1. **Data Loading and Exploration:**
   * Load the dataset into a Pandas DataFrame.
   * Explore the data structure, identify missing values, and understand data types.

2. **Data Cleaning and Preprocessing:**
   * Handle missing values (e.g., fill missing director names with "Director Not Specified").
   * Convert data types as needed.

3. **Exploratory Data Analysis (EDA):**
   * Analyze content rating distribution using a pie chart.
   * Identify top actors and directors based on the number of titles they're associated with.
   * Explore content production trends over time.

4. **Sentiment Analysis:**
   * Analyze the sentiment of content descriptions using the TextBlob library.
   * Determine the overall sentiment polarity of Netflix content.

### **Results and Insights**

The analysis reveals valuable insights, such as:

* **Content Rating Distribution:** The most common content rating is TV-MA, followed by TV-14.
* **Top Actors and Directors:** Identify the actors and directors with the highest number of titles on Netflix.
* **Content Production Trends:** Analyze the trend of content production over time, including movies and TV shows.
* **Sentiment Analysis:** Determine the overall sentiment polarity of Netflix content.

### **Future Work**

* **Genre Analysis:** Explore the popularity of different content genres.
* **Country Analysis:** Analyze content distribution by country.
* **Recommendation System:** Develop a recommendation system based on user preferences and content similarities.

### **Acknowledgments**
* Kaggle for providing the Netflix dataset.
* The Python community for developing essential libraries like Pandas, NumPy, and Matplotlib.
* The TextBlob library for sentiment analysis.
