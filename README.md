# Lending Club Data Analysis

This project analyzes Lending Club loan data from 2007 to 2018, including both accepted and rejected loan applications.

## Setup

### Prerequisites

- Python 3.8+
- Jupyter Notebook or JupyterLab
- Required Python packages (install with `pip install -r requirements.txt` if available, or manually install):
  - pandas
  - numpy
  - matplotlib

### Installing Dependencies

```bash
pip install pandas numpy matplotlib
```

## Data Acquisition

The large CSV data files are not included in this repository due to their size. You need to download them from Kaggle.

### Downloading the Data

1. **Create a Kaggle Account** (if you don't have one)
   - Go to [kaggle.com](https://www.kaggle.com) and sign up

2. **Download the Lending Club Dataset**
   - Visit the [Lending Club Loan Data](https://www.kaggle.com/datasets/wordsforthewise/lending-club) dataset page on Kaggle
   - Or search for "Lending Club" on Kaggle and select the dataset with data from 2007-2018

3. **Download Required Files**
   - **Accepted Loans**: Download `accepted_2007_to_2018Q4.csv`
   - **Rejected Loans**: Download `rejected_2007_to_2018Q4.csv`

4. **Place Files in Project Directory**
   - Extract the downloaded files
   - Place `accepted_2007_to_2018Q4.csv` in the `accepted_2007_to_2018q4.csv/` directory
   - Place `rejected_2007_to_2018Q4.csv` in the `rejected_2007_to_2018q4.csv/` directory

   Your directory structure should look like:
   ```
   Lending club/
   ├── accepted_2007_to_2018q4.csv/
   │   └── accepted_2007_to_2018Q4.csv
   ├── rejected_2007_to_2018q4.csv/
   │   └── rejected_2007_to_2018Q4.csv
   └── lending_club_analysis.ipynb
   ```

### Alternative: Using Kaggle API

If you have the Kaggle API set up:

```bash
# Install Kaggle API
pip install kaggle

# Download the dataset (replace with actual dataset path)
kaggle datasets download -d wordsforthewise/lending-club

# Extract the files
unzip lending-club.zip
```

## Project Structure

- `lending_club_analysis.ipynb` - Main Jupyter notebook for analysis
- `accepted_2007_to_2018q4.csv/` - Directory for accepted loan data (not in repo)
- `rejected_2007_to_2018q4.csv/` - Directory for rejected loan data (not in repo)
- `Lending Club Data Dictionary*.csv` - Data dictionaries (ignored in git)

## Usage

1. Ensure you have downloaded the data files from Kaggle (see Data Acquisition section)
2. Open `lending_club_analysis.ipynb` in Jupyter Notebook
3. Run the cells to perform your analysis

## Notes

- The large CSV files and personal notes are excluded from version control via `.gitignore`
- Data dictionary files are available locally but not tracked in git

