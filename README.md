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
<img width="427" height="47" alt="image" src="https://github.com/user-attachments/assets/b8ae3350-f09c-4f04-b570-4b3c65436c4a" />
Create a directory named "my-folder"

## COMMAND AND OUTPUT
<img width="443" height="53" alt="image" src="https://github.com/user-attachments/assets/e4843df8-0c4d-450c-ade0-e2526242b587" />
Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="665" height="443" alt="Screenshot 2026-05-20 110644" src="https://github.com/user-attachments/assets/efd326e7-a34b-4e9f-a891-83cbe922ce59" />
Create the file Rose.txt

## COMMAND AND OUTPUT
<img width="707" height="352" alt="image" src="https://github.com/user-attachments/assets/b186c650-8d70-48cd-9750-2c7426c8d17b" />
Create the file hello.txt using echo and redirection


## COMMAND AND OUTPUT
<img width="570" height="197" alt="image" src="https://github.com/user-attachments/assets/fea431cd-a038-40a1-8663-c66b35893f9b" />
Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="443" height="120" alt="image" src="https://github.com/user-attachments/assets/ddcd6891-5631-441b-9582-412ea37573c2" />
Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="435" height="138" alt="image" src="https://github.com/user-attachments/assets/39f898ee-20f9-41df-a398-dff05d952d73" />
List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="452" height="366" alt="image" src="https://github.com/user-attachments/assets/a8aa8f68-7450-4257-b872-a4d4413aeede" />
List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="531" height="262" alt="image" src="https://github.com/user-attachments/assets/a2a41feb-910d-4a39-a547-e4bdf7ecc715" />
Compare the file hello.txt and rose.txt

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="445" height="90" alt="image" src="https://github.com/user-attachments/assets/5fa7dc89-027c-4d28-8c2d-9ddde2a50831" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="632" height="220" alt="image" src="https://github.com/user-attachments/assets/636da45e-0cfe-477d-b5cc-876c2ba4d396" />




Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT
<img width="518" height="225" alt="image" src="https://github.com/user-attachments/assets/d1ed71aa-3439-4ef8-93dc-d6a153860f63" />




Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="587" height="208" alt="image" src="https://github.com/user-attachments/assets/e2c60efd-ba07-4177-a733-e492ae23f84a" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="466" height="411" alt="image" src="https://github.com/user-attachments/assets/b48544e2-c000-4718-8922-d66f37d0b6ce" />



# RESULT:
The commands/batch files are executed successfully.

