# Lab Report 1

## Changing Your Password
1. Go to this [link](https://sdacs.ucsd.edu/~icc/index.php)
2. Enter your username and PID. ![Image](Screen Shot 2023-04-10 at 2.56.25 PM.png)
3. Click the button under the header "Additional Accounts"  
![Image](Screen Shot 2023-04-10 at 11.30.45 AM.png)

4. Click on the "Global Password Change Tool" link in the orange box ![Image](Screen Shot 2023-04-10 at 2.58.06 PM.png)
5. Click on the "Proceed to the Password Change Tool" under the header "Student, AX, or Course-Specific Student Accounts" ![Image](Screen Shot 2023-04-10 at 2.58.44 PM.png)
6. Enter your CSE 15L username (text on the button you first clicked) ![Image](Screen Shot 2023-04-10 at 2.59.49 PM.png)
7. Click on the "I want to reset my course-specific account password." link ![Image](Screen Shot 2023-04-10 at 3.00.43 PM.png)
8. Do the Duo Multi-Factor Authentication
9. Click on the "YES" button when prompted to confirm your email. ![Image](Screen Shot 2023-04-10 at 3.01.36 PM.png)
10. Go to your email and go to the "Password Reset" email. Click on the "UC San Diego Password reset page" link within the email.  

![Image](Screen Shot 2023-04-10 at 3.02.57 PM.png).  

![Image](Screen Shot 2023-04-10 at 3.03.15 PM.png)

11. Enter your new password, confirm the password by entering it again, then click the "Change Password" button. ![Image](Screen Shot 2023-04-10 at 3.04.37 PM.png)


## Installing VScode

Note: I did not need to do these steps because my computer already had VScode downloaded.

1. In order to download VScode, you first need to go the the [Visual Studio Code website](https://code.visualstudio.com/) 
2. Complete the instructions on the website to download it to your computer. 
3. Cick on the button in the top right that says "download". ![Image](Screen Shot 2023-04-10 at 3.14.37 PM.png)
4. Download the version that applies to your computer. ![Image](Screen Shot 2023-04-10 at 3.15.36 PM.png)
5. Open the downloaded file. You should now be able to use VScode. ![Image](Screen Shot 2023-04-05 at 5.19.33 PM.png)

## Remotely Connecting

1. Open the terminal in VScode. This can be done by opening VScode and going to "view" in the top left corner of your Mac. Then, click "view" and you should be able to open the terminal

2. Type in the command ```ssh cs15lsp23dd@ieng6.ucsd.edu```. However, you will have to replace "dd" with the letters in your course-specific account. I typed in the command ```ssh cs15lsp23dd@ieng6.ucsd.edu``` because the letters in my course-specific account were "dd". ![Image](Screen Shot 2023-04-10 at 3.31.29 PM.png) As you can see in the screenshot, under the heading "Additional Accounts", the letters for my course-specific account were the letters where the dashes are in "cs15lsp23--" on the button text.  

![Image](Screen Shot 2023-04-10 at 11.30.45 AM.png)

3. You may get the message.  
"The authenticity of host 'ieng6.ucsd.edu (128.54.70.227)' can't be established.
RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.
Are you sure you want to continue connecting (yes/no/[fingerprint])? ." If this occurs, type in "yes" into the terminal.

4. You will then be prompted to enter your password. If you get an error message, make sure you wait 15-60 minutes after changing your CSE15L account password before trying again. When I attempted to do this, I got an error message. I waited around 20 minutes before trying again, and then everything worked as it was supposed to.

5. Once you enter your password, you will get this ![Image](Screen Shot 2023-04-10 at 3.29.14 PM.png) You are done!


## Trying Some Commands

1. Using the terminal in VScode, run the following commands: ```ruby cd ```, ```ls ```, ```pwd ```, ```mkdir```, and ```cp ```. Try various combinations of these commands, noting when they work and when you get an error. I ran all these commands.

* ```cd ```
![Image](Screen Shot 2023-04-10 at 11.49.36 AM.png). 
This command is “Change Directory” and it is used to switch the current working directory to the given path

* ```ls ```
![Image](Screen Shot 2023-04-10 at 11.47.08 AM.png). 
This command is “List” and it is used to list the files and folders the given path

* ```pwd ```
![Image](Screen Shot 2023-04-10 at 11.47.16 AM.png). 
This command is “Print working directory” and it is used to display the current working directory

* ```mkdir```
![Image](Screen Shot 2023-04-10 at 11.47.57 AM.png). 
This command is "Make Directory" and it is used to create a new directory

* ```cp ```
![Image](Screen Shot 2023-04-10 at 11.48.07 AM.png). 
This command is "Copy" and it is used to copy files or directories from one location to another

I also ran the following combinations. For some of the commands I didn't get any ouputs and for some I got errors.
* ```cd ``` and ```cp ```
![Image](Screen Shot 2023-04-10 at 11.48.18 AM.png). 
In this screenshot, there is an error.

* ```pwd ``` and ```ls```
![Image](Screen Shot 2023-04-10 at 11.48.51 AM.png). 
In this screenshot, the pwd command ran becuase the current working directory was printed but the ls command did not.

* ```mkdir ``` and ```pwd ```
![Image](Screen Shot 2023-04-10 at 11.49.29 AM.png). 
In this screenshot, nothing is printed.


2. Run the following commands and note the output. 
* ```cd ~ ```
* ```ls -lat ```
* ```ls -a ```
* ```ls <directory> ``` where ```<directory>``` is ```/home/linux/ieng6/cs15lsp23/cs15lsp23abc```, where the ```abc``` is a group members’ username
* ```cp /home/linux/ieng6/cs15lsp23/public/hello.txt ~/```
* ```cat /home/linux/ieng6/cs15lsp23/public/hello.txt``` 

3. I ran all these commands and the following is what I got.
* ```cd ~``` 

![Image](Screen Shot 2023-04-10 at 3.39.47 PM.png). 
In this screenshot, the current working directory is changed to the user's home directory.

* ```ls -lat```

![Image](Screen Shot 2023-04-05 at 5.53.55 PM.png). 
In this screenshot, the files and directories in the current working directory are listed by modification time in reverse order.

* ```ls -a ```

![Image](Screen Shot 2023-04-10 at 3.40.18 PM.png). 
In this screenshot, all the files and directories in the current working directory are listed, including hidden files and directories.

* ```ls <directory> ``` where ```<directory>``` is ```/home/linux/ieng6/cs15lsp23/cs15lsp23abc```, where the ```abc``` is a group members’ username 

![Image](Screen Shot 2023-04-10 at 3.41.51 PM.png). 
In this screenshot, the files in the path ```/home/linux/ieng6/cs15lsp23/cs15lsp23dd``` are listed.

* ```cp /home/linux/ieng6/cs15lsp23/public/hello.txt ~/```

![Image](Screen Shot 2023-04-10 at 3.42.18 PM.png). 
In this screenshot, the files in the path ```/home/linux/ieng6/cs15lsp23/public/hello.txt ~/``` are copied.

* ```cat /home/linux/ieng6/cs15lsp23/public/hello.txt``` 

![Image](Screen Shot 2023-04-10 at 3.42.35 PM.png). 
In this screenshot, the contents of the file in the path ```/home/linux/ieng6/cs15lsp23/public/hello.txt``` are printed.


