# 🗂️ User Behavior & Ratings Analysis Using Pandas

## 📝 **Project Overview**

This project focuses on performing advanced data manipulation and analysis using **Pandas**, a powerful Python library for data science. The project involves working with real-world datasets, specifically user data and movie ratings, to derive actionable insights through data cleaning, merging, aggregation, and exploratory data analysis (EDA).

---

## 🎯 **Objectives**

- Load, clean, and preprocess real-world datasets.
- Perform **data merging** to combine datasets effectively.
- Apply **grouping and aggregation** techniques to analyze trends.
- Conduct **exploratory data analysis (EDA)** to uncover hidden patterns.
- Generate insights from user and movie rating data to support business decisions.

---

## 📂 **Dataset Description**

1. **`ratings.txt`** 📄  
   - Contains user ratings for various movies.  
   - **Fields:** User ID, Movie ID, Rating, Timestamp.

2. **`users.txt`** 👥  
   - Holds demographic information about the users.  
   - **Fields:** User ID, Gender, Age, Occupation, Zip-code.

---

## ⚙️ **Technologies Used**

- **Python Libraries:**
  - `Pandas` for data manipulation and analysis
  - `NumPy` for numerical operations
  - `Matplotlib` & `Seaborn` for basic data visualization
- **Tools:** Jupyter Notebook for interactive data exploration

---

## 📊 **Project Workflow**

1. **Data Loading:**
   - Importing data from `ratings.txt` and `users.txt` using `pandas.read_table()`.

2. **Data Cleaning:**
   - Handling missing values.
   - Renaming columns for clarity.
   - Ensuring data types are consistent.

3. **Merging Datasets:**
   - Combining ratings and user data on `User ID` to create a unified dataset.

4. **Exploratory Data Analysis (EDA):**
   - Analyzing rating distribution across demographics.
   - Identifying top-rated movies and user engagement patterns.
   - Grouping data by age, gender, and occupation to derive meaningful insights.

5. **Aggregation and Grouping:**
   - Calculating average ratings, total ratings per user, and movie popularity.
   - Using `groupby()`, `agg()`, and pivot tables for summarization.

---

## 📈 **Key Insights & Results**

- Discovered **user rating patterns** based on demographics like age and gender.
- Identified **top-rated movies** and **most active users**.
- Analyzed how different age groups and occupations influence movie preferences.
- Uncovered trends in rating behavior over time.

---

## 🚀 **How to Run the Project**

1. **Clone the Repository:**
   ```bash
   git clone [GitHub Repository Link]
   ```
2. **Install Dependencies:**
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. **Place the Required Files:**
   - Ensure `ratings.txt` and `users.txt` are in the same directory as the notebook.

4. **Open the Notebook:**
   ```bash
   jupyter notebook Nikitha_kadaparthi_Pandas_HW4.ipynb
   ```
5. **Run the Notebook:**
   - Execute each cell to perform data analysis.
   - Modify code if you'd like to explore additional insights.

---

## 🤔 **Future Improvements**

- Incorporate **time-series analysis** to study rating trends over time.
- Apply **advanced statistical methods** to identify rating biases.
- Develop **recommendation systems** based on user preferences.
- Visualize key findings using **interactive dashboards** (Plotly, Dash).

---

## 🙌 **Contributions**

Contributions are welcome! Feel free to fork the repository, suggest improvements, or submit pull requests.

---

**Author:** Nikitha Kadaparthi  
**GitHub:** [GitHub Profile](https://github.com/Nikithakadaparthi)  
**LinkedIn:** [LinkedIn Profile](https://www.linkedin.com/in/nikitha-kadaparthi-4a42321a8/)

> *"Turning raw data into actionable business insights with the power of Pandas."*

