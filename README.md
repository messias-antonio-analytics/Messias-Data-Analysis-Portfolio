Messias Data Analytics Portfolio

Welcome to my Data Analytics Portfolio. This repository brings together practical projects developed with Python, Jupyter Notebook, data visualization, automation, and API integration.

My work focuses on transforming raw data into clear information that can support analysis, reporting, and decision-making.

Projects

1. KoboToolbox Data Automation and Analytics with Python

An automated data analysis project that connects to the KoboToolbox API, retrieves survey submissions, processes the data with Python, and generates indicators and visualizations.

The project was designed for humanitarian needs assessment and includes analyses related to demographic characteristics, displacement, protection, health, WASH, food security, shelter, livelihoods, education, priorities, and referrals.

Main capabilities

•
Connection to KoboToolbox through the API.

•
Automated retrieval of survey data.

•
Data processing with Pandas.

•
Identification and normalization of categorical responses.

•
Correction of duplicated categories caused by spaces, line breaks, and invisible characters.

•
Generation of charts with Matplotlib and Seaborn.

•
Export of charts and raw analytical outputs.

•
Compatibility with automated execution through GitHub Actions.

Technologies

Python · Pandas · Requests · Matplotlib · Seaborn · NumPy · KoboToolbox API · GitHub Actions

Project files

•
KoboToolbox Data Automation and Analytics with Python API.ipynb

•
Python analysis script

•
Project documentation


Security note: API tokens and sensitive data are not stored in the repository. Credentials must be configured through environment variables or platform Secrets.

2. Messias Nutrition Project

A data analysis project focused on nutrition-related information using Python and Jupyter Notebook.

The notebook demonstrates the process of exploring, organizing, analyzing, and visualizing data to identify relevant patterns and indicators.

Technologies

Python · Jupyter Notebook · Pandas · Data Visualization

Project file

•
messias_nutri_project.ipynb

Skills demonstrated

This portfolio demonstrates practical experience in:

•
Data collection through APIs.

•
Data cleaning and normalization.

•
Exploratory data analysis.

•
Automated reporting.

•
Data visualization.

•
Python scripting and notebooks.

•
Reproducible analytical workflows.

•
Humanitarian and nutrition-related data analysis.

•
Secure management of API credentials.

Repository structure

Plain Text


messias-data-analytics-portfolio/
├── README.md
├── LICENSE
├── .gitignore
├── kobotoolbox-data-automation/
│   ├── KoboToolbox Data Automation and Analytics with Python API.ipynb
│   ├── analise_kobo_mesmo_formato.py
│   ├── requirements.txt
│   └── README.md
└── messias-nutri-project/
    ├── messias_nutri_project.ipynb
    └── README.md



How to run the KoboToolbox project

Install the required dependencies:

Bash


pip install -r kobotoolbox-data-automation/requirements.txt



Configure the credentials as environment variables. On Windows PowerShell:

Plain Text


$env:KOBO_TOKEN="your_new_token"
$env:KOBO_UID="your_kobo_form_uid"



Run the Python script:

Bash


python kobotoolbox-data-automation/analise_kobo_mesmo_formato.py



Do not place the real token directly in the Python file. Do not commit .env files, tokens, or raw sensitive data to GitHub.

Future improvements

Possible future developments include an interactive Streamlit dashboard, scheduled report generation with GitHub Actions, automated publication of charts, and additional quality checks for incoming survey data.

Author

Messias Antonio

Data Analytics · Python · Data Automation · API Integration

License

This project is available under the license included in this repository.

