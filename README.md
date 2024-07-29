This Python script reads a CSV file, filters out rows where the 'word' column contains punctuation or whitespace, and calculates the average of the 'totsurp' column from the filtered data.
Prerequisites

    Python 3.x
    pandas library

    Ensure you have a CSV file named joota_avg.csv with at least the following columns:

    word: Contains the words to be checked for punctuation and whitespace.
    totsurp: Contains the numerical values for which you want to calculate the average.

    The script will output the average of the 'totsurp' values excluding rows where the 'word' column is punctuation or whitespace.
