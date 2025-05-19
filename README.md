# Crime Prediction Dashboard 🌦️

A Python-powered interactive dashboard to analyze crime patterns in relation to weather conditions in Toronto.
## Overview

The Crime Prediction Dashboard is a data-driven project that merges crime and weather datasets to explore how environmental factors influence crime rates. Built with Python in a Jupyter Notebook, this tool provides interactive visualizations that allow users to filter crime categories, seasons, and temperature ranges to uncover meaningful trends. It’s ideal for data enthusiasts, researchers, and urban planners interested in predictive analytics and geospatial insights.
## Key Features

    Interactive dashboard with dropdown filters for crime categories (e.g., Assault, Robbery), seasons, and temperature bands.

    Visualizations including heatmaps, bar plots, line graphs, and pie charts to reveal crime trends.

    Integration of crime data with weather variables for a comprehensive analysis.

    Built using Python libraries: pandas, matplotlib, seaborn, and ipywidgets.

## Tech Stack

    Language: Python 3

    Libraries: pandas, matplotlib, seaborn, ipywidgets

    Environment: Jupyter Notebook

    Datasets: Custom crime and weather data (available upon request)

## Project Structure

Crime-Prediction-Dashboard/
├── ADT_Project.ipynb         # Main notebook with code and dashboard
├── datasets/                 # Placeholder for crime and weather CSV files
├── README.md                 # Project documentation
└── requirements.txt          # Python dependencies

## Getting Started

### Clone the repository:

git clone https://github.com/your-username/Crime-Prediction-Dashboard.git
cd Crime-Prediction-Dashboard

### (Optional) Create and activate a virtual environment:

python -m venv venv
source venv/bin/activate        # On Windows: venv\Scripts\activate

### Install dependencies:

pip install -r requirements.txt

Add your datasets (crime.csv and weather.csv) to the datasets/ folder.

### Launch Jupyter Notebook:

    jupyter notebook

    Open ADT_Project.ipynb and run all cells to load the interactive dashboard.

### Usage

Use the dropdown menus to filter data by:

    Crime Category (e.g., Assault, Break and Enter)

    Season (Winter, Summer, Fall)

    Temperature Category (Cold, Mild, Warm, Hot)

Click Update Dashboard to refresh visualizations, including heatmaps, bar charts, line plots, and pie charts.
Troubleshooting

    If you encounter errors like ValueError: zero-size array to reduction operation fmin, ensure your filters return non-empty data or update the notebook to handle empty results gracefully.

    Confirm datasets are correctly placed and formatted in the datasets/ folder.

    Verify all dependencies are installed properly.

### Future Enhancements

    Implement predictive models (e.g., Random Forest, LSTM) for crime forecasting.

    Deploy as a web application using Streamlit or Dash.

    Add geospatial crime hotspot mapping.

    Improve error handling and user feedback for empty data filters.

## Contribution

Contributions are welcome! Please fork the repo, create a feature branch, commit your changes, and open a pull request. Follow the repository’s code of conduct.
License

## Contact

For questions or dataset access, please contact:
Email: patel49b@uwindsor.ca
GitHub Issues: Open an issue on this repository.
