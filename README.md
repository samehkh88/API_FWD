Trello's / fakerestapi APIs testing

Automate all the test cases and generate a testing report w/ the status of features using each test case/scenario status (PASS/FAIL), the execution time of the automated test, and the testing steps status (PASS/FAIL).

****  the Test report created by run on  newman ****

newman run "collection.json" -e "environment.json" -n 1 -r htmlextra

The reports is HTML report show all information and TCs
