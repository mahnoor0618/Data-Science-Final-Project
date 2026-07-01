# Data-Science-Final-Project
# Financial Fraud Detection Using R

This is a simple interactive program built in Python that helps analyze transactions and identify potential financial fraud based on basic rules. It takes user input, evaluates the risk, generates a report, and shows visual plots.

## How it Works

The script evaluates each transaction and flags it as "Fraud" if it meets any of the following conditions:
* The transaction amount is greater than 100,000.
* The transaction time is between late night/early morning hours (0 to 4).
* The location is specified as "Foreign".

If none of these conditions are met, the transaction is marked as "Normal".

## Project Structure

* **CAF PROJECT.R**: The main R script containing the source code for data input, logic evaluation, and chart generation.

## How to Run

1. Make sure you have R or RStudio installed on your computer.
2. Open your terminal, command prompt, or R console.
3. Run the script using the following command:

   Rscript "CAF PROJECT.R"

4. Enter the number of transactions when prompted, and follow the on-screen instructions to input the details (ID, Amount, Time, and Location).

## Features Included

* **Interactive Input**: Prompts the user step-by-step for transaction data.
* **Summary Report**: Displays a detailed breakdown of each transaction along with total counts and the fraud percentage.
* **Visual Charts**: Automatically creates a Bar Plot and a Pie Chart at the end to visually compare Fraud vs Normal transactions.
