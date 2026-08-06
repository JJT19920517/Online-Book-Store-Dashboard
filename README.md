# Dash Board Images
![images](images/onlinebookstoreanalytics.png)
![images](images/Screenshot1.png)
![images](images/Authoranalysis.png)
![images](images/ratinganalysis.png)
![images](images/genreanalysis.png)
![images](images/languageanalysis.png)
![images](images/formatanalysis.png)
![images](images/insight.png)

# Online Bookstore Data Analysis

## 1. About the Project

This project focuses on analyzing an Online Bookstore dataset to identify meaningful patterns and insights related to books, authors, genres, ratings, languages, formats, series, and overall book performance. The project follows an end-to-end data analytics workflow, beginning with data collection and preprocessing in Excel and progressing to interactive dashboard development in Power BI. The objective is to transform raw bookstore data into meaningful visual insights that can support better understanding of book popularity, reader preferences, author performance, rating patterns, and other key characteristics of the dataset.

## 2. Data Collection

The dataset was collected from Kaggle and contains information about books available in an online bookstore, including details such as book title, author, publisher, language, genre, format, price, number of ratings, rating distribution, number of pages, series information, and other relevant attributes.

Source: Kaggle – Online Bookstore Dataset

The raw dataset was retained as the original source data and was used as the starting point for the preprocessing and analysis stages.

## 3. **Phase 1 – Data Preprocessing in Excel**

The raw dataset was imported into Excel and subjected to data quality checks and preprocessing before being used for dashboard development.

### Major preprocessing activities

- Identified and reviewed missing, blank, and null values.
- Standardized data types for numerical, text, and categorical fields.
- Cleaned and standardized text fields and capitalization.
- Identified and handled encoding issues in publisher and other text fields.
- Cleaned the Genre column to make it suitable for analysis and visualization.
- Reviewed blank values in fields such as Liked Percent and Number of Pages.
- Extracted volume numbers from the Series field.
- Created a Volume Number field for series-related analysis.
- Handled books without series or volume information appropriately.
- Cleaned author-related fields containing list-style values.
- Processed the RatingsByStars field to derive useful rating metrics.
- Calculated 5-star rating percentages where applicable.
- Created and standardized analytical categories required for the dashboard.
- Performed data validation and checked for inconsistencies before loading the data into Power BI.

### Challenges encountered

One of the major challenges was inconsistent text encoding in some publisher names, which resulted in unreadable characters. Another challenge was the presence of blank values, list-based genre and author fields, and rating information stored in text format. The Genre field also contained multiple values within individual records, which required careful handling before performing categorical analysis. These issues were addressed during preprocessing to make the dataset more consistent and suitable for analysis.

## 4. Phase 2 – Power BI Dashboard

The preprocessed dataset was imported into Power BI to create an interactive analytical report.

### Dashboard Analysis

The report includes analysis of:

- Overall Book Performance
- Author Analysis
- Genre Analysis
- Rating Analysis
- Language Analysis
- Book Format Analysis
- Key Insights

Interactive slicers, filters, buttons, and drill-down/interactions were implemented to allow users to explore the data dynamically.

### Report Creation

The Power BI report was designed with a clean and professional dashboard layout. Navigation buttons were created to allow users to move between different analytical pages. Interactive selections were also implemented, such as selecting an author to explore the books, ratings, and other information associated with that author.

### DAX Measures

DAX was used to create calculated measures and KPIs required for the analysis. Examples include:

- Total Books
- Total Ratings
- Average Rating
- Average Price
- 5-Star Rating Percentage
- Books by Rating Category
- Series Listed
- Average Number of Pages
- Author and Genre-related metrics

These measures were used across cards, charts, tables, and other Power BI visuals to provide dynamic analysis.

## 5. Key Insights

The dashboard enables users to identify patterns such as:

- Distribution of books across rating categories.
- Authors with the highest number of books and ratings.
- Popular genres and their distribution.
- Rating patterns and 5-star rating performance.
- Distribution of books across different languages.
- Comparison of different book formats.
- Characteristics of books belonging to different series.
- Relationships between book attributes and reader engagement.

## 6. Tools Used

- Microsoft Excel – Data preprocessing and data quality analysis
- Power BI – Data modeling, DAX calculations, visualization, and dashboard development
- Power Query – Data transformation and preparation

## 7. Project Workflow

- Raw Dataset
- Data Quality Analysis
- Excel Preprocessing
- Data Transformation
- Power BI Data Modeling
- DAX Measures
- Interactive Dashboard
- Analysis & Insights
