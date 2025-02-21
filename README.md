# Data Sweeper: Streamlit Web App for Data Cleaning and Conversion

**Data Sweeper** is a web app built with **Streamlit** and **Pandas** that allows users to upload CSV or Excel files, clean the data by removing duplicates and filling missing values, visualize the data, and convert the cleaned data into CSV or Excel formats.

## Features

- **Upload Files:** Supports CSV and Excel file uploads.
- **Data Cleaning:** Remove duplicates and fill missing values.
- **Column Selection:** Choose specific columns to keep or drop.
- **Data Visualization:** Generate bar charts for numerical data.
- **File Conversion:** Convert cleaned data back to CSV or Excel format.
- **Download Cleaned Data:** Easily download the cleaned file in the desired format.

## Requirements

To run this app locally, you need to have the following dependencies installed:

- **Python 3.x**
- **Streamlit**
- **Pandas**

You can install the necessary Python packages using the following:

```cmd
pip install streamlit pandas

How to Run the App
Clone this repository:
cmd
Copy
git clone https://github.com/BBismaarshad/file-cleaner-streamlit.git
Navigate to the project directory:
cd app.py
Run the Streamlit app:
streamlit run app.py
Open your browser and go to http://localhost:8501 to start using the app.
Usage
Upload Your Files: Click on the upload button to select CSV or Excel files from your local storage.
Clean Your Data: Use the options to remove duplicates and fill missing values in your dataset.
Visualize Your Data: View the bar charts generated for the numerical columns of your data.
Choose Columns: Select specific columns you want to keep or remove from the data.
Convert & Download: After cleaning, convert your file back to CSV or Excel format and download it.
Contributing
Feel free to fork this repository, contribute improvements, or open issues for bugs and feature requests.
