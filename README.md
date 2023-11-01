This program performs linear regression on a dataset to predict sales based on advertising expenses for TV and Radio. It uses the scikit-learn library for machine learning.

Description
The program does the following:

Reads a CSV file named "Sales.csv" that contains data on advertising expenses for TV and Radio as well as corresponding sales figures.

Preprocesses the data by removing rows with missing values and duplicate rows to ensure data quality.

Splits the dataset into a training set (80% of the data) and a testing set (20% of the data) for model evaluation.

Builds a linear regression model using the training data.

Makes predictions on the testing data.

Calculates and prints the Mean Squared Error (MSE) to evaluate the model's performance.

How to Run
Ensure you have Python installed on your system.

Install the required libraries if you haven't already. You can install them using pip:

Copy code
pip install pandas scikit-learn
Download the "Sales.csv" dataset and place it in the same directory as the program or update the file path accordingly.

Run the program by executing the Python script:

Copy code
python your_script_name.py
Replace your_script_name.py with the actual name of your Python script.

Dataset
The program assumes that you have a dataset named "Sales.csv" in the specified format. The dataset should contain the following columns:

'TV': Advertising expenses on TV.
'Radio': Advertising expenses on radio.
'Sales': Sales figures.
Please make sure your dataset follows this format for the program to work correctly.

Note
The script utilizes scikit-learn's LinearRegression for modeling and train_test_split for data splitting.

The Mean Squared Error (MSE) is used as a measure of model performance. A lower MSE indicates a better fit of the model to the data.

You can adjust the test_size and random_state parameters when splitting the data to suit your requirements.

Feel free to adapt the README to your specific needs, and include any additional information or usage instructions that may be relevant for your users.




