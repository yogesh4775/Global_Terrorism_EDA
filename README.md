- **Terrorism EDA Project**
  - **Project Overview**
    - Exploratory Data Analysis (EDA) on the Global Terrorism Database (1970–2017)
    - Identifies trends across:
      - Time (year/month/day)
      - Regions and countries
      - Attack methods, targets, and weapons
      - Casualties and incident severity
    - Notebook follows the provided capstone template and includes business-focused insights for decision-making

  - **Objectives**
    - Understand historical terrorism patterns
    - Detect high-risk regions and countries
    - Analyze distributions of attacks, targets, and weapons
    - Evaluate casualty trends and severity
    - Provide actionable recommendations for governments, security agencies, and policymakers

  - **Dataset**
    - **File**: `Global Terrorism Data.csv`
    - **Records**: ~181K incidents
    - **Key columns used**
      - **Date**: `iyear`, `imonth`, `iday`
      - **Location**: `country_txt`, `region_txt`, `city`
      - **Event details**: `attacktype1_txt`, `targtype1_txt`, `weaptype1_txt`
      - **Impact/outcome**: `nkill`, `nwound`, `success`

  - **Main Notebook**
    - **Completed notebook**: `Global_Terrorism_EDA_Submission.ipynb`
    - **Reference template**: `Sample_EDA_Submission_Template.ipynb`

  - **Tech Stack**
    - **Language**: Python 3.x
    - **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`
    - **Environment**: Jupyter Notebook / VS Code

  - **Project Workflow**
    - Import libraries and load dataset
    - Perform initial data inspection (shape, columns, info, summary)
    - Analyze missing values and duplicates
    - Perform data wrangling:
      - Select core analytical columns
      - Handle missing values logically
      - Create `event_date`
      - Create `casualties` and `casualties_capped` (IQR method)
    - Visualization + storytelling (UBM approach):
      - Univariate analysis
      - Bivariate analysis
      - Multivariate analysis
    - Business interpretation and recommendations

  - **Visualization Coverage**
    - 20+ meaningful visualizations included
    - Mandatory plots included:
      - Correlation heatmap
      - Pair plot
    - For each chart section, notebook includes:
      - Why the chart was chosen
      - Key insights
      - Business impact

  - **How to Run**
    - Place all files in one folder:
      - `Global Terrorism Data_Submission.csv`
      - `Global_Terrorism_EDA.ipynb`
    - Open the notebook in Jupyter / VS Code
    - Install dependencies (if needed):

      ```bash
      pip install pandas numpy matplotlib seaborn jupyter
      ```

    - Run all cells from top to bottom

  - **Expected Outcomes**
    - Clear understanding of terrorism trends over time
    - Identification of high-risk geographies and categories
    - Insights into casualty-heavy attack patterns
    - Actionable direction for prevention and preparedness strategy

  - **Deliverables**
    - `Global_Terrorism_EDA_Submission.ipynb` (final completed analysis notebook)
    - `README.md` (this file)
    - `Global Terrorism Data.csv` (input dataset)
