# AdventureWorks Report
 

## Problem Statement

This dashboard helps the Top level management of AdventureWorks Company understand their customers and products better. It helps the company to know if their customers are satisfied with their products. Through different products, they get to know their improvement area, & thus they can improve their products by identifying these area. It also lets them know the average Sales, star products, star locations around the globe, orders delivered, orders returned etc.



### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present.
- Step 5 : For calculating sum of revenue, sum of profits, i wrote DAX. 
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : Since the data contains various products, thus in order to represent product category, a new visual was added using the three ellipses in the visualizations pane in report view. 
- Step 8 : Visual filters (Slicers) were added for four fields named "product", product category,price, profits..
- Step 9 : Two card visuals were added to the canvas, one representing average departure delay in minutes & other representing average arrival delay in minutes.
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
           
           Although, by default, while calculating average, blank values are ignored.
