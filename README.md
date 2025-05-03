# ETL-Baby-Names

Success
> I made my extract function 99.88% much more efficient to process 288,000+ lines of code into a dataframe.
> Went from 8 minutes on 9 test files to 0.50 seconds after 2-3 days of learning

Learned
> If a list of dict/series is passed and the keys are all contained in the DataFrame’s index, the order of the columns in the resulting DataFrame will be unchanged.

Iteratively appending rows to a DataFrame can be more computationally intensive than a single concatenate. A better solution is to append those rows to a list and then concatenate the list with the original DataFrame all at once.

> I can try unpacking or just converting each txt file to a csv file FIRST
