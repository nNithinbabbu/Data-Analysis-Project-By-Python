# Data Analysis Project by Python

## Project Overview
This project performs data analysis on website traffic and user engagement data using Python. The analysis explores users, sessions, engagement rates, and traffic patterns across different channel groups and hours.

## Dataset
The project uses the dataset `data-export (1).csv`.

The dataset contains 3,182 rows and the following columns:

- Channel group
- Date and hour
- Users
- Sessions
- Engaged sessions
- Average engagement time per session
- Engaged sessions per user
- Events per session
- Engagement rate
- Event count

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Analysis and Visualization

The project includes the following analyses:

### 1. Data Cleaning and Preprocessing
- Loading the CSV dataset using Pandas
- Renaming dataset columns
- Converting date-hour values into datetime format
- Converting numerical columns into appropriate data types
- Extracting the hour from date-hour values
- Checking missing values and descriptive statistics

### 2. Sessions and Users Over Time
Visualizes the total number of sessions and users over time.

### 3. Total Users by Channel
Analyzes the total number of users across different channel groups using a bar chart.

### 4. Engagement Rate Distribution by Channel
Uses a box plot to examine the distribution of engagement rates across channel groups.

### 5. Engaged vs. Non-Engaged Sessions
Compares engaged sessions and non-engaged sessions across channel groups.

### 6. Traffic by Hour and Channel
Uses a heatmap to visualize session traffic by hour and channel group.

### 7. Engagement Rate vs. Sessions Over Time
Visualizes engagement rate and sessions over time.

## Project Structure

```text
Data-Analysis-Project-By-Python/
│
├── data analysis.ipynb
├── data-export (1).csv
└── README.md
```

## Installation and Usage

### 1. Clone the Repository

```bash
git clone https://github.com/nNithinbabbu/Data-Analysis-Project-By-Python.git
```

### 2. Navigate to the Project Folder

```bash
cd Data-Analysis-Project-By-Python
```

### 3. Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 4. Open the Jupyter Notebook

```bash
jupyter notebook
```

Open `data analysis.ipynb` and run the notebook cells.

**Note:** Keep `data-export (1).csv` in the project folder because the notebook loads the dataset using this filename.

## Author

**Nithin Potta**

GitHub: [nNithinbabbu](https://github.com/nNithinbabbu)
