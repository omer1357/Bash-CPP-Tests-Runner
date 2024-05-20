# Bash CPP Tests Runner
Bash script to run cpp tests with multiple input files and comare to matching output files.
Diff and memory (using Valgrind) tests.

# How to use
 - Place tester.sh in the same directory as all of the cpp files of the project.
 - Place in that directory the folder "Tests" contains all the input and output files.
   Use .in and .out file extensions, Make sure each input and output files have the same name.
   Make sure all the files are in the correct format for diff (use dos2unix if files came from Windows OS).
 - Give tester.sh execute permissions.
 - Run tester.sh

# Results
Each test will print a summary line if passed or failed.
After all of the tests will complete a final summary for all tests will be printed.
A folder of failed tests will be created for easier debugging.
