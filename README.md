# Earthquake Analysis and Prediction Project

This Python project is designed to analyze earthquake data and predict earthquake magnitudes using various data analysis and machine learning techniques. It leverages popular Python libraries such as NumPy, pandas, matplotlib, geopy, and scikit-learn to perform data processing, visualization, and model training. In this README, you will find information on the project structure, dependencies, how to use the script, and potential future improvements.

## Dependencies

Before running the project, ensure you have the following Python libraries installed. You can install them using pip:

```bash
pip install pandas numpy matplotlib geopy scikit-learn
```

## Project Structure

The project is organized into several Python functions:

1. `data_cleaning()`: This function reads earthquake data from a CSV file, removes rows with missing values, and handles outliers.

2. `plot_avg_magnitude_by_year()`: Plots the average magnitude of earthquakes per year.

3. `plot_avg_magnitude_by_decade()`: Plots the average magnitude of earthquakes per decade.

4. `top_strongest_earthquakes()`: Prints the top 10 strongest earthquakes based on magnitude.

5. `top_seismogenic_places()`: Prints the top N seismogenic places based on the number of earthquakes.

6. `plot_magnitude_percentage_data()`: Plots the percentage distribution of earthquake magnitudes.

Additionally, the script includes the training and evaluation of a random forest model on earthquake data.

## Usage

To use the script, follow these steps:

1. Make sure you have the required dependencies installed (pandas, numpy, matplotlib, geopy, scikit-learn).

2. Run the script in a Python environment. It will automatically load earthquake data from a CSV file named 'earthquake_data.csv' and perform the analysis and predictions.

3. The script will generate various plots showcasing earthquake data analysis and print important insights.

4. It will also train a random forest model and display its performance metrics.

## Output

The script generates the following output:

- Plots showing the average earthquake magnitude per year and per decade.
- A plot displaying the percentage distribution of earthquake magnitudes.
- The top 10 strongest earthquakes based on magnitude.
- The top N seismogenic places based on the number of earthquakes.
- Performance metrics (MAE, MSE, R2 Score) for the random forest model.

## Future Work

This project serves as a foundational example of earthquake data analysis and prediction. Here are some potential avenues for future improvement and expansion:

- Implement more advanced data cleaning techniques to handle missing values and outliers effectively.
- Experiment with different machine learning models to predict earthquake magnitudes and compare their performance.
- Enhance data visualization with additional charts and graphs to provide deeper insights into earthquake patterns.
- Optimize the random forest model by tuning hyperparameters to improve prediction accuracy.
- Utilize the model's predictions to make informed decisions regarding earthquake safety measures or early warning systems.

Feel free to explore and expand upon this project to gain further insights into earthquake data and contribute to earthquake prediction research.
