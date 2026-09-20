# MSCS 634 - Lab 1

## Data Visualization, Data Preprocessing, and Statistical Analysis

This lab focuses on basic data analysis and preprocessing techniques using Python in Jupyter Notebook. I used a retail sales dataset containing product, region, units sold, unit price, customer rating, and revenue information.

## Work Completed

The dataset was explored using different visualizations, including a bar chart, scatter plot, histogram, and box plot.

I checked the dataset for missing values and replaced missing numerical values using the mean and missing categorical values using the mode.

I used the IQR method to identify and remove an outlier from the Units_Sold column.

I also performed data reduction using random sampling and column removal. Min-Max scaling was applied to selected numerical columns, and customer ratings were converted into categories using discretization.

Finally, I performed statistical analysis using descriptive statistics, central tendency measures, dispersion measures, and correlation analysis.

## Key Insights

The visualizations showed differences in sales volume across products.

One unusually high Units_Sold value was identified as an outlier.

The correlation analysis showed a strong positive relationship between Unit_Price and Revenue in this dataset.

## Challenges and Decisions

I used the mean to replace missing Customer_Rating values because it is numerical.

I used the mode to replace missing Region values because it is categorical.

The IQR method was used for outlier detection because it is a simple and useful method for identifying unusual values.

## Files

- `MSCS_634_Lab_1.ipynb` - Jupyter Notebook
- `sales_data.csv` - Dataset used in the lab
- `README.md` - Lab description and summary
