# Simple Exercise in understanding Control Flow
This lab is designed to be a very gentle introduction to git and github. As such the exercise is very straightforward and each of the Parts in the exercise needs minimal code. The lab exercise has the following objectives:
- To get you started using git and github
- To get you started using the Command Line Interface
- To understand sequence, selection and iteration
- To understand the "Control Flow" of a computer program - the order in which the program executes statements and the way it jumps around

The program in the file Steps.py prints outputs the following
Step 1<br> Step 2<br> Step 3<br> Step 4<br> Step 5<br> Step 6<br> Step 7<br> Step 8<br> Step 9<br>

The goal is to acheive the same output using a mix of Sequence Selection and Iteration rather than just Sequence which is used in the orginal code.

# Part A

Copy the file Steps.py to PartA.py. Add the name of the program, a description of what it does, your name and the date in comments at the top of the file. Change the file to add a function at the top of file called printSteps(). This function should just print out 
Step 4
Step 5
Step 6

To the screen. Modify the original code so that the three lines in the middle of the set of original Steps are removed and replaced with a call to the function printSteps(). Execute your program. When the program is executed the output should look the same. Once your program is working, add your file to the repo by typing ***git add .*** into the Command Line Interface then write a commit to your repo by typing ***git commit -am "added printSteps() function"*** then push your code into the repo by typing ***git push origin main***.

# Part B

Copy the file PartA.py to PartB.py.  Modify the function you wrote in PartB.py so that rather than simply printing Step 4, Step 5, Step 6 to the screen the function will be more generally useful. Change the function printSteps so that it will accept two arguments so printSteps(a, b). Replace the code inside the function so that it uses a for loop to loop a variable i from a to b. Inside the loop print the "Step i" to the screen where i is the iteration of the loop you are on. Modify your code so that it now calls the function printSteps and passes the appropriate arguments to ensure the program sill outputs the Steps 1 to 9 to the screen the way it initially did. Modify the description in the comments at the top of the file to describe what your program will do. 

Once your program is working, add your file to the repo by typing ***git add .*** into the Command Line Interface then write a commit to your repo by typing ***git commit -am "changed printSteps() function to take two arguments"*** then push your code into the repo by typing ***git push origin main***.

# Part C

Copy the file PartB.py to PartC.py. Modify the function you wrote in Part B so that it removes all the original lines which print Step 1, Step 2 etc. Change the function call so there is only call to the function printSteps(a, b) but use appropriate arguments so that the output remains exactly the same as it is for Steps.py. Modify the description in the comments at the top of the file to describe what your program will do.

Once your program is working, add your file to the repo by typing ***git add .*** into the Command Line Interface then write a commit to your repo by typing ***git commit -am "Replace original Steps so only a loop is used"*** then push your code into the repo by typing ***git push origin main***.


