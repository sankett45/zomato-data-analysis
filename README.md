# Zomato Dataset Exploratory Data Analysis (EDA)

## Overview
This project performs Exploratory Data Analysis (EDA) on the Zomato dataset, collected from Kaggle. The analysis involves data cleaning, merging, handling missing values, and visualizing restaurant distributions across different countries.

## Dataset
The dataset consists of information about restaurants listed on Zomato, including:
- Restaurant names
- Country locations
- Cuisines offered
- Ratings
- Price range
- Online delivery and table booking options

## Steps Involved
1. **Loading and Merging Data**
   - Read the Zomato dataset and country code mappings.
   - Merge datasets on country code to obtain country names.

2. **Data Cleaning & Preprocessing**
   - Handle missing values (e.g., drop missing cuisine values).
   - Check and clean duplicate or irrelevant records.
   
3. **Exploratory Data Analysis (EDA)**
   - Analyze missing values with visualizations.
   - Examine restaurant distribution across countries.
   - Visualize the proportion of restaurants with table booking and online delivery.
   - Explore the distribution of price ranges and ratings.
   
4. **Geospatial Analysis**
   - Plot restaurant locations on a world map using geopandas.
   - Compare the most common cuisines across countries.
   
5. **Insights & Conclusions**
   - Identify key trends in restaurant ratings, pricing, and popularity.
   - Understand how location impacts restaurant availability and preferences.
   
## Technologies Used
- Python
- Pandas & NumPy for data manipulation
- Matplotlib & Seaborn for visualizations
- Geopandas for geospatial mapping

## Future Improvements
- Perform sentiment analysis on customer reviews.
- Predict restaurant ratings based on available features.
- Expand analysis to city-level insights.

## Installation & Usage
1. Clone the repository:
   ```bash
   git clone <repo-link>
   ```
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn geopandas
   ```
3. Run the analysis:
   ```bash
   python zomato_analysis.py
   ```

## Contributing
Feel free to open issues or submit pull requests to improve the analysis.

## License
This project is licensed under the MIT License.
