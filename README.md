# VizCraft: Interactive Data Navigator
---

Welcome to VizCraft, an all-in-one web application that empowers you to upload, explore, analyze, and visualize datasets in CSV and Excel formats. This tool is designed for data analysts, scientists, and anyone interested in gaining quick and insightful analysis from their data.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [File Upload](#file-upload)
- [Dataset Overview](#dataset-overview)
- [Columns Values to Count](#columns-values-to-count)
- [Groupby: Simplify Your Data Analysis](#groupby-simplify-your-data-analysis)
- [Contributing](#contributing)
- [License](#license)

## Features
- **Upload and Analyze Data:** Easily upload CSV or Excel files and explore your data within seconds.
- **Dataset Overview:** Get a comprehensive summary, view column names, data types, and inspect the top and bottom rows of your dataset.
- **Column Value Counting:** Select specific columns to count and visualize the frequency of values using various chart types.
- **Groupby Analysis:** Group your data by one or more columns and perform operations like sum, max, min, mean, median, and count. Visualize the results with different graph types.

## Installation
To get started with VizCraft, you need to have Python installed along with the required libraries. You can install the dependencies using the following command:

```bash
pip install pandas plotly streamlit
```

## Usage
To run the VizCraft application, use the following command in your terminal:

```bash
streamlit run app.py
```

This will open the application in your web browser.

## File Upload
VizCraft allows you to upload your datasets directly through the sidebar. Supported file formats are CSV and Excel.

- **Example CSV Input:** If you do not have a dataset ready, you can use the provided example dataset by clicking the button to load it.

## Dataset Overview
Once a dataset is uploaded or the example dataset is loaded, you can explore the following sections:

- **Summary:** View the number of rows and columns and a statistical summary of your dataset.
- **Columns:** Display the names of all columns in your dataset.
- **Data Types:** Inspect the data types of each column.
- **Head and Tail:** View the top and bottom rows of your dataset, with adjustable row numbers.

## Columns Values to Count
In this section, you can:

- **Select a Column:** Choose a column from your dataset to count the frequency of its values.
- **Visualize Data:** Generate bar, line, and pie charts to visualize the frequency distribution.

## Groupby: Simplify Your Data Analysis
This feature allows you to:

- **Group Data:** Group your dataset by one or more columns and perform operations like sum, max, min, mean, median, and count.
- **Data Visualization:** Choose from various graph types, including line, bar, scatter, pie, and sunburst charts, to visualize the results of your groupby analysis.

## Example Screenshots
<img width="1438" alt="image" src="https://github.com/user-attachments/assets/92cc4c04-d5ce-4282-a7ed-4847c153850c">
<img width="1189" alt="image" src="https://github.com/user-attachments/assets/1a308e69-f681-44ec-a16a-3d8c08ba5fbc">
<img width="1440" alt="image" src="https://github.com/user-attachments/assets/37ae162d-73ba-4d54-ad7b-7855e6175b78">
<img width="1410" alt="image" src="https://github.com/user-attachments/assets/9dd811b0-0e22-431b-8e4c-1a2984a81c2c">


## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue if you have any suggestions or improvements.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
