# Environmental & Health Data Visualization

Two exploratory data visualizations examining environmental pollution and recommended sleep patterns using Python.

The project focuses on transforming raw tabular data into clear visual representations of relationships, ranges, and real-world patterns.

## Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook
- Data Cleaning
- Exploratory Data Analysis

## Ocean Plastic Pollution

![Drivers of Ocean Plastic Pollution](images/plastic-pollution-drivers.png)

This visualization explores potential drivers of ocean plastic pollution by comparing coastal exposure with the percentage of mismanaged plastic waste entering the ocean.

Rainfall is incorporated as a third variable through the colour scale, while logarithmic axes are used to represent variables with large differences in magnitude.

### Techniques Demonstrated

- Data filtering and cleaning
- Derived-variable calculation
- Multivariable scatter visualization
- Logarithmic scaling
- Continuous colour encoding

## Recommended Sleep by Age

![Recommended Sleep by Age](images/recommended-sleep-by-age.png)

This visualization presents the National Sleep Foundation's recommended lower and upper sleep-duration ranges across different age groups.

Rather than displaying a single value for each group, the visualization emphasizes the recommended interval.

### Techniques Demonstrated

- Ordered categorical data
- Range visualization
- Custom plotting
- Visual hierarchy and styling

## Data

The analysis uses:

- `river-plastics.csv`
- `sleep.csv`

## Notebook

The complete data preparation and visualization code is available in [`analysis.ipynb`](analysis.ipynb).
