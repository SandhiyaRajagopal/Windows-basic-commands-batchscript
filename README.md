# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
%userprofile%\Desktop\MyLab
![image](https://github.com/user-attachments/assets/81ed0fc5-7183-48d5-9b23-04c13432a2ec)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
%userprofile%\Desktop\MyLab
![image](https://github.com/user-attachments/assets/7d1bb562-18e7-4164-beba-3db25ce4d5aa)
![image](https://github.com/user-attachments/assets/ba3049d2-7681-4991-957d-8f0cb0f0d28b)

## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
![image](https://github.com/user-attachments/assets/ab46d819-e5ae-48a2-bd57-1cf18330b01e)


## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
%userprofile%\Desktop\Backup
![image](https://github.com/user-attachments/assets/03727300-f265-440b-bd86-995d0477b50a)
![image](https://github.com/user-attachments/assets/af0669d1-422f-4e53-8f19-2e66d45a630e)

## COMMAND AND OUTPUT
mv Myfile.txt %userprofile%\Documents
![image](https://github.com/user-attachments/assets/48e0a6d2-1c10-4287-bf78-1e17141ae3ba)


## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!

## OUTPUT

![image](https://github.com/user-attachments/assets/ce520d3d-7d50-4e62-955a-ab3ed96f3f6f)

# RESULT:
The commands/batch files are executed successfully.

