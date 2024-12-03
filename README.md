
# Data Analysis and Sentiment Labeling

This project involves analyzing a dataset (e.g., Yelp reviews) and performing sentiment labeling based on star ratings.

## Features
- Load a JSON dataset into a Pandas DataFrame.
- Perform basic data analysis and preprocessing.
- Categorize sentiment as positive or negative based on star ratings.

## Prerequisites

Ensure you have the following installed on your system:
- Python 3.7+
- Jupyter Notebook
- Required Python libraries: `pandas`, `os`, `json`

Install the required Python packages using pip:

```bash
pip install pandas jupyter
```

## Setup Instructions

1. **Download or Prepare the Dataset**:
   - Place the dataset file (e.g., `yelp_academic_dataset_review.json`) in the same directory as the notebook or update the file path in the code.

2. **Optional: Kaggle Integration**:
   - If using the Kaggle API, set up your `kaggle.json` credentials file.
   - Install the Kaggle Python package:

     ```bash
     pip install kaggle
     ```

   - Use the Kaggle API to download the required dataset.

## Running the Notebook

1. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

2. Open the notebook file (`notebookc83c4196e8.ipynb`) from the Jupyter interface.

3. Update the `file_path` variable to point to your dataset.

4. Execute each cell sequentially to:
   - Load the data into a DataFrame.
   - Perform sentiment labeling.
   - Analyze and visualize the data as needed.

## Output

The notebook provides:
- Basic dataset structure and previews.
- Sentiment labels for reviews based on star ratings.

## Notes

- Ensure the dataset is in JSON format and matches the expected schema for smooth execution.
- For large datasets, consider optimizing memory usage (e.g., by loading data in chunks).

## NOTE
To access the dataset, please use the following link:  https://www.yelp.com/dataset