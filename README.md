# Professional Expectations Analysis Project

This project analyzes professional expectations and preferences using survey data. The analysis includes demographic breakdowns, professional priorities by gender and socioprofessional categories, and preferences for independence in professional activities.

This project is implemented using **R** with a focus on data cleaning, descriptive statistics, and visualization.

---

## Features

- **Data Cleaning**: Handles missing values and converts character variables to factors.
- **Descriptive Statistics**:
  - Age distribution.
  - Gender breakdown.
  - Socioprofessional categories of parents.
- **Professional Expectations Analysis**:
  - Priorities by gender.
  - Expectations by socioprofessional categories.
- **Visualization**:
  - Bar charts for frequencies and priorities.
  - Scatter plots for correlations.
- **Custom Visualizations**: Highlights trends and relationships between survey questions.

---

## Project Structure

```
📁 Project Folder
├── data_questio.csv               # Dataset for analysis
├── etude.py                       # Python script for extended data processing
├── main.py                        # Main R script for data analysis
├── README.md                      # Project documentation
```

---

## Installation

### Requirements
This project requires **R** and the following R libraries:
- `tidyverse`
- `ggplot2`

### Steps
1. Install R from [CRAN](https://cran.r-project.org/).
2. Install the required packages in R:
   ```R
   install.packages(c("tidyverse", "ggplot2"))
   ```

---

## Usage

### Running the Analysis
1. Ensure `data_questio.csv` is in the working directory.
2. Run the script `main.py` in RStudio or your preferred R environment:
   ```R
   source("main.py")
   ```

---

## Key Outputs

1. **Age Distribution**:
   - Frequency table and bar chart of age groups.
   
2. **Gender Priorities**:
   - Bar charts showing professional expectations by gender.
   
3. **Socioprofessional Categories**:
   - Distribution of respondents' parents' socioprofessional categories.
   - Professional expectations by socioprofessional background.

4. **Correlation Insights**:
   - Scatter plot between initial and current professional clarity.

5. **Independence Preferences**:
   - Bar chart of preferences for independent professional activities.

6. **Corporate Values Sensitivity**:
   - Distribution of values respondents are most sensitive to in corporate policies.

---

## Visualizations

- **Bar Charts**: Represent distribution and frequencies.
- **Scatter Plots**: Highlight correlations between variables.
- **Grouped Bar Charts**: Compare professional priorities across groups.

---

## Data Cleaning Process

1. **Column Renaming**: Removes special characters and spaces from column names.
2. **Missing Values**: Drops rows with missing data.
3. **Data Transformation**: Converts character columns to factors.

---

## Contributing

Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Open a pull request.

---

## License

This project is licensed under the MIT License.

---

## Contact

**Shimwa Galille**  
[GitHub Profile](https://github.com/Shimwa-Galille)

---

## Acknowledgements

- The project leverages R packages like `tidyverse` and `ggplot2` for data manipulation and visualization.

