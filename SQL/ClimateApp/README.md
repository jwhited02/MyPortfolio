# Advanced SQL Project
This project was a climate analysis on Honolulu, Hawaii. As part of the project there was a precipitation analysis, a temperature analysis, and I created an app to display the results using Flask. 

## The following Python libraries are required to run this program:

- `matplotlib`: For plotting and data visualization.
  - `%matplotlib inline`: Enables inline plotting in Jupyter Notebooks.
  - `style`: Used for applying different styles to plots (e.g., `"fivethirtyeight"`).
  - `pyplot`: For creating static plots.
- `numpy`: For numerical operations and array manipulation.
- `pandas`: Data manipulation and analysis.
- `datetime`: For working with date and time.
- `sqlalchemy`: SQL toolkit and Object Relational Mapper (ORM).
  - `automap_base`, `Session`, `create_engine`, `func`: For database connection and mapping.
- `Flask`: For creating a web server and building API endpoints.
  - `jsonify`: For converting data to JSON format.

You can install the necessary packages using the following command:

```bash
pip install matplotlib numpy pandas sqlalchemy flask

