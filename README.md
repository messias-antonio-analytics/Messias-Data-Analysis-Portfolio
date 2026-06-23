Health & Nutrition Integrated Dashboard

Project Overview

This project presents a prototype of an integrated data analysis dashboard designed for UNICEF Mozambique, focusing on health and nutrition indicators within humanitarian and emergency contexts. Developed by Messias António, a Data Specialist, this dashboard aims to provide actionable insights by combining health admissions data with logistics information (e.g., stock levels of therapeutic food like Plumpy'Nut). The primary goal is to enhance operational decision-making, facilitate resource allocation, and improve the prioritization of interventions in vulnerable districts.

Key Features & Analyses

•
Integrated Data Model: Combines health data (Severe Acute Malnutrition - SAM, Moderate Acute Malnutrition - MAM admissions, Vaccination Coverage) with logistics data (Plumpy'Nut stock levels) to provide a holistic view.

•
Malnutrition Trends: Visualizes SAM and MAM admissions by district, highlighting areas with the highest burden of acute malnutrition.

•
Stock Control & Alerts: Monitors Plumpy'Nut stock levels against minimum thresholds, identifying districts with critical stock shortages and triggering urgent replenishment alerts.

•
Geographic Prioritization Map: Utilizes interactive mapping (Plotly Express) to visually represent districts based on an integrated priority level, considering both health needs (SAM admissions, vaccination coverage) and logistical challenges (critical stock). This allows for rapid identification of areas requiring maximum emergency attention or focused logistical support.

•
Actionable Insights: Generates clear, data-driven recommendations for immediate operational responses, such as identifying districts for increased clinical attention or urgent stock replenishment.

Technologies Used

•
Python: The core programming language for data manipulation and analysis.

•
Pandas: Essential for data structuring, cleaning, and integration.

•
NumPy: Used for numerical operations and conditional logic.

•
Matplotlib & Seaborn: Employed for static data visualization, including bar plots for malnutrition admissions and stock levels.

•
Plotly Express: Utilized for creating interactive geographic maps, enabling dynamic exploration of priority areas.

Impact & Application

This dashboard serves as a critical tool for humanitarian organizations like UNICEF and MSF to:

•
Rapidly Identify Needs: Pinpoint districts with escalating health crises or critical resource shortages.

•
Optimize Resource Allocation: Guide the distribution of medical supplies and therapeutic food to areas with the highest integrated priority.

•
Inform Strategic Planning: Provide a clear overview of the situation to inform emergency preparedness and response strategies.

•
Enhance Collaboration: Offer a common operational picture for coordination teams, government counterparts, and NGOs.

How to Run the Code

1.
Clone the Repository:

Bash


git clone [Your GitHub Repository URL]
cd health-nutrition-dashboard





2.
Install Dependencies: Ensure you have Python installed. Then, install the required libraries:

Bash


pip install pandas numpy matplotlib seaborn plotly





3.
Execute the Script:

Bash


python health_nutrition_dashboard.py



The script will output textual analysis summaries and display the generated plots. The interactive map will open in your default web browser.



Developer

Messias António

•
Email: messiasantonio20200@gmail.com



