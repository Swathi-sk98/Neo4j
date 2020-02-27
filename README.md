 Install neo4j and run neo4j by typing 'sudo service neo4j start' in terminal. And to view database, go to http://localhost:7474/browser/.


test.py is for checking if the question gives the right answer (questions and answers which is present in new q&a.csv file). neo.py is for storing in database.

only problem in our code is, in case of common target with multiple q&a, the random answer is selected and displayed.
