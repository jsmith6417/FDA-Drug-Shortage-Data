# FDA Drug Shortage Tracker for GLP-1 Drugs

This Jupyter Notebook retrieves real-time drug shortage data for GLP-1 drugs using the FDA Drug Shortages API. The program eliminates the need to manually download and clean CSV files by connecting directly to the API.

## Overview

- Retrieves current drug shortage data from the FDA Drug Shortages API  
- Focuses specifically on GLP-1 class medications  
- Automatically stores data in a local SQLite database  
- Compares new records with existing entries  
- Updates only rows where data has changed  

This selective update process ensures the database remains current while minimizing redundant processing and unnecessary writes.

## Requirements

The following Python packages are required:

- `pandas` – for working with tabular data  
- `requests` – for making API calls to the FDA endpoint  
- `sqlite3` – for managing the local SQLite database (included in Python standard library)  
- `ipython-sql` – for using SQL Magic (`%sql`) in Jupyter Notebook cells  

To install the required non-standard packages:
pip install pandas requests ipython-sql
