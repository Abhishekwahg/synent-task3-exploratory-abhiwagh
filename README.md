# 🎬 Netflix Data - Exploratory Data Analysis (EDA)

This repository contains an in-depth **Exploratory Data Analysis (EDA)** on the Netflix Movies and TV Shows dataset. The primary goal of this project is to uncover trends, analyze content distribution, and derive meaningful insights about Netflix's global content library.

---

## 📌 Project Objectives
* Compare the share of **Movies vs. TV Shows** available on the platform.
* Analyze the **growth of content** added to Netflix over the years.
* Identify the **top content-producing countries**.
* Understand content distribution based on **Genres** and **Maturity Ratings**.
* Clean and handle missing values to prepare the data for analysis.

---

## 📊 About the Dataset
The dataset includes information about TV shows and movies available on Netflix up to recent years. It contains the following features:
* `show_id`: Unique ID for every movie/show.
* `type`: Identifier - A Movie or TV Show.
* `title`: Title of the movie/show.
* `director`: Director of the movie.
* `cast`: Actors involved in the movie/show.
* `country`: Country where the movie/show was produced.
* `date_added`: Date it was added on Netflix.
* `release_year`: Actual release year of the movie/show.
* `rating`: TV rating of the movie/show (e.g., PG-13, TV-MA, R).
* `duration`: Total duration in minutes or number of seasons.
* `listed_in`: Genere/Category.

---

## 🛠️ Tech Stack & Libraries
The following Python libraries were used for data manipulation, cleaning, and visualization:
* **Python** (Core Language)
* **Pandas**: For data loading, cleaning, and manipulation.
* **NumPy**: For numerical computations.
* **Matplotlib**: For creating static, basic visualizations.
* **Seaborn**: For advanced and aesthetically pleasing statistical charts.

---

## 🔄 Workflow & Steps

### 1. Data Inspection
* Loaded the dataset using `pd.read_csv()`.
* Checked data types, shape, and summary statistics using `.info()`, `.shape`, and `.describe()`.

### 2. Data Cleaning & Preprocessing
* Identified and handled missing values in `director`, `cast`, and `country` (imputed with 'Unknown' where appropriate).
* Dropped rows with critical missing values that couldn't be imputed.
* Converted `date_added` to a proper datetime format and extracted `year_added` and `month_added` for time-series analysis.

### 3. Data Visualization & Insights
* Used Pie Charts and Bar Plots to visualize the categorical distribution of content.
* Created Line Charts to plot the trend of content additions over time.
* Used Count Plots to rank the top genres and maturity ratings.

---

## 🚀 How to Run This Project Locally

1. **Clone the repository:**
```bash
   git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
