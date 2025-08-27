📊 Population Distribution Visualization – India

This project visualizes India's population distribution using data from the World Bank and UN World Population Prospects (2022).
The goal is to create simple and clear charts (bar chart/histogram) showing how the population is divided into different age groups.

📁 Dataset

The dataset comes from the World Bank API:

API_SP.POP.TOTL_DS2_en_csv_v2_447796.csv → Main population data (country-wise, year-wise)

Metadata_Country_API_SP.POP.TOTL_DS2_en_csv_v2_447796.csv → Metadata about countries

Metadata_Indicator_API_SP.POP.TOTL_DS2_en_csv_v2_447796.csv → Metadata about indicators

Additional age-group values are referenced from the UN World Population Prospects 2022 report.

🚀 Features

Load and process population dataset for India.

Extract the latest population statistics (2022).

Visualize age group distribution (0–20, 21–64, 65+).

Generate a bar chart for easy interpretation.

🛠️ Technologies Used

Python 3

Google Colab / Jupyter Notebook

Pandas → Data processing

Matplotlib → Visualization

📊 Visualization Example

Bar chart showing India’s population distribution by age (2022):

0–20 years → 512M (36.1%)

21–64 years → 807M (57.0%)

65+ years → 98M (6.9%)

▶️ How to Run

Clone this repository:

git clone https://github.com/your-username/population-distribution.git
cd population-distribution


Open Google Colab or Jupyter Notebook.

Upload the dataset CSV files.

Run the Python script (population_distribution.ipynb).

📌 Future Improvements

Automate age-group calculation using UN population-by-age datasets.

Add gender distribution visualization.

Extend analysis for multiple countries.


🙌 Acknowledgements

World Bank Open Data

UN World Population Prospects (2022)

Visualization inspired by statsOfIndia.in


<img width="695" height="547" alt="task1" src="https://github.com/user-attachments/assets/2b70e397-0bcf-4edc-be65-050940e33323" />
