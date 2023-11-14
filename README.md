# REDCap Data Export Tool
Description
This Python script automates the process of exporting data from REDCap (Research Electronic Data Capture) in CSV format, converting it to an Excel (XLSX) file, and saving it to a user-defined location, such as a local OneDrive folder. It's designed to facilitate easy and efficient data retrieval and conversion for users who regularly work with REDCap datasets.

## Features:
- Data Export from REDCap: Automatically downloads data from a specified REDCap form or project.
- CSV to Excel Conversion: Converts the downloaded CSV file to an Excel format.
- Custom Save Location: Saves the files directly to a designated folder, such as OneDrive.

## Getting Started
### Prerequisites
- Python 3.x
- Required Python packages: requests, pandas, openpyxl

## Installation
- Clone the repository: git clone https://github.com/ArminH93/redcap_export
- Install the required packages: pip install requests pandas openpyxl

## Usage
Update the api_key, api_url, and form_name variables in the script with your REDCap API key, REDCap API URL, and the name of the form you wish to download.

To run the script, execute: python redcap_export.py
The script will download the data from REDCap, convert it to an Excel file, and save both CSV and Excel files to the specified location.

## Configuration
- Download Location: Modify the get_downloads_folder function to specify a different download location.
- File Naming: The script uses static file names for saving. Modify the filename variables to change this behavior (e.g., to append a timestamp).

## Contributing
Contributions to the project are welcome. Please follow the standard procedure for contributing to GitHub projects:
- Fork the repository.
- Create a new branch (git checkout -b feature-branch).
- Make your changes and commit them (git commit -am 'Add a new feature').
- Push to the branch (git push origin feature-branch).
- Create a new Pull Request.

Contact
For any queries or contributions, please contact ar.halilovic@gmail.com
