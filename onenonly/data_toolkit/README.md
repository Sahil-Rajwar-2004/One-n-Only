# Data Processing Toolkit (data-toolkit)
The Data Processing Toolkit (data-toolkit) is a Python library designed to streamline data processing tasks and facilitate the exploration and manipulation of datasets. Whether you're working with local files or remote datasets, this toolkit provides functions to fetch, analyze, and preprocess data efficiently. It is particularly useful for individuals engaged in data analysis, machine learning, and research.

# Installation
You can install the data-toolkit library using pip:

```bash
pip install onenonly
```

# Usage
Once you've installed the library, you can import it and use its functions to perform various data processing operations.

```python
import onenonly.data_toolkit as dt

# Fetch data from a remote source
file = "dataset_name"
data = dt.fetch_data(file)

# Fetch data from a local file dialog
data = dt.fetch_data_dir()

# Fetch a list of available remote datasets
dataset_list = dt.fetch_remote_dataset_lists()

# Get a list of data files in a directory
data_files = dt.get_data_files_list()

# Split data into training and testing sets
x_train, y_train, x_test, y_test = dt.split(x, y, test_size=0.2, seed=42)

# Convert a DataFrame to a numpy matrix
matrix_data = dt.df2matrix(dataframe)

# Drop rows or columns from a matrix or array
new_data = dt.drop(data, index, via="row")
new_data = dt.drop(data, index, via="column")

# Replace a specific value with NaN in a matrix or array
new_data = dt.dropExact(data, (row, col))

# Generate statistics summary for a DataFrame
statistics_summary = dt.describe(dataframe)

# Check if a matrix or array contains NaN values
has_nan = dt.isnan(data)
```
