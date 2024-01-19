# Statistics Concepts for Aspiring Data Scientists

This README serves as a guide to essential statistics concepts for those entering the field of data science, with illustrative examples in Python.

## Exploratory Data Analysis (EDA) Phase

*Exploratory Data Analysis (EDA) is a critical step in the data science workflow. It involves summarizing the main characteristics of a dataset, often through visual methods. A thorough EDA provides a deeper understanding of the data's patterns, anomalies, and relationships between variables.*

### Data Types

Data types are crucial in understanding the kind of statistical techniques to apply:

- **Numeric**
  - *Continuous*: Values that can take any value within an interval (e.g., interval, float).
  - *Discrete*: Values that are countable in a finite amount of time (e.g., integer values).
- **Categorical**
  - A fixed set of values, such as names, surnames, or state names.
  - Binary categories, like 0/1 or true/false.
  - Ordinal categories, such as numerical ratings (1,2,3,4,5).

### Key Concepts of Statistics (Location)

- **Weight**: Values assigned manually or derived from another column in the dataset to emphasize certain data points.
- **Mean**: The sum of all values divided by the count of values. Simple to compute but sensitive to outliers.
- **Weighted Mean**: The sum of all values times their weights divided by the sum of the weights, accounting for varying importance among values.
- **Trimmed Mean**: The mean calculated after removing a fixed number of extreme values; often preferred to mitigate the impact of outliers.
- **Median**: The middle value in a sorted list of numbers; less affected by extreme values.
- **Weighted Median**: The value at which half the sum of the weights falls above and below in the sorted list.
- **Robust**: A statistic is robust if it is not influenced by extreme values.
- **Outlier**: A data point that differs significantly from other observations.

### Variability

Variability measures how data points are spread out:

- **Deviations**: The differences between observed values and an estimate of location.
- **Variance**: The average of the squared deviations from the mean, which is sensitive to outliers.
- **Standard Deviation**: The square root of the variance; commonly used but not robust against outliers.
- **Mean Absolute Deviation**: The mean of the absolute deviations from the mean.
- **Median Absolute Deviation**: The median of the absolute deviations from the median; robust against outliers.
- **Percentile**: The value below which a given percentage of observations falls.
- **Interquartile Range (IQR)**: The range between the first quartile (25th percentile) and the third quartile (75th percentile).

### Data Distribution for Numeric Data

- **Boxplot**: A graphical depiction of data distribution through quartiles.
- **Frequency Table**: A table that counts occurrences of data points within specified ranges.
- **Histogram**: A graphical representation of the frequency table.
- **Density Plot**: A continuous, smooth version of the histogram.

### Concepts and Data Distribution for Categorical Data

- **Mode**: The most frequently occurring category in a dataset.
- **Expected Value**: A weighted average of a numeric value based on its probability of occurrence, often used with categorical data.
- **Bar Charts**: Visual representation of the frequency or proportion of categories.
- **Pie Charts**: A circular statistical graphic divided into slices to illustrate numerical proportion.

### Correlation Between Variables

Analyzing the relationship between variables:

- **Correlation Coefficient**: A measure of the linear relationship between two variables, ranging from –1 (perfect negative correlation) to +1 (perfect positive correlation).
- **Correlation Matrix**: A table displaying the correlation coefficients between variables.
- **Contingency Table**: A table used to show the relationship between two or more categorical variables.
- **Scatterplot**: A graph that uses Cartesian coordinates to display values for two variables.
- **Violin Plot**: Similar to a boxplot but includes a kernel density estimate to show the distribution shape of the data.

### Feature Engineering (FE)

*Feature Engineering is the process of using domain knowledge to extract features from raw data. These features can be used to improve the performance of machine learning algorithms.*

