# Solving an SDG Problem with Data (Choose Your SDG)

## Overview
Select a Sustainable Development Goal (SDG) that resonates with you and develop a data-driven solution to address a specific problem within that SDG. Design a database, perform data analysis, and use Microsoft Excel as the user interface.

## Objectives
- Choose an SDG and identify a specific problem to address.
- Design and implement a relational database relevant to your chosen problem.
- Write SQL queries to retrieve and analyze data.
- Use Microsoft Excel for data visualization and analysis.

## Requirements

### Part 1: SDG Selection and Problem Definition
- **SDG Selection:** Choose an SDG (e.g., SDG 3: Good Health, SDG 7: Affordable and Clean Energy).
- **Problem Definition:** Define a specific problem within your chosen SDG that can be addressed using data.

### Part 2: Database Design
- **ERD:** Design an ERD for your project, including entities relevant to your SDG problem.
- **Schema:** Write SQL statements to create the database schema based on your ERD.
- **Sample Data:** Populate the database with relevant sample data.

### Part 3: SQL Programming
- **Data Retrieval:** Write SQL queries to retrieve relevant data based on your problem definition.
- **Data Analysis:** Write SQL queries to analyze data and generate insights related to your SDG problem.

### Part 4: Data Analysis Using Excel
- **Import Data:** Import data from your database into Excel.
- **Analysis:** Analyze the data using pivot tables, charts, and other Excel tools.
- **Dashboard:** Create an interactive Excel dashboard to visualize key insights.

### Part 5: Integration and Testing
- **Integration:** Document the process of importing data into Excel and ensuring consistency.
- **Testing:** Test the integration and functionality of your Excel dashboard.

### Part 6: Presentation
- **Pitch Deck:** Develop a 10-slide PowerPoint presentation as taught in the entrepreneurship module covering:
  - Project overview and SDG alignment.
  - Problem definition and significance.
  - Database design and schema.
  - Data analysis insights.
  - Excel dashboard demonstration.
- **Delivery:** Present your pitch deck, demonstrating how your project addresses the SDG problem.

## Deliverables
- SDG problem definition document
- ERD
- SQL scripts
- Excel workbook with data analysis and dashboard
- Integration documentation
- Pitch deck presentation



BIAKOLO SUBMISSION


Project Proposal: SDG 3 - Good Health and Well-being
Problem Definition:
Maternal Mortality Rate: Despite advancements in healthcare, maternal mortality remains a significant challenge in many regions. This project aims to analyze factors contributing to maternal mortality and identify potential interventions through data-driven insights.

Database Design:
Entities:

Patient
Pregnancy
Delivery
Infant
HealthcareFacility
Staff
Relationships:

A Patient can have multiple Pregnancies.
A Pregnancy results in a Delivery.
A Delivery results in an Infant.
A Delivery occurs at a HealthcareFacility and is attended by Staff.
SQL Schema:

SQL
CREATE TABLE Patient (
    patient_id INT PRIMARY KEY,
    name VARCHAR(100),
    age INT,
    address VARCHAR(255)
);

CREATE TABLE Pregnancy (
    pregnancy_id INT PRIMARY KEY,
    patient_id INT,
    start_date DATE,
    end_date DATE,
    FOREIGN KEY (patient_id) REFERENCES Patient(patient_id)
);

-- Similar tables for Delivery, Infant, HealthcareFacility, and Staff
 

Data Analysis:
Identify factors correlated with maternal mortality (e.g., age, location, education, healthcare access).
Analyze trends in maternal mortality rates over time.
Determine the impact of different healthcare interventions on maternal mortality.
Excel Dashboard:
Overview of maternal mortality rate by region.
Distribution of maternal age, education level, and other relevant factors.
Trends in maternal mortality over time.
Comparison of maternal mortality rates across healthcare facilities.
Potential Challenges and Solutions:
Data Quality: Ensure data accuracy and completeness through data cleaning and validation.
Privacy: Protect patient data through anonymization and encryption.
Data Availability: Access to comprehensive and reliable data might be limited. Explore alternative data sources or partnerships.
By effectively addressing these challenges, this project can provide valuable insights into reducing maternal mortality and contribute to achieving SDG 3.
