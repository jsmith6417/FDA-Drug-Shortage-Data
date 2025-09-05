# FDA Drug Shortage Tracker for GLP-1 Drugs

This Jupyter Notebook retrieves real-time drug shortage data for GLP-1 drugs using the FDA Drug Shortages API. The program eliminates the need to manually download and clean CSV files by connecting directly to the API.

## Overview

- Retrieves current drug shortage data from the FDA Drug Shortages API  
- Focuses specifically on GLP-1 class medications  
- Automatically stores data in a local SQLite database  
- Compares new records with existing entries  
- Updates only rows where data has changed  

This selective update process ensures the database remains current while minimizing redundant processing and unnecessary writes.

## Visualizations
Explore the interactive Tableau dashboards here:  
[GLP-1 Drug Availability](https://public.tableau.com/views/GLP1DrugShortage/GLP-1DrugAvailibility?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Article at JCS Analytics
**Streamlined Drug Shortage Tracking with Python and SQLite**  
https://jcsanalytics.com/index.php/articles/streamlined-drug-shortage-tracking-with-python-and-sqlite
