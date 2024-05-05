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

## PROGRAM:
```py
## Developed By : K KESAVA SAI
## RegisterNumber : 212223230105
```
# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.

mkdir %userprofile%\Desktop\MyLab
![image](https://github.com/Kesavasai20/Windows-basic-commands-batchscript/assets/138849303/96762007-ee05-45a2-a564-7994e8df7108)

## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.

cd %userprofile%\Desktop\MyLab
![image](https://github.com/Kesavasai20/Windows-basic-commands-batchscript/assets/138849303/2655d315-0ebf-4586-b118-6917786e41a4)

## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

dir %userprofile%\Desktop\MyLab
![image](https://github.com/Kesavasai20/Windows-basic-commands-batchscript/assets/138849303/6ca8a729-33a1-4db9-a6b2-aed4aac2dc0a)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.

mkdir %userprofile%\Desktop\Backup mkdir %userprofile%\Desktop\Backup
![image](https://github.com/Kesavasai20/Windows-basic-commands-batchscript/assets/138849303/a5697091-2128-4991-b5e8-c8765f7325c4)


## COMMAND AND OUTPUT

mv Myfile.txt %userprofile%\Documents
![image](https://github.com/Kesavasai20/Windows-basic-commands-batchscript/assets/138849303/11eee88e-07e2-4643-8076-eb529d43b190)

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off mkdir %userprofile%\Desktop\DocBackup copy %userprofile%\Documents*.docx %userprofile%\Desktop\DocBackup echo Backup completed successfully!

## OUTPUT
![image](https://github.com/Kesavasai20/Windows-basic-commands-batchscript/assets/138849303/6b5d1c3c-ab82-45c3-ab2f-594f7445abff)

# RESULT:
The commands/batch files are executed successfully.

