### Problem statement:

  A businessman is running a superstore and needs to do descriptive analysis to find out KPIs growth.
 To achieve that, needs to do drill down analysis from region to state to study sales and profit.

### Objective:

To build a dashboard that represents KPIs from region to state with respective trend line visualization.

### Performed Tasks:
 - Use excel file **sample_-_superstore.xls**
    - Connect to saved excel file from your local machine.
 - Establish relationship between all three tables(**Orders,People,Returns**) on tableau.

#### Sheet 1 - Region map

 - Create a geographical map from Region
    - Create calculated fields to find current,previous year sales and profit.
    - Create positive and negative sales/profit change indicators.
    - Select required information to show measure values on tooltip.
 - Establish drill down feature region to state.
    - Create a Country,Region and State hierarchy
    - Create a region selected set
    - Create a calculated field with the region selected set.
    - Select worksheet-> Actions and select set value to perform action.

#### Sheet 2 - State map

 - Duplicate Region map.
 - Drag region selected set to filter pane.

#### Sheet 3 - Current year sales KPI

 - Drag current year sales and previous year sales measures on column shelf.
 - For current year sales change mark type to "Bar" and for previous year sales change mark type to "Gantt bar".
 - Make this chart as dual axis then synchronize axis and unmark show header.
 - Adjust tooltip deatils.
 - Incorporate information details on chart heading like current year sale, amount and growrth indicator.

#### Sheet 4 - Current year profit KPI

 - Follow the same steps as Sales KPI with profit details.

#### Sheet 5 - Current year avg shipping days KPI

 - Create a calculated field avg shipping days.
 - Create a calculated field for current year avg shipping days and previous year avg shipping days.
 - Follow the same steps as current year sales KPI.

#### Sheet 6 - Sales trend lines

 - Create a line chart for sales against current year monthwise.
 - Adjust tooltip for information display.

#### Sheet 7 - Profit trend lines

 - Follow same steps as sales trend lines with profit details.

#### Sheet 8 - Avg shipping trend lines

 - Follow same steps as sales trend lines with avg. shipping details.

### Dashboard

 - Set automatic size canvas for dashboard creation.
 - Drag and adjust all sheets on the blank canvas.
 - Currently, dashboard is not interactive.
 - To make dashboard interactive go to Dashboard-> Actions and select set variable.
 - Select state map sheet as filter source and except region map all sheets will be target sheet.
 - Select blank object as a header of dashboard and fill with title.
 
 
 ### Link for dashboard:
 [Business dashboard with descriptive analysis](https://public.tableau.com/app/profile/anubha.ranjan/viz/BusinessKPIDashboardthroughdescriptiveanalysis/Dashboard1?publish=yes).






