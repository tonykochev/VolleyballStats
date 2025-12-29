# NCAA Rankings & Data Analysis Research

This repository contains code and data used to collect, analyze, and rank NCAA teams using multiple statistical models. The project includes web scraping, data cleaning, ranking algorithms (Massey and Colley), data mining experiments, and visual analysis through charts and graphs.

The goal of this project is to explore different ranking methodologies and compare how various models evaluate team performance based on historical game data as well as to improve those models for future use.

---

## Project Structure

The repository is organized into the following main components:

### 1. Data Scraping
Scripts that scrape game results and team data from NCAA-conference websites.

- Collects raw game data (scores, teams, dates, locations, etc.)
- Outputs structured datasets used by the ranking models
- Serves as the starting point for the entire analysis pipeline

---

### 2. Ranking Models

#### Massey Rating Model
Code implementing the Massey ranking system, which uses point differentials and linear algebra to rate teams.

- Builds the Massey matrix
- Solves for team ratings
- Allows experimentation with different features and weights

#### Colley Rating Model
Code implementing the Colley ranking system, which is based on wins and losses rather than score margins.

- Constructs the Colley matrix
- Produces normalized team rankings
- Useful for comparison against Massey results

---

### 3. Data Mining & Analysis
Files related to exploratory data analysis and data mining experiments.

- Feature exploration and model comparisons
- Statistical summaries and trend analysis
- Evaluation of how different variables affect rankings

---

### 4. Data Files
Includes datasets used throughout the project.

- CSV and Excel files containing raw and cleaned data
- Intermediate files generated during processing
- Final datasets used for ranking and visualization

---

### 5. Visualizations
Generated plots and images created during analysis.

- Ranking comparisons
- Team performance trends
- Model output visualizations
- Saved as image files for reporting and presentation

---

## Technologies Used

- **Python**
- **Pandas / NumPy**
- **BeautifulSoup / Requests** (for web scraping)
- **Matplotlib / Seaborn** (for visualizations)
- **Excel / CSV** for data storage and inspection
- **Linear Algebra** techniques for ranking models

---

## How to Use

1. **Scrape Data**
   - Run the scraping scripts to collect NCAA game data.
   - Verify output files are saved in the appropriate data directory.

2. **Clean & Prepare Data**
   - Process raw data into a format compatible with ranking models.

3. **Run Ranking Models**
   - Execute Massey and Colley model scripts.
   - Review generated rankings and outputs.

4. **Analyze & Visualize**
   - Run data mining and visualization scripts.
   - View generated graphs in the visualization/output folders.

---

## Notes

- Some scraped data may depend on website structure and may require updates if NCAA pages change.
- Excel files are included for transparency and manual verification.
- This project is intended for educational and analytical purposes.

---

## Future Improvements

- Automate the full pipeline from scraping to final rankings
- Add model evaluation metrics
- Expand to additional ranking systems
- Improve visualizations and dashboards

---

## Author

**Tony Kochev**

If you have questions or suggestions, feel free to reach out or open an issue.
