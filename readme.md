### Data Organization Tool

[![mail](https://cdn.discordapp.com/attachments/918110120494387200/1222496959496060928/send_email.png?ex=66166e04&is=6603f904&hm=c2a5339c19ed448923bc33f074ba6b78d6c732b77528de0276b5ec5ab89273e4&)](mailto:vaibhav.pr21@iiits.in)

This Python script is designed to organize and process data stored in CSV files structured in a specific folder hierarchy. It provides functions for data extraction, visualization, and organization into a standardized folder-file structure.

#### Dependencies
- NumPy
- pandas
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook (or similar environment)

#### Usage

1. **Data Extraction Function (`data_extraction`)**: This function reads CSV files, performs data cleaning, and saves the modified dataframe back to the CSV file. It is designed to handle CSV files containing time series data with specific column names.

2. **Data Visualization Function (`data`)**: This function visualizes the time series data by plotting it as a line chart and displaying its distribution using a histogram.

3. **Main Execution**: The script utilizes the `os` module to iterate through a specified folder (`Sub 0` in this example), read CSV files, extract data, and organize it into a folder structure based on predefined rules. The data is grouped into subjects, weapons, modes, mice, and trials, and saved as CSV files in a structured directory hierarchy.

#### Folder Structure
The data is organized into the following folder hierarchy:
- `data` (top-level folder)
  - `sub0`, `sub1`, ... (subject folders)
    - `Vandal`, `Guardian` (weapon folders)
      - `Hard`, `Medium` (mode folders)
        - `Mouse1`, `Mouse2`, `Mouse3`, `Mouse4` (mouse folders)
          - `Trial1.csv`, `Trial2.csv`, ... (trial CSV files)

#### How to Use
1. Ensure all dependencies are installed.
2. Modify the `folder_path` variable to specify the folder containing the CSV files.
3. Run the script in a Python environment (e.g., Jupyter Notebook) to execute the data extraction, visualization, and organization processes.

#### Note
- Make sure to replace the placeholder `folder_path` with the actual path to the folder containing the CSV files.
- The script assumes a specific naming convention and folder structure for the input CSV files. Adjust the code as needed to match your data organization requirements.

For any questions or issues, please contact [vaibhav.pr21@iiits.in](mailto:vaibhav.pr21@iiits.in).