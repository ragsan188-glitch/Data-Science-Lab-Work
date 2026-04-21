# Lab 2: Control Statements

## Description

This lab focuses on loading datasets from different file formats (CSV, TXT, and Excel) and analyzing them using Python libraries. The objective is to understand how file formats affect data structure and to perform basic exploratory data analysis.

## Dataset

* Source: Provided dataset (Facebook Friends data)
* Formats used:

  * CSV
  * TXT
  * Excel
* Description: Contains user-related features such as age, photos, posts, likes, and number of friends.

## Steps Performed

1. Imported required libraries (Pandas, Matplotlib, Seaborn)
2. Loaded datasets from CSV, TXT, and Excel formats
3. Compared dataset structures (shape and columns)
4. Identified formatting and encoding issues in CSV and TXT files
5. Selected Excel dataset for accurate analysis
6. Performed data inspection:

   * Column names
   * Data types
   * Head and tail of dataset
   * Missing values check
7. Generated statistical summary using `describe()`
8. Visualized data distribution using histograms

## Results

* CSV and TXT files were not properly structured due to delimiter and encoding issues
* Excel file contained clean and complete data
* Dataset has 715 rows and 18 columns
* No missing values were found
* Statistical summary provided insights into distribution of features such as age, posts, and friends

## Tools Used

* Python
* Pandas
* Matplotlib
* Seaborn
* Google Colab

## Conclusion

The lab demonstrated how different file formats impact data loading and structure. It also highlighted the importance of selecting the correct dataset format for analysis. Basic exploratory data analysis was successfully performed on the cleaned dataset.

## Author

Ragul Y S
