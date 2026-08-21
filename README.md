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
<img width="334" height="33" alt="image" src="https://github.com/user-attachments/assets/5039d14a-8ef6-4035-b298-4f19a8d9249a" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="323" height="40" alt="image" src="https://github.com/user-attachments/assets/f76ee650-a387-4f8a-a876-2532430fb06d" />


Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="567" height="406" alt="image" src="https://github.com/user-attachments/assets/b42ae18e-f4ab-49ab-b6d1-592a41ba2e6c" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="490" height="93" alt="image" src="https://github.com/user-attachments/assets/bcadb732-5702-44e1-84f2-eba68df7e9a7" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="490" height="93" alt="image" src="https://github.com/user-attachments/assets/82880079-cc4f-4fb3-80b1-384c7ebf11e1" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="342" height="42" alt="image" src="https://github.com/user-attachments/assets/15d8cb38-31d2-4c06-a141-729ee4bd0ddf" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="476" height="625" alt="image" src="https://github.com/user-attachments/assets/babc9d18-07da-4526-b140-fafc72329cec" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="513" height="189" alt="image" src="https://github.com/user-attachments/assets/66d8f85f-cb2d-4705-afdb-15d638aa14b4" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
<img width="387" height="75" alt="image" src="https://github.com/user-attachments/assets/c111716b-2618-4c90-ab9a-8adc0ea35de0" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT


<img width="620" height="232" alt="image" src="https://github.com/user-attachments/assets/03ffe0c4-7b3b-4fe8-abc9-830209f6a0ae" />


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="533" height="174" alt="image" src="https://github.com/user-attachments/assets/f1b8b13b-8731-4974-a27e-4b687d96cc67" />




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="631" height="193" alt="image" src="https://github.com/user-attachments/assets/c7740a29-27a6-421c-91cd-5eefd991c691" />

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="505" height="476" alt="image" src="https://github.com/user-attachments/assets/614f037f-35a9-4424-ad98-1a7d5be0b0b6" />


# RESULT:
The commands/batch files are executed successfully.

