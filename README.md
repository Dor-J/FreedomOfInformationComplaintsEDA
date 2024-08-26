# FreedomOfInformationComplaintsEDA
Freedom of Information Complaints Database - Exploratory Data Analysis (EDA)

## Project Overview
This project involves the analysis of a dataset containing complaints related to Freedom of Information (FOI) requests. The main objective of this analysis is to uncover insights and trends in the complaints, such as the entities most frequently complained against, the subjects of these complaints, and the outcomes of the complaints.

    Table of Contents
    Project Overview
    Dataset Information
    Analysis Goals
    Installation and Setup
    Exploratory Data Analysis (EDA)
    Key Findings
    Future Work
    Contributing
    License

## Dataset Information
Columns:
_id: Unique identifier for each complaint.
Complaint Number: The official number assigned to the complaint.
Channel of Receipt: The medium through which the complaint was received (e.g., Online Form, Email).
Initial Request Date for Information: The date when the initial FOI request was made.
Complaint Subject: The subject matter of the complaint.
Complaint Receipt Date: The date the complaint was received.
Entity Complained Against: The government entity or organization against which the complaint was made.
Closing Date: The date when the complaint was resolved.
Decision: The outcome of the complaint (e.g., Justified, Unjustified).
Status: The current status of the complaint (e.g., Completed).
Complainant Type: The type of complainant (e.g., Citizen, Organization).
Freedom of Information Request Subject: Specific subject matter of the FOI request.
Number of Treatment Days: The number of days taken to resolve the complaint.
Complaint Receipt Year: The year when the complaint was received.
Complaint Receipt Month: The month when the complaint was received.
Initial Response Days: The number of days taken to provide the initial response to the FOI request.

## Analysis Goals
Entity Analysis:
Identify the most frequently complained about entities.
Analyze trends in complaints over time for these entities.

Complaint Subject Analysis:
Investigate the most common subjects of complaints.
Explore how these subjects vary by complainant type.

Decision Outcome Analysis:
Calculate success rates (e.g., percentage of complaints deemed justified).
Examine correlations between variables like treatment days, initial response days, and complaint outcomes.

Time to Resolution:
Analyze the time taken to resolve complaints and how it varies by entity, subject, and year.

## Installation and Setup
Prerequisites
Python 3.8 or higher
Required Python packages (listed in requirements.txt):
pandas
numpy
matplotlib
seaborn
statsmodels

### Installation
Clone this repository:
bash
Copy code
git clone https://github.com/Dor-J/FreedomOfInformationComplaintsEDA.git
cd foi-complaints-eda
Install the required Python packages:

bash
Copy code
pip install -r requirements.txt
Run the Jupyter Notebook:

bash
Copy code
jupyter notebook
Open the foi_complaints_eda.ipynb notebook to explore the analysis.

## Exploratory Data Analysis (EDA)
The EDA process involves various steps, including:

Data Cleaning: Handling missing values, correcting data entry errors, and standardizing entity names.
Descriptive Statistics: Summarizing key metrics and distributions.
Visualizations: Using charts and graphs to identify patterns and trends in the data.
Correlation Analysis: Investigating relationships between variables.
Logistic Regression: Modeling the likelihood of a complaint being justified based on various factors.
Key Findings
Certain entities have a higher frequency of complaints, and these complaints are often related to specific subjects.
The time taken to resolve complaints varies significantly across entities and subjects.
There is a correlation between the number of treatment days and the likelihood of a complaint being deemed justified.
Future Work
Deeper Analysis: Further exploration of the data to understand the underlying causes of delays in complaint resolution.
Predictive Modeling: Developing models to predict the likelihood of a complaint being justified based on initial conditions.
Dashboard Development: Creating an interactive dashboard for stakeholders to explore the data.
Contributing
Contributions to this project are welcome. Please feel free to submit a pull request or open an issue if you have suggestions for improvements.

## General key findings from your exploratory data analysis (EDA)
1. High Volume of "No Response" Complaints: The most common issue across all complainant types, particularly for individual citizens and non-profit organizations, is the lack of response from entities, which accounts for a significant portion of the complaints.
2. Significant Variability in Treatment Times: There is considerable variability in the number of treatment days across different entities, with healthcare-related entities exhibiting some of the longest average treatment times, indicating potential inefficiencies or complexities in handling complaints in this sector.
3. Justified Complaints Predominantly Linked to Longer Treatment Times: The logistic regression analysis revealed that the number of treatment days is a significant predictor of whether a complaint is justified, with longer treatment times associated with a higher likelihood of the complaint being justified.
4. High Success Rates for Certain Entities: Several entities, particularly in the healthcare and governmental sectors, have high success rates (100%) in justified complaints, suggesting that when complaints are made against these entities, they are often found to be valid.
5. Dominance of Individual Citizen Complaints: The majority of complaints come from individual citizens, highlighting the importance of addressing public concerns and improving response mechanisms to enhance citizen satisfaction and trust in the entities involved.

## Conclusion
The EDA reveals key areas where systemic issues are prevalent, particularly in the health sector, and highlights the importance of improving response times and transparency in handling public complaints. Entities with high volumes of justified complaints, especially those related to "No Response," should prioritize addressing these concerns to enhance public trust and service delivery.

These findings provide a foundation for targeted interventions aimed at improving the efficiency and effectiveness of complaint resolution processes, especially within entities that consistently receive high volumes of complaints.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
