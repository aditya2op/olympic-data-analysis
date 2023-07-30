
# Complete Olympic Data Analysis

A Streamlit web app for analyzing Olympic Games data. The app allows users to explore various aspects of the Olympics, including medal tallies, overall analysis, country-wise analysis, and athlete-wise analysis.


## Authors

- [@AdityaMishra](https://github.com/aditya2op)


## Features

**Features:**

1. **Medal Tally Analysis:**
   - Users can select a specific year and country to view the medal tally for that year and country.
   - If 'Overall' is selected for both year and country, it shows the overall medal tally for all years and countries.
   - The medal tally is displayed in a table format.

2. **Overall Analysis:**
   - Displays top statistics related to the Olympics, such as the number of editions, host cities, sports, events, athletes, and participating nations.
   - A heatmap is presented showing the number of events held for each sport over time.

3. **Country-wise Analysis:**
   - Users can select a country from the sidebar to view its medal tally over the years in a line chart.
   - It also shows a heatmap indicating the sports in which the selected country has excelled over the years.

4. **Athlete-wise Analysis:**
   - Displays a distribution plot of the age of athletes, categorized by overall age, gold medalists, silver medalists, and bronze medalists.
   - Another distribution plot shows the age distribution of gold medalists for various famous sports.
   - A line chart displays the participation of men and women athletes over the years.

**Data Sources:**

- The app uses two CSV files: 'athlete_events.csv' and 'noc_regions.csv' to load Olympic Games data and region information, respectively.

**Libraries Used:**

- The app uses several Python libraries for data manipulation, visualization, and interaction:
   - Streamlit: For creating the web app interface.
   - Pandas: For data manipulation and analysis.
   - Plotly Express: For interactive data visualization.
   - Matplotlib and Seaborn: For additional data visualization.
   - Plotly Figure Factory: For creating custom plots.

**Overall, the app provides an interactive and user-friendly interface for exploring and analyzing Olympic Games data, enabling users to gain insights into the performance of countries, athletes, and sports over time.**

Please note that this is a summary based on the provided code, and the actual functionality might have additional details or variations.


## Demo

