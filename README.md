# python-Implementing-Unit-Testing
 
The script emails.py, matches users to an email address and lets us easily look them up! 
In this sample script we add a test to reproduce the bug, 
and verify that all the tests pass to make sure the script works

- check for basic functionality
- tests to check for edge cases
- try/except statement


emails.py: consists of two functions: populate_dictionary(filename) and find_email(argv). The function populate_dictionary(filename) reads the user_emails.csv file and populates a dictionary with name/value pairs. The other function, find_emails(argv), searches the dictionary created in the previous function for the user name passed to the function as a parameter. It then returns the associated email address. This script accepts employee's first name and last name as command-line arguments and outputs their email address. The script accepts arguments through the command line. These arguments are stored in a list named sys.argv. The first element of this list, i.e. argv[0], is always the name of the file being executed. So the parameters, i.e., first name and last name, are then stored in argv[1] and argv[2] respectively.
