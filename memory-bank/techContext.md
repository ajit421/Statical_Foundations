# Tech Context

## Technologies Used
- **Python:** The primary programming language used for all scripting and data analysis.
- **Jupyter Notebook:** The environment for creating and sharing documents that contain live code, equations, visualizations, and narrative text.
- **Pandas:** A powerful data analysis and manipulation library. Used for reading, cleaning, and transforming data.
- **NumPy:** A fundamental package for scientific computing with Python. Used for numerical operations.
- **Matplotlib:** A comprehensive library for creating static, animated, and interactive visualizations in Python.
- **Seaborn:** A Python data visualization library based on Matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.

## Development Setup
To run this project, a user needs a Python environment with the above libraries installed. A common way to set this up is by using a distribution like Anaconda, which comes with most of these packages pre-installed.

Alternatively, the libraries can be installed using `pip`:
```bash
pip install jupyter pandas numpy matplotlib seaborn
```

## Technical Constraints
- The project is designed to be run locally. There are no web-based components.
- The datasets used are relatively small and are included in the repository, so there are no external data dependencies.

## Dependencies
The project's dependencies are the Python libraries listed above. There are no other external dependencies.

## Tool Usage Patterns
- **Data Loading and Cleaning:** Pandas is the standard tool for loading data from CSV or Excel files and performing any necessary cleaning or preprocessing.
- **Data Analysis:** A combination of Pandas and NumPy is used for statistical calculations.
- **Visualization:** Matplotlib and Seaborn are used to create plots and charts to visualize the data and the results of the analysis.
