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
![img]("https://github.com/user-attachments/assets/54cd79bc-c48e-4afc-8c1e-029578556d58")

Remove the directory "my-folder"

## COMMAND AND OUTPUT
![img]("https://github.com/user-attachments/assets/dbcd1c3d-f3b6-4691-906e-92d0c40cdd2f")


Create the file Rose.txt

## COMMAND AND OUTPUT


Create the file hello.txt using echo and redirection


COMMAND AND OUTPUT
 ![Uploading Screenshot 2026-03-18 214754.png…]()
Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT

Remove the file hello1.txt
<img width="636" height="129" alt="Screenshot 2026-03-18 214022" src="https://github.com/user-attachments/assets/16392150-683d-4eed-a9ef-98452987719a" />

## COMMAND AND OUTPUT
<img width="677" height="466" alt="image" src="https://github.com/user-attachments/assets/aa3c87ca-3069-4111-b1de-1da22834209a" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="612" height="226" alt="image" src="https://github.com/user-attachments/assets/5a22bb02-548d-40a7-934b-011ae7228bc3" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="568" height="123" alt="image" src="https://github.com/user-attachments/assets/df195256-449b-4fe5-a793-720a47b76796" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT
<img width="445" height="315" alt="image" src="https://github.com/user-attachments/assets/fe16e352-8b4b-417a-b4a8-ea10d5de41c5" />

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
<img width="478" height="110" alt="image" src="https://github.com/user-attachments/assets/1cbb9af0-2be5-4a2f-9e6b-84a887ccf044" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="523" height="218" alt="image" src="https://github.com/user-attachments/assets/033724fc-0f6a-40fe-a642-55fad1001f4a" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="482" height="177" alt="image" src="https://github.com/user-attachments/assets/dede61a6-d891-4540-9590-848e78114a8f" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="776" height="223" alt="image" src="https://github.com/user-attachments/assets/1c030fbd-88b0-45c5-b7db-ff206a4c4648" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT
<img width="623" height="424" alt="image" src="https://github.com/user-attachments/assets/9a161149-1ae9-4d39-bfa5-b594ee7e20ae" />



# RESULT:
The commands/batch files are executed successfully.

