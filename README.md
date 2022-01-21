# econ-etl
### Team Members
* MaryClare Colombo
* Victoria Barbosa Munoz
* Jorge Hernandez
* Sviatoslav Piasta
* Keith Moravec

### Question:  Are leading economic indicators that most every day people use correlated? How have these indicators changed over time?

### Step 1:  Identify Sources:
* FRED  https://fred.stlouisfed.org
* EducationData.org

### Indicators of interest
* House Prices
* Gas Prices
* College
* Average Salary
* CPI
* Stock Market Indexes
* Population
* 30 Year Mortgage Rate

### Step 2:  Proposed Methodology
* Download all data into Panda's df 
* Standardize all df by date.
* Standardize all date formats and intervals
* Create Schemata in Postgres - each df will be a table - PK=Date 
* Load df to Postgres
