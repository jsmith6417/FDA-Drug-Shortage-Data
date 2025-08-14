# FDA Drug Shortage Tracker for GLP-1 Drugs

This Jupyter Notebook retrieves real-time drug shortage data for GLP-1 drugs using the FDA Drug Shortages API. The program eliminates the need to manually download and clean CSV files by connecting directly to the API.

## Overview

- Retrieves current drug shortage data from the FDA Drug Shortages API  
- Focuses specifically on GLP-1 class medications  
- Automatically stores data in a local SQLite database  
- Compares new records with existing entries  
- Updates only rows where data has changed  

This selective update process ensures the database remains current while minimizing redundant processing and unnecessary writes.
