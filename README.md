# Project Overview

To analyze the New Yor Citi Bike program data in order to obtain valuable insights, and answer specific questions about the program. Present the results of the analysis to a non technical audience

# Questions to answer

- [] How many trips have been recorded total during the chosen period?
- [] By what percentage has total ridership grown?
- [] How has the proportion of short-term customers and annual subscribers changed?
- [] What are the peak hours in which bikes are used during summer months?
- [] What are the peak hours in which bikes are used during winter months?
- [] Today, what are the top 10 stations in the city for starting a journey? (Based on data, why do you hypothesize these are the top locations?)
- [] Today, what are the top 10 stations in the city for ending a journey? (Based on data, why?)
- [] Today, what are the bottom 10 stations in the city for starting a journey? (Based on data, why?)
- [] Today, what are the bottom 10 stations in the city for ending a journey (Based on data, why?)
- [] Today, what is the gender breakdown of active participants (Male v. Female)?
- [] How effective has gender outreach been in increasing female ridership over the timespan?
- [] How does the average trip duration change by age?
- [] What is the average distance in miles that a bike is ridden?
- [] Which bikes (by ID) are most likely due for repair or inspection in the timespan?
- [] How variable is the utilization by bike ID?

# Project approach

## Data exploration

- I began by exploring the data available (public) in [Citi Bike System Data](https://www.citibikenyc.com/system-data)
- After an initial exploration, and the questions that need to be answer, the project will probably need 3 main datasets
    1. Historical over a chosen timespan (probably will choose last 12 months)
    2. Daily data
    3. Grouped dataset by bike ID (rather than by trip)
- The csv file format is not consistent, will change the column names from the csv itself to simplify the merging process in jupyter
    - I will use the most recent file as template, for scalability purposes (new data should not need to be reformatted)