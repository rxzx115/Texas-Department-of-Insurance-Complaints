# Texas-Department-of-Insurance-Complaints

Objective: To understand how factors such as the company listed on the complaint, the channel filing the complaint, and the type of complaint impact the volume of complaints and the length of response times to enhance customer satisfaction


Guiding questions:
    - What are the current numbers of complaints and the average times to close the complaints? How have the volume of complaints and response times changed over time?
    - Which companies are associated with higher numbers of complaints and longer average times to close? What are specific complaint types that stand out to these issues for these companies?
    - How do the different filing channels impact the number of complaints and average time to close?
    - What seasonality trends are there within the higher volume of complaints or longer resolution times?
    - What are the distributions of complaints and resolution times?


Data collection: To retrieve data from Data.gov


Data cleaning:
    - Compared the unique list of complaints for data integrity
    - Reviewed outliers to avoid errors or unusual events
    - Investigated missing values for data quality and data usability


Data exploration:
    - Exploratory data analysis was performed in SQL to answer the guiding questions
    - Refer to the separate .sql file for further details


Data visualization
    - Data visualization was performed in Tableau
    - Refer to the separate Tableau data visualization on Tableau Public for further details


Insights and recommendations: 
    1) The complaints by top company data shows that State Farm had the highest number of complaints, followed by Allstate in multiple years.
        - Conduct a deeper dive with State Farm and Allstate to identify recurring issues and areas for process improvement.
    2) The complaints by type data indicates that property and casualty is the most frequent type of insurance complaint.
        - Analyze the common reasons to understand the underlying issues and develop targeted solutions or preventative measures.
    3) The response rates by top company data reveals substantial differences in the average days to respond to complaints among the top companies. Allstate has a notably higher average response time compared to State Farm and other listed companies.
        - Investigate Allstate's complaint handling process to identify bottlenecks and inefficiencies contributing to the longer response times. Implement strategies to streamline their process and improve responsiveness, potentially by allocating more resources or optimizing workflows.
