# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

## COMMAND AND OUTPUT

<img width="1912" height="167" alt="image" src="https://github.com/user-attachments/assets/20cf780b-6f09-4ef6-8fd2-cbe8c80d87f8" />


Remove the directory "my-folder"

## COMMAND AND OUTPUT

<img width="1917" height="1130" alt="image" src="https://github.com/user-attachments/assets/aa5c7bba-e3cb-45d2-9f43-27c955a023a3" />


Create the file Rose.txt

## COMMAND AND OUTPUT

<img width="1885" height="327" alt="image" src="https://github.com/user-attachments/assets/f09dc84a-4e10-48ea-9ae4-c2266202e861" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT

<img width="1917" height="272" alt="image" src="https://github.com/user-attachments/assets/8bc129de-4716-443b-8caa-88a781eecada" />



Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT

<img width="1917" height="161" alt="image" src="https://github.com/user-attachments/assets/74131803-04cf-4e74-915b-91a34d0ae80b" />


Remove the file hello1.txt

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT

<img width="1901" height="267" alt="image" src="https://github.com/user-attachments/assets/037eb102-c534-456e-a26e-ae1dcb089a4e" />


List out all the associated file extensions 

## COMMAND AND OUTPUT

<img width="1917" height="1010" alt="image" src="https://github.com/user-attachments/assets/ccc41c4e-b356-43ee-8d98-4aef735c14b9" />



Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

<img width="1917" height="185" alt="image" src="https://github.com/user-attachments/assets/3fabe24b-f36f-4af9-8d20-a2c0c6b0d0bf" />


## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="1472" height="747" alt="image" src="https://github.com/user-attachments/assets/28e906a8-774b-4885-a901-83d47bb9b377" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="1467" height="742" alt="image" src="https://github.com/user-attachments/assets/c133606e-3cf3-47a7-9562-1077a880ab5b" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.





## OUTPUT

<img width="1476" height="748" alt="image" src="https://github.com/user-attachments/assets/9ee65ed3-b40a-4416-b255-7b7c0171a60d" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="1488" height="760" alt="image" src="https://github.com/user-attachments/assets/4ca6680a-987a-4f31-a7a6-7c80fbcaf6e0" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="1477" height="747" alt="image" src="https://github.com/user-attachments/assets/a3751d01-b3f0-43fc-81d4-cc3d9907b9c0" />

<img width="1468" height="755" alt="image" src="https://github.com/user-attachments/assets/9d1fc838-bc82-4f29-8f32-521335208992" />


# RESULT:
The commands/batch files are executed successfully.

