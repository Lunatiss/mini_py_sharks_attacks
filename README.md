# 🦈 Shark Tales: Unraveling the Mysteries of Messy Data

👩‍💻 This project contain notebook associated with it. You can access [here](https://github.com/Lunatiss/mini_py_sharks_attacks/blob/main/py_shark.ipynb).

## Introduction
Welcome to the Shark Tales Data Wrangling project! In this adventure, we embarked on a journey to clean a messy data set known as "Shark Attacks" using various data wrangling techniques. Our mission was not only to tame the unruly data but also to prepare it for analysis for a use case of our choice. Throughout this exhilarating quest, we sharpened our Python skills, advanced toward mastery as data analysts, fostered teamwork, and honed our problem-solving abilities.

### Set Hypothesis
In coastal regions with high recreational activity, such as the east coast of the United States, Australia, and South Africa, shark attacks are likely to be more frequent during the summer months due to the greater influx of people in the water and increased recreational water activities during this season.

### Original Dataset Overview
The original dataset comprised 23 columns and 6969 rows, documenting shark attacks over the past centuries. Most columns contained data of object and float types. However, the data were not standardized, with varying values within each column. For instance, the "Gender" column contained values like 'F', 'Female', 'Masc', 'M', etc.

### Structure and Process of Data Cleaning and Analysis
To streamline our analysis, we decided to focus on the last 20 years of data. We created filters to exclude irrelevant years and columns, resulting in a refined dataset with 11 columns and 2324 rows.

#### Data Cleaning Steps:
1. **Filtering by Timeframe:** We filtered out data beyond the last 20 years.
2. **Selecting Relevant Columns:** We retained only the columns relevant to our analysis.
3. **Standardizing Values:** We standardized values within each column.
   - **Column Type:** Categorized records into 'Unprovoked', 'Provoked', 'Unconfirmed', and 'Exogenous' using regex pattern.
   - **Column Country:** Converted records to lowercase with the first letter in uppercase.
   - **Column Activity:** Utilized regular expressions to categorize activities into 5 patterns using regex pattern.
   - **Column Species:** Employed regex to retain records of the 6 most well-known shark species.
4. **Date Transformation:** Transformed "Date" into the date format for consistency.
5. **Defining Categories:** Utilized regex and dictionaries to define categorical values.
6. **Function Definition:** Created reusable functions to streamline data cleaning processes.

## Conclusion
Through meticulous data wrangling efforts, we transformed a messy dataset into a clean and structured format suitable for analysis. This project not only enhanced our technical skills but also sharpened our problem-solving abilities and teamwork dynamics. We are now well-equipped to delve into insightful analyses using this refined dataset.
