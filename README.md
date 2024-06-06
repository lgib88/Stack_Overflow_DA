# Stack Overflow Data Analysis

## Project Overview
This project aims to analyze trends in technology by leveraging the Stack Overflow API. By examining questions, answers, and user interactions on Stack Overflow, we can uncover insights into technology usage, popular programming languages, and emerging trends.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Data Sources](#data-sources)
- [Analysis Workflow](#analysis-workflow)
- [Contributing](#contributing)
- [License](#license)

## Installation
1. **Clone the repository:**
    ```bash
    git clone https://github.com/lgib88/Stack_Overflow_DA.git
    ```
2. **Navigate to the project directory:**
    ```bash
    cd Stack_Overflow_DA
    ```
3. **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. **Set up your Stack Overflow API key:**
   - Obtain an API key from the Stack Exchange API portal.
   - Store your API key in a `.env` file in the project root directory.
2. **Run the analysis scripts:**
   - Use the provided Python scripts in the `scripts` folder to fetch data from the Stack Overflow API and perform analysis.

## Project Structure
- `data/`: Directory to store the fetched Stack Overflow data.
- `notebooks/`: Jupyter notebooks for data exploration and analysis.
  - `Data_Exploration.ipynb`: Initial exploration of the Stack Overflow data.
  - `Trends_Analysis.ipynb`: Analysis of technology trends and insights.
- `scripts/`: Python scripts for data fetching and preprocessing.
  - `fetch_data.py`: Script to fetch data from the Stack Overflow API.
  - `preprocess_data.py`: Script to clean and preprocess the fetched data.
- `.gitignore`: Specifies files to ignore in the repository.
- `README.md`: Project documentation.
- `requirements.txt`: Python dependencies required for the project.

## Data Sources
The data for this project is sourced from the Stack Overflow API. The API provides access to various endpoints, including questions, answers, tags, and user data. Detailed information about the API can be found on the [Stack Exchange API documentation](https://api.stackexchange.com/docs).

## Analysis Workflow
1. **Data Collection:**
   - Use `fetch_data.py` to collect data from the Stack Overflow API based on specified criteria (e.g., date range, tags).

2. **Data Preprocessing:**
   - Clean and preprocess the collected data using `preprocess_data.py`.

3. **Exploratory Data Analysis (EDA):**
   - Use `Data_Exploration.ipynb` to perform initial data exploration and visualization.

4. **Trend Analysis:**
   - Analyze technology trends and generate insights using `Trends_Analysis.ipynb`.

## Contributing
Contributions are welcome! If you'd like to contribute, please fork the repository and create a pull request with your changes. Ensure your code adheres to the project's coding standards and includes relevant tests.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

For more information, visit the [GitHub repository](https://github.com/lgib88/Stack_Overflow_DA).
