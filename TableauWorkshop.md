# Tableau Workshop

## Introduction

- This workshop is designed to introduce you to Tableau, a business intelligence and data visualization tool

- While there are many data visualization tools and packages for scripting languages, Tableau is particularly useful for exploring data and doing simple modeling

  - Tableau does not have a scripting language but has an extremely easy-to-use GUI

## Important Links

**Mortgage Complaint Data from CFPB**: https://query.data.world/s/13ozpoyqtxqbm1dv0pd2iwt7q

**Free Tableau for Students**: https://www.tableau.com/academic/students#form

**Free Tableau for Instructors**: https://www.tableau.com/academic/teaching

**Tableau Public**: https://public.tableau.com/s/

## Data Connections

- First thing that shows up when you open Tableau

- Tableau can connect to many types of data sources including Excel Spreadsheets, CSV files, text files, and various databases

- Download [Mortgage Complaint Data](https://query.data.world/s/13ozpoyqtxqbm1dv0pd2iwt7q)

  - Save it to an accessible directory

- Click _Text File_
  - Select Mortgage Complaint Data

- Click _Automatically Update_

## Create Sheets

### Bar Graph

- Click _Go to Worksheet_

- Dimensions and Measures

- Drag **Issue** to Columns

- Drag **Number of Records** to Rows

- Drag **State** to the Color button in the Marks section

- This is a bar graph of number of issues by **Issue** and **State**

- Let's create a bar graph with the companies with most mortgage complaints

  - Create sheet

  - Drag **Company** to Columns

  - Drag **Number of Records** to Rows

  - Sort Company descending by Number of Records

  - Filter **Company** above 1,000 complaints

### Line Graph

- Create new sheet

- Add **Date Received** to Columns

- Add **Number of Records** to Rows

- Click _Show Me_

  - Click on the continuous line graph

- Click on the _Plus Sign_ on the **Date Received** field in Columns
  - This will aggregate the data in different periods of time

#### Useful Calculations

##### Analysis

- Click on _Analytics_

- Drag **Trend Line** and select **Linear**

##### Running Sum

- Click the arrow on the field **SUM(Number of Records)** in Columns

  - Go down to _Quick Table Calculation_ and select _Running Total_

- This is a running sum

  - Fields can be overlaid in Tableau; you can have a running sum on top of other lines

### Geographic Visualizations

- Tableau supports many levels of geographic visualizations

- You can incorporate custom shape maps, or better yet, custom coordinates

- I recommend using FIPS codes for counties as Tableau does not always recognize county names

- Create new sheet

- Drag **State** into _Marks_ section

- Drag **Number of Records** into the _Colors_ button in _Marks_ section

- This will visualize the number of records reported by state

  - You can change colors and scale as you see fit

- Drag **Issue** into _Filters_ section

  - Select **Loan modification,collection,foreclosure**

- This limits the data visualized

- You can change colors and scales by clicking _Edit Colors…_ in the legend

  - For this data you might want to reverse the scale

### Sharing

- Click _Worksheet_ and select _Export_

- Any option will export the sheet as an image

- Tableau Public

## Dashboards

- Click _New Dashboard_

- Drag your sheets onto the dashboard

- Dashboards can be shared as images or published to Tableau Public

## Final notes

- Tableau is a powerful visualization tool

  - Very customizable

- Visualizations can be interactive and can be shared in many ways

- Tableau does have limitations
  - No scripting language

  - Closed source







