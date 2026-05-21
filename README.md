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
<img width="673" height="208" alt="Screenshot 2026-05-21 093314" src="https://github.com/user-attachments/assets/f78c460a-a395-4b91-b722-f8b60423eaef" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT
<img width="690" height="362" alt="Screenshot 2026-05-21 093514" src="https://github.com/user-attachments/assets/9b772d5e-c846-48c0-9b9a-265ed37ecfb8" />

Create the file Rose.txt

## COMMAND AND OUTPUT

<img width="780" height="122" alt="Screenshot 2026-05-21 093533" src="https://github.com/user-attachments/assets/303a3e55-78a2-4274-9fa2-fdb0242e89b4" />

Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
<img width="636" height="146" alt="Screenshot 2026-05-21 093600" src="https://github.com/user-attachments/assets/c6c4f298-15a8-4ee5-8cd9-8fdddff4af8b" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT
<img width="636" height="146" alt="Screenshot 2026-05-21 093600 - Copy" src="https://github.com/user-attachments/assets/6edff4fa-3712-4de1-9246-51271a7c17c7" />

Remove the file hello1.txt

## COMMAND AND OUTPUT
<img width="652" height="197" alt="Screenshot 2026-05-21 093759" src="https://github.com/user-attachments/assets/4294df90-84fb-43be-9e17-f86e5d88424c" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT
<img width="527" height="543" alt="Screenshot 2026-05-21 093846" src="https://github.com/user-attachments/assets/7470fccf-e407-4dc4-96f4-848551f614cf" />

List out all the associated file extensions 

## COMMAND AND OUTPUT
<img width="602" height="198" alt="Screenshot 2026-05-21 093911" src="https://github.com/user-attachments/assets/b22db089-4cda-4761-8eb9-d481a0f42380" />


Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT
<img width="612" height="138" alt="Screenshot 2026-05-21 093940" src="https://github.com/user-attachments/assets/41b16e3d-3149-4175-aa8d-d469bcf46ac6" />



Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT
<img width="663" height="276" alt="Screenshot 2026-05-21 094007" src="https://github.com/user-attachments/assets/5e6ffd20-bbb2-44ee-be54-9233d8ef3daf" />


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="488" height="221" alt="Screenshot 2026-05-21 094016" src="https://github.com/user-attachments/assets/ca9aa5ef-c5dc-47e4-8f54-93e6d5647436" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT


<img width="455" height="257" alt="Screenshot 2026-05-21 094104" src="https://github.com/user-attachments/assets/1808bdf0-7479-48bb-bc6b-c78ee79a8c38" />

Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="398" height="477" alt="Screenshot 2026-05-21 094140" src="https://github.com/user-attachments/assets/78460479-7fb3-4cc5-877b-c8c4bcf8ce5d" />


# RESULT:
The commands/batch files are executed successfully.

