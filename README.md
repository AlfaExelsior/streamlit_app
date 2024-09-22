
# Simple Data Dashboard

This is a simple data dashboard created using Python and Streamlit. The app allows users to upload a CSV file, preview the data, filter it based on a selected column, and visualize it using a line chart.

## Features

- **Upload CSV File**: Upload a CSV file to the app for analysis.
- **Data Preview**: View the first few rows of the uploaded data.
- **Data Summary**: Get a quick statistical summary of the dataset.
- **Filter Data**: Filter the dataset by selecting a specific column and value.
- **Data Visualization**: Plot the filtered data with options to choose x and y-axis columns.

## Installation

To run this app locally, you need to have Python installed along with the required libraries.

1. Clone this repository or download the code.
2. Install the necessary dependencies by running:

```bash
pip install streamlit pandas matplotlib
```

## Running the App

Once the dependencies are installed, you can run the app with the following command:

```bash
streamlit run app.py
```

Here `app.py` is the name of the Python file containing the code.

## Usage

1. Run the Streamlit app using the above command.
2. Upload a CSV file using the "Choose a CSV file" uploader.
3. View the data preview and summary.
4. Filter the data by selecting a specific column and value.
5. Generate a plot by choosing the x and y columns and clicking the "Generate Plot" button.

## Example

Here’s how the app workflow looks:

1. **Upload a CSV file**: A CSV file containing any dataset.
2. **View Data**: The first few rows and a summary of the data are displayed.
3. **Filter Data**: Choose a column and a value to filter the dataset.
4. **Plot Data**: Visualize the filtered data using a line chart.

## Dependencies

- `streamlit`: A fast way to create custom web apps for data science.
- `pandas`: For data manipulation and analysis.
- `matplotlib`: For data visualization.

## License

This project is licensed under the MIT License.
