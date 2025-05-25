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
       mkdir %userprofile%\Desktop\MyLab
       ![image](https://github.com/user-attachments/assets/32c10ba4-bf3b-4009-b87f-3860c283f18f)


Remove the directory "my-folder"

## COMMAND AND OUTPUT
          cd %userprofile%\Desktop\MyLab

       ![image](https://github.com/user-attachments/assets/a09e65f5-7b13-4771-9f04-b9297d8bfa6c)



Create the file Rose.txt

## COMMAND AND OUTPUT
     
      type nul > MyFile.txt

![image](https://github.com/user-attachments/assets/a22b5ef9-65d1-44a2-a0ba-c9495c00741c)


Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT
         dir %userprofile%\Desktop\MyLab

![image](https://github.com/user-attachments/assets/362bc197-3716-47ba-aa14-9aa53c4df298)


Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT

      mkdir %userprofile%\Desktop\Backup


![image](https://github.com/user-attachments/assets/fb24375a-fc23-48da-b7f1-bddfdd4229ad)


Remove the file hello1.txt

## COMMAND AND OUTPUT

      copy MyFile.txt %userprofile%\Desktop\Backup

![image](https://github.com/user-attachments/assets/9359ab65-0259-4562-b857-09b09f356199)


List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT

          
          copy MyFile.txt %userprofile%\Desktop\Backup


![image](https://github.com/user-attachments/assets/f69c0860-29e4-4e82-b9f7-7c5e255aed85)


List out all the associated file extensions 

## COMMAND AND OUTPUT

            mkdir %userprofile%\Desktop\Documents

move MyLab Documents

![image](https://github.com/user-attachments/assets/461e9f57-fc56-4b71-9df7-a3507db33544)



Compare the file hello.txt and rose.txt

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
## COMMAND

          @echo off
          mkdir %userprofile%\Desktop\DocBackup
          copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
          echo Backup completed successfully!



## OUTPUT
![image](https://github.com/user-attachments/assets/a3e5d48c-434b-423a-9ba8-7dc7b0ade210)

## COMMAND
          @echo off
          mkdir %userprofile%\Desktop\DocBackup
          copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
          del %userprofile%\Documents\*.docx
          echo Backup and deletion completed successfully!


## OUTPUT

![image](https://github.com/user-attachments/assets/72f2c878-b10e-4b1e-a5a3-d22e6e559bed)




# RESULT:
The commands/batch files are executed successfully.

