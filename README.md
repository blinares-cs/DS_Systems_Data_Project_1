# DS_Systems_Data_Project_1

This project is a flexible data processing tool designed to handle data from multiple sources and formats. The utility allows users to ingest data from either a local CSV file or an external API (specifically the OpenFDA API), modify the structure of the data by removing unwanted columns, and save the processed data in the format of CSV, JSON, or a SQL database. 

### Features:
- Data Ingestion: The user can choose to load data from a CSV file or fetch data from an API. The CSV file is read locally, while the API call retrieves a dataset from OpenFDA.
- Column Modification: Users can interactively remove specific columns from the dataset by providing a comma-separated list of column names.
- Data Conversion: The processed data can be saved in one of three formats: CSV, JSON, or SQL database.
- Error Handling: The utility includes error handling, ensuring that users are informed if any errors occur, such as invalid column names or failed file/API loading.
- Summary of Data: The tool provides a summary of the dataset before and after modification, including the number of records and columns.

### How to Run:
1. Run the script, and you will be prompted to choose a data source: CSV (1) or API (2).
   If CSV is chosen, the tool will load data from the provided CSV file path.
   If API is selected, the tool will fetch data from the OpenFDA API.
   After loading the data, the tool will show you the records and columns of the data source.
2. The tool will ask you to input column names you wish to remove from the dataset.
   The tool will summarize the records and columns of the modified dataset.
3. The tool will then ask you to save it in either a CSV (1), JSON (2), or SQL database format (3).
