# Project: Accenture North America Data Analytics and Visualization
Certification: 
## Client : [Social Buzz](https://cdn.theforage.com/vinternships/companyassets/T6kdcdKSTfg2aotxT/MsAqi7SNLKw3C6LAr/1664296994014/Data_Analytics%20Client%20Brief.pdf)
### Introduction to Project:
The project involves a data analyst who acts as a link between business and data. **Social Buzz** is the client, and Accenture's Managing Director, Mae Mulligan, leads the project. She has gathered a diverse team of Accenture experts to deliver the project, and tomorrow morning, she has scheduled a project kick-off call with the internal Accenture project team.

### Task 1: Project Understanding
- Accenture's task is to solve the client's problem of not having enough resources to handle their massive scale.
- To achieve this, Accenture needs to perform
  - An audit of the big data practice
  - Provide recommendations for IPO
  - Analyze popular content
**Task for Data analyst**:
- Analysis of sample data sets with visualizations to understand the popularity of different content categories.
- The client wanted to see “An analysis of their content categories showing the top 5 categories with the largest popularity”.
### Task 2: Data Cleaning & Data Modeling
In order to answer this business question, which is to find out the top 5 categories with the largest popularity, you don't necessarily need to use all the available datasets. Therefore, the first step is to use this [data model](https://cdn.theforage.com/vinternships/companyassets/T6kdcdKSTfg2aotxT/MsAqi7SNLKw3C6LAr/1664297834541/Data%20model.pdf) to identify the necessary datasets for analysis. 

- After conducting the analysis, we found the following datasets to be required to complete the analysis: 
  - Reaction Score (which quantify popularity)
  - Content ID
  - Reaction Type
  - Content Type
  - Category

- Clean the data by:
  - Removing rows that have values which are missing(by using Filters)
  - Changing the data type of some values within a column
  - Removing columns which are not relevant to this task(deleting the User ID and URL columns).
- **Data modeling**: Create a final data set by merging these three data sets.
  - First join the relevant columns from Content data set, and then the Reaction Types data set with Reaction data set(By using VLookUp formula)
  - Add up the total scores for each category by using “Sum If” formula.

### Task 3: Data Visualization and Storytelling
- We create Graph and Pie chart
- Prepare good presentation
### Task 4: Present to the client
- Let's put together a well-structured and informative presentation that effectively communicates our ideas to the client.
