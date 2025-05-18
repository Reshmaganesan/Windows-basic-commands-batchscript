WINDOWS COMMANDS:

Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.

COMMAND AND OUTPUT
mkdir %userprofile%\Desktop\MyLab
image

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.

COMMAND AND OUTPUT
cd %userprofile%\Desktop\MyLab
image

type nul > MyFile.txt
image

List the contents of the "MyLab" directory.

COMMAND AND OUTPUT
dir %userprofile%\Desktop\MyLab
image

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

COMMAND AND OUTPUT
mkdir %userprofile%\Desktop\Backup
image

copy MyFile.txt %userprofile%\Desktop\Backup
image

Move the "MyLab" directory to the "Documents" folder.

COMMAND AND OUTPUT
mkdir %userprofile%\Desktop\Documents
image



## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT



# RESULT:
The commands/batch files are executed successfully.

