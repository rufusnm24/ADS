# Temporal Analysis of Mass Shootings in USA

# Introduction

Welcome to the GitHub repository for the research project "Temporal Analysis of Mass Shootings in the United States." This project is spearheaded by researchers Venkata Ajay Kumar Vutty, Rufus Nemalikanti, and our professor, Dr.Nidhi Rastogi, from the Rochester Institute of Technology, Rochester, NY, USA. Our aim is to develop a comprehensive and predictive model that analyzes the temporal trends and sociopolitical dynamics of mass shootings in the United States.

This repository contains all the datasets and resources used in our study. The project leverages a combination of traditional time-series analyses and state-of-the-art machine learning techniques to forecast the frequency and underlying drivers of these tragic events. Our goal is to inform public health strategies and policymaking, aiming at the prevention and reduction of future occurrences.

## Data Sources for Temporal Analysis of Mass Shootings in the United States

In our research project "Temporal Analysis of Mass Shootings in the United States," we have meticulously collected and curated data from various reputable sources. This data forms the backbone of our analysis, enabling us to delve deep into the historical patterns, underlying trends, and sociopolitical dynamics of mass shootings in the U.S. Below is a detailed overview of each primary data source utilized in our study.

### 1. **ALERRT Active Attack Data**
- **Description**: The Advanced Law Enforcement Rapid Response Training (ALERRT) provides detailed data on active attack incidents, including mass shootings, as well as vehicle and knife attacks.
- **Content**: This dataset includes essential details about the events, such as the profiles of perpetrators, types of weaponry used, and resolution strategies employed.
- **Use in Study**: This data helps in understanding the dynamics of such events, particularly focusing on the typical profiles of perpetrators and the nature of the attacks.

### 2. **Firearms Mortalities by State - CDC**
- **Description**: Sourced from the Centers for Disease Control and Prevention, this dataset offers state-level data on firearm-related mortalities.
- **Content**: It includes statistics on gun-related deaths across different states, providing a crucial context for understanding regional variations and trends in firearm mortalities.
- **Use in Study**: We use this data for a comparative analysis of firearm-related deaths across states, helping to identify patterns and correlations with mass shooting incidents.

### 3. **Gun Violence Archive (GVA)**
- **Description**: The Gun Violence Archive is a comprehensive database cataloging various gun violence incidents in the U.S.
- **Content**: It provides detailed recording and categorization of incidents, including mass shootings, with data on the date, location, number of victims, and other relevant information.
- **Use in Study**: This resource supplements our analysis with both current and historical data on gun violence, enabling a thorough examination of mass shooting events.

### 4. **K-12 School Shooting Database**
- **Description**: Compiled by the Naval Postgraduate School’s Center for Homeland Defense and Security, this database focuses specifically on school shootings.
- **Content**: It includes incidents where a firearm is brandished, fired, or hits school property, offering a focused view on this critical aspect of gun violence.
- **Use in Study**: This database allows us to analyze the specific context of school shootings, understanding their patterns, frequency, and impact within educational settings.

### 5. **Mother Jones US Mass Shootings Database**
- **Description**: Mother Jones provides a database that offers historical context for mass shootings in the U.S. from 1982 to the present.
- **Content**: It includes detailed information about each shooting, such as the date, location, shooter's profile, weapons used, and number of casualties.
- **Use in Study**: We utilize this database to understand the evolution and patterns of mass shooting incidents over an extended period, aiding in longitudinal analyses.

### 6. **Stanford University Library’s Mass Shootings in America (MSA)**
- **Description**: Although no longer maintained, the MSA database provides historical data on mass shootings in America.
- **Content**: Sourced from online media, it offers insights into past mass shooting events.
- **Use in Study**: This data is used to gain historical insights and supplement our analysis with information from past years, helping to construct a comprehensive picture of the evolution of mass shootings in the U.S.

### 7. **The Violence Project’s Mass Shooter Database**
- **Description**: This database contains extensive details about public mass shootings in the U.S. and their perpetrators.
- **Content**: It includes in-depth data about shootings, personal histories of perpetrators, and the types of weapons used.
- **Use in Study**: Critical for understanding the personal and psychological profiles of shooters, this database aids in analyzing the human element involved in mass shootings.

### 8. **Washington Post Analysis of Mass Shootings in America**
- **Description**: The Washington Post provides a relational database that allows refined searches based on shooting details.
- **Content**: It includes specific, detailed information on shootings, enhancing our ability to conduct detailed analyses of individual events.
- **Use in Study**: This database is used for obtaining specific information on shootings, enhancing our ability to conduct detailed analyses of individual events.

## Preliminary Analysis of Datasets

### Category: Dataset Integration and Selection

Through an extensive review and preliminary analysis of the available datasets, our team has gained a comprehensive understanding of how to best integrate these diverse data sources for our study on mass shootings in the United States.

#### Selection of Baseline Dataset

After careful consideration, we have concluded that the "K-12 School Shooting Database" will serve as our baseline dataset. The decision to prioritize this dataset is based on several key factors:

- **Comprehensive Coverage**: This database offers a thorough record of school shooting incidents, dating back to 1970, providing a long-term view of this specific aspect of gun violence.
- **Real-Time Data**: The up-to-date nature of this dataset ensures that our analysis includes the most recent and relevant incidents, which is crucial for understanding current trends and patterns.
- **Extensive Data**: The "K-12 School Shooting Database" is notably extensive, encompassing a wide range of incidents, which makes it an invaluable resource for our study.

#### Integration Approach

In integrating the "K-12 School Shooting Database" with other datasets, our approach will be meticulous and structured:

- **Ensuring No Duplicates**: We will implement stringent checks to ensure that there are no duplicate records across datasets. This is vital for maintaining the integrity and accuracy of our analysis.
- **Comprehensive Coverage**: By integrating other datasets with our baseline, we aim to cover all aspects and incidents of mass shootings, not just those occurring in schools. This broadens the scope of our study and allows for a more holistic understanding of the issue.
- **Data Consistency**: We will ensure consistency in data formats and definitions across all datasets to facilitate seamless integration and analysis.

Through this approach, we aim to build a robust, comprehensive dataset that captures the multifaceted nature of mass shootings in the United States. Our goal is to leverage this integrated data to develop a predictive model that can offer insights into the frequency, trends, and drivers of these tragic events, with the ultimate aim of informing effective intervention strategies.

