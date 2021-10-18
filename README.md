# Container Cloning

## Assigned: Wednesday, October 18, 2021
## Due: Friday, October 22, 2021

After cloning this repository to your computer, please take the following steps:

- Follow the instructions on the Proactive Programmers web site for this project
- Use the `cd` command to change into the directory for this repository.
- Change into the program directory by typing `cd source`.
- Run both of the provided Python scripts by typing the following:
  - `python perform-container-cloning.py`: perform duplicate removal with container cloning
- Confirm that the programs are producing the expected output
- Explain why the programs produce the output that they do
- Repair all of the defects inside of the program suggested by the checks
- Use a `docker run` command for your operating system to run GatorGrader
- Provide all of the required responses in the `writing/reflection.md` file
- The program should initially produce the following output:

```
Expected output not correct for input lists: [1, 2, 3, 4] and [1, 2, 5, 6]
  actual_list_one: [2, 3, 4]
  actual_list_two: [2, 5, 6]
At least one test case did not pass!
```

- You need to fix the defects in the program so that it produces the correct output!

```
Expected output correct for input lists: [1, 2, 3, 4] and [1, 2, 5, 6]
All of the test cases passed!
```
