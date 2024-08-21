# VizCraft: Interactive Data Navigator

---

**VizCraft** is a powerful and user-friendly web application built with Streamlit that allows you to upload, explore, analyze, and visualize datasets in CSV and Excel formats. This tool is ideal for data analysts, scientists, and anyone interested in gaining insights from their data quickly and easily.

## Features

- **Interactive Data Upload**: Upload your datasets in CSV or Excel format and instantly visualize the data.
- **Comprehensive Data Overview**: Explore basic information about your dataset, including summary statistics, data types, column names, and more.
- **Flexible Data Analysis**:
  - View top and bottom rows of your data.
  - Count values in selected columns with dynamic visualizations (bar, line, and pie charts).
  - Group data by one or more columns and perform operations like sum, max, min, mean, median, and count.
- **Customizable Visualizations**: Generate various types of charts, including line, bar, scatter, pie, and sunburst charts, to better understand your data.

## Installation

To run VizCraft locally, follow these steps:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/vizcraft.git
   cd vizcraft
   ```

2. **Create a virtual environment (optional but recommended)**:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required packages**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure the theme** (Optional):
   - Create a `.streamlit` directory in the root of your project:
     ```bash
     mkdir .streamlit
     ```
   - Create a `config.toml` file inside this directory and add the following content:
     ```toml
     [theme]
     base="light"
     font="serif"
     ```

5. **Run the application**:
   ```bash
   streamlit run myapp.py
   ```

6. **Access the app**:
   - Open your web browser and go to `http://localhost:8501/` to use VizCraft.

## Usage

1. **Upload a Dataset**: Use the file uploader to upload a CSV or Excel file.
2. **Explore Data**: View a summary of your data, including the number of rows and columns, statistical summaries, top and bottom rows, data types, and column names.
3. **Value Counts**: Select a column to count the values and visualize them using various chart types.
4. **Group By Analysis**: Group your data by one or more columns and apply aggregate functions like sum, mean, or count. Visualize the results with customizable charts.

## Example Screenshots

<img width="1440" alt="image" src="https://github.com/user-attachments/assets/50ff4d7b-0e63-46ef-b139-7c829704f5df">
<img width="1440" alt="image" src="https://github.com/user-attachments/assets/1de0d51d-d3fa-4242-ace3-ff86588fcbd7">


## Credits

This project was made possible with the help and guidance from the [Console Flare]([https://www.youtube.com/c/ConsoleFlare](https://www.youtube.com/@consoleflare)) YouTube channel. I learned the necessary skills and concepts to build this application by following their tutorials.

## Contributing

Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or suggestions, please contact [Sai Srivatsa Thangallapelly](mailto:saisrivatsat@example.com).

---

This README file now includes a "Credits" section that acknowledges the learning resources from the Console Flare YouTube channel. Feel free to customize it further as needed.
