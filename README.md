# Global Terrorism EDA Project

## Project Overview
This project performs an Exploratory Data Analysis (EDA) on the **Global Terrorism Database (1970-2017)** to identify terrorism trends across time, regions, countries, attack methods, targets, weapons, and casualties.  
The notebook is structured to match the provided capstone template and includes business-focused insights for decision-making.

## Objective
- Understand historical terrorism patterns.
- Detect high-risk regions and countries.
- Analyze attack, target, and weapon distributions.
- Evaluate casualty trends and severity.
- Provide actionable recommendations for governments, security agencies, and policy makers.

## Dataset
- **File:** `Global Terrorism Data.csv`
- **Records:** ~181K incidents
- **Key columns used:**
  - `iyear`, `imonth`, `iday` (date)
  - `country_txt`, `region_txt`, `city` (location)
  - `attacktype1_txt`, `targtype1_txt`, `weaptype1_txt` (event details)
  - `nkill`, `nwound`, `success` (impact/outcome)

## Main Notebook
- **Completed Notebook:** `Global_Terrorism_EDA_Submission.ipynb`
- **Reference Template:** `Sample_EDA_Submission_Template.ipynb`

## Tech Stack
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook

## Project Workflow
1. Import libraries and load dataset.
2. Initial data inspection (shape, columns, info, summary).
3. Missing value and duplicate analysis.
4. Data wrangling:
   - selected core analytical columns
   - handled missing values logically
   - created `event_date`
   - created `casualties` and `casualties_capped` (IQR method)
5. Visualization and storytelling (UBM approach):
   - Univariate analysis
   - Bivariate analysis
   - Multivariate analysis
6. Business interpretation and recommendations.

## Visualization Coverage
- 20+ meaningful visualizations included.
- Mandatory plots included:
  - Correlation Heatmap
  - Pair Plot
- For each chart section, the notebook includes:
  - why this chart was chosen
  - key insights
  - business impact

## How to Run
1. Place all files in one folder:
   - `Global Terrorism Data_Submission.csv`
   - `Global_Terrorism_EDA.ipynb`
2. Open notebook in Jupyter/VS Code.
3. Install dependencies (if needed):
   ```bash
   pip install pandas numpy matplotlib seaborn jupyter
   ```
4. Run all cells from top to bottom.

## Expected Outcomes
- Clear understanding of terrorism trends over time.
- Identification of high-risk geographies and categories.
- Insight into casualty-heavy attack patterns.
- Actionable direction for prevention and preparedness strategy.

## Deliverables
- `Global_Terrorism_EDA_Submission.ipynb` (final completed analysis notebook)
- `README.md` (this file)
- `Global Terrorism Data.csv` (input dataset)

