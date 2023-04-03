# "Lost interest? Using artificial intelligence to predict if low-income households are at risk of meeting loan repayments" (Harvard Master in Design Engineering Graduate Thesis)  :robot:
A repo containing code and paper for my Master's in Design Engineering (MDE) thesis project which explored how machine learning can better predict if low-income households are at risk of meeting loan repayments. Acknowledgements: Professor [David C. Parkes](https://datascience.harvard.edu/people/david-c-parkes)) (advisor), [Cole Bateman](https://www.linkedin.com/in/cole-bateman/) (collaborator), and Professors [Milind Tambe](https://teamcore.seas.harvard.edu/people/milind-tambe) and [Boaz Barak](https://quantum.harvard.edu/boaz-barak) (CS182). Awarded the departmental thesis award.

**Code Setup:**

1. Run 'bash make_data_directory_structure,sh' from the top directory
2. Get data sets 'application_test.csv', 'application_train.csv', 'bureau.csv', and 
   'bureau_balance.csv' from https://www.kaggle.com/c/home-credit-default-risk/data
3. Insert data sets in data/raw
4. Run python files in alphabetical order, starting with 'a_data_manipulation.py' and 
   ending with 'e_lstm_plus_static_keras.py'
		-Note, you can run the baseline 'random_forest.py' and any point in the process 
		 to get comparative data
		-Note, 'd_join_sequence_and_features.py' takes the longest to run.

(Ignore the file 'scrap_code.py', it was used for testing and storing unused code)
