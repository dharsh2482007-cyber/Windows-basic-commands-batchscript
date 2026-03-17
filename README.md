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
<img width="861" height="101" alt="image" src="https://github.com/user-attachments/assets/a6c550bb-0167-43b8-996e-631377506100" />

## COMMAND AND OUTPUT

Remove the directory "my-folder"
<img width="939" height="105" alt="image" src="https://github.com/user-attachments/assets/8f330dfc-a245-4e3c-8202-df7f4f131253" />

## COMMAND AND OUTPUT

Create the file Rose.txt
<img width="976" height="65" alt="image" src="https://github.com/user-attachments/assets/fb8eb40c-c73c-409c-b3a7-a616615a668f" />

## COMMAND AND OUTPUT

Create the file hello.txt using echo and redirection
<img width="1063" height="36" alt="image" src="https://github.com/user-attachments/assets/3a3f451d-ced1-4704-85c0-9f7c3f1729bd" />

## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt
<img width="990" height="115" alt="image" src="https://github.com/user-attachments/assets/d0651a80-7666-400b-9f08-89f9b8c80198" />


## COMMAND AND OUTPUT

Remove the file hello1.txt
<img width="848" height="85" alt="image" src="https://github.com/user-attachments/assets/479f2e11-66a8-4b66-b644-4caf01f5d262" />

## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory
<img width="944" height="184" alt="image" src="https://github.com/user-attachments/assets/0abcaac1-a8fb-4d31-bca2-4ad246710d97" />

## COMMAND AND OUTPUT

List out all the associated file extensions 
<img width="788" height="1064" alt="image" src="https://github.com/user-attachments/assets/bcd61b3a-afc4-4a2e-a770-4700cd98016d" />
<img width="1059" height="1089" alt="image" src="https://github.com/user-attachments/assets/f4492108-e73c-4084-9f0a-3081b82617f7" />

## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt
<img width="948" height="161" alt="image" src="https://github.com/user-attachments/assets/c1a1d695-7e56-44f6-acaf-76e7a7b54121" />

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="510" height="97" alt="image" src="https://github.com/user-attachments/assets/54f0a968-81cd-42c7-b003-a3418c199e87" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="591" height="231" alt="image" src="https://github.com/user-attachments/assets/0f53db6f-7ff5-47c4-b173-ac9cd678e69c" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="433" height="197" alt="image" src="https://github.com/user-attachments/assets/dbfb9314-c0f0-466c-b7f1-fb1ba6b64e8f" />




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT


<img width="412" height="62" alt="image" src="https://github.com/user-attachments/assets/9e6eed8b-ad1f-4ef5-a963-04223e2a1b30" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file 
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="380" height="159" alt="image" src="https://github.com/user-attachments/assets/d5d41044-fb98-4c46-9499-2e0c917946fe" />



# RESULT:
The commands/batch files are executed successfully.

