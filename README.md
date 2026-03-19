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
<img width="415" height="53" alt="image" src="https://github.com/user-attachments/assets/e3f66b3c-fada-4d8f-9968-3522ae08ddd2" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="374" height="55" alt="image" src="https://github.com/user-attachments/assets/c1438bb2-0249-4326-8a10-f51f99bd19db" />


Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="633" height="375" alt="image" src="https://github.com/user-attachments/assets/b9c3b80c-c30d-4223-a176-f15c1003cceb" />


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="590" height="119" alt="image" src="https://github.com/user-attachments/assets/7b956690-7662-4a44-a1ca-ff7145fcc2f3" />


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="539" height="145" alt="image" src="https://github.com/user-attachments/assets/0e2df5b1-aa93-4245-b7bd-7ad7c29efeeb" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="388" height="60" alt="image" src="https://github.com/user-attachments/assets/b8f10b2f-72b5-49be-b5b7-32a92b10f114" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="440" height="143" alt="image" src="https://github.com/user-attachments/assets/ff79c956-bc30-495d-ae79-591ad51e1643" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="432" height="339" alt="image" src="https://github.com/user-attachments/assets/8045fed5-a2ae-467b-aed6-e549048b8380" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="532" height="191" alt="image" src="https://github.com/user-attachments/assets/5fc377e9-44f7-4cb8-95c6-7865384a32cc" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".



## OUTPUT
<img width="405" height="104" alt="image" src="https://github.com/user-attachments/assets/396c5cd8-da39-4f31-9989-e85b40d94c88" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="595" height="248" alt="image" src="https://github.com/user-attachments/assets/9ef706b4-97c9-4446-888a-b3954d3a8b01" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="434" height="197" alt="image" src="https://github.com/user-attachments/assets/1511afdd-fb9c-40a9-b780-9e48fef6007b" />




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="584" height="143" alt="image" src="https://github.com/user-attachments/assets/dd42e3fe-209c-4133-955d-5bbcac20e1d8" />



Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="427" height="405" alt="image" src="https://github.com/user-attachments/assets/0011382f-b2fa-4f59-9bb5-cbedb9e54c16" />



# RESULT:
The commands/batch files are executed successfully.

