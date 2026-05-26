# Gurgaon Real Estate Analysis | Python, Pandas, Matplotlib, Seaborn

**Project Overview**
-
- **Purpose:** Analyze a Gurgaon real-estate dataset and answer common market questions.
- The analysis is implemented in [main.py](main.py).
- **Data:** Uses [real_estate_data.csv](real_estate_data.csv) with columns like `price`, `area`, `rate_per_sqft`, `status`, `rera_approval`, `flat_type`, `bhk_count`, `locality`, `socity`, and `company_name`.

**Dependencies**
-
- **Python:** `3.8+`
- **Libraries:** `pandas`, `matplotlib`, `seaborn`
 - **Install:** `pip install -r requirements.txt`

**Usage**
-
- **Run:** `python main.py`
- **Output:** Prints summary answers to several questions and displays two scatter plots (area vs price, area vs rate_per_sqft).

**Data Cleaning**
-
- **Cleaning performed by the script:** removes duplicates, strips/normalizes text columns, and converts numeric columns after removing commas.


**What It Analyzes**
-
- **Costliest flat:** Finds the single most expensive listing.
- **Locality averages:** Localities with highest average price and highest average rate per sqft.
- **Status comparison:** Compares average prices for `ready to move` vs `under construction`.
- **RERA premium:** Compares average price for RERA-approved vs not-approved properties.
- **Area vs price:** Visualizes how area relates to price.
- **BHK & property type:** Identifies the most expensive BHK configuration and property type by `rate_per_sqft`.
- **Builders:** Lists the top 5 builders by average `rate_per_sqft`.
- **Price per sqft vs area:** Visualizes whether larger homes are more expensive per sqft.




