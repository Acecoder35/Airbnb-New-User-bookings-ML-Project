First run the NDF_ONLY_project_final.ipynb
This notebook classifies the NDF vs non-NDF category and creates three new files.
1. train_new_final.csv(training data without NDF entries)
2. test_new_final.csv(test data without NDF predictions)
3. onlyNDF_final.csv(output for NDF predictions)

Now run the Final_Project.ipynb
This notebook tries to categorize the non-NDF entries into different classes.
It takes the train_new_final.csv and test_new_final.csv as the input train and test.
It trains on the the filtered training data and predicts for the remaining test data.
It predicts the predictions for the entries and then combines it with the onlyNDF_final.csv to give the final submission file named "final_project.csv"

Note: The location of the files must be changed.