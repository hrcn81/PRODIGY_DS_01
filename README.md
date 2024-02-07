# Prodigy-Internship

#### Task_DS_01

#### Population Analysis of India (1960 - 2020) 📊

This GitHub repository holds a Python script leveraging Pandas and Matplotlib to analyze and visualize population data for various countries, with a focus on India. Here's a concise conclusion with a touch of emojis:

1. **Data Loading and Cleaning:**
   - The initial dataset (`df1`) contains information on the total population of various countries from 1960 to 2022.
   - Unnecessary columns like 'Country Code', 'Indicator Name', and 'Indicator Code' were dropped to create a cleaner dataset (`df2`).

2. **India's Population Overview:**
   - The script confirms the presence of data for India using the `isin` function, indicating that India is indeed present in the dataset.
   - A subset of the dataset (`cont`) focusing on India's population over the years was extracted.

3. **Population Visualization:**
   - The script generates a bar plot and a histogram to visualize India's population trend from 1960 to 2020.
   - The bar plot shows a steady increase in population over the years.
   - The histogram provides a distribution of population data, highlighting the most frequent population ranges.

4. **Conclusion:**
   - The analysis reveals a consistent growth in India's population over the examined period.
   - The visualizations offer a clear representation of the population dynamics, showcasing the overall trend and distribution.

5. **Usage:**
   - Users can utilize this script to analyze population data for different countries by modifying the country names in the `isin` and subsequent filtering steps.
   - The script can be a useful starting point for exploring and visualizing population trends using Pandas and Matplotlib.
