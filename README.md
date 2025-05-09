# ml-job-cleaning-portfolio
The 1000 ML Job Postings in USA dataset contains job listings related to machine learning roles across various companies and locations in the United States. Before performing any form of data analysis or visualization, it's essential to clean the dataset by addressing duplicate records and missing values. These issues, if not handled properly, can lead to misleading insights and reduce the overall quality of the analysis.

During the data cleaning process, duplicate rows were identified—most likely a result of repetitive web scraping—and were removed to ensure that job postings were not counted more than once. Furthermore, missing values were found in key columns such as Company, Location, and Description. Instead of dropping entire rows, which would reduce the dataset size, a more conservative approach was taken: missing Company and Location values were filled with "Unknown", and missing Description fields were filled with "No description provided". This helps preserve the dataset’s structure and ensures consistent formatting across all records.
## Goals:
1. Remove duplicate entries to prevent skewed results in analysis.
2. Handle missing values while retaining as much usable data as possible.
3. Ensure data consistency before proceeding to Exploratory Data Analysis (EDA) or modeling.
## Insight
1. Duplicate records were present and successfully removed to maintain data integrity.
2. Key columns like Company, Location, and Description contained missing values that were imputed using string placeholders.
3. Data cleaning improved the dataset’s reliability, making it ready for visual exploration and statistical evaluation.
## Advice
1. Always check for duplicates when working with scraped datasets, as repeated entries are common.
2. Use contextual imputation (e.g., filling missing values with "Unknown" or default phrases) instead of dropping rows unnecessarily, especially when working with small datasets.
3. Clean data before any visualization or modeling step to avoid bias and improve the quality of insights drawn from the dataset.

If you have any suggestions or feedback, please don't hesitate to contact to me in direct message on 
LinkedIn: https://www.linkedin.com/in/evelynegidiasitopu and Email: evelynsitopu@gmail.com
