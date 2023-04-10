# Lab Report 1

## Installing VScode

1. In order to download VScode, you first need to go the the Visual Studio Code website (https://code.visualstudio.com/)
2. Complete the instructions on the website to download it to your computer. I did not need to do these steps because my computer already had VScode downloaded

## Remotely Connecting

1. Open the terminal in VScode. This can be done by opening VScode and going to "view" in the top left corner of your Mac. Then, click "view" and you should be able to open the terminal.

2. Type in the command ssh cs15lsp23dd@ieng6.ucsd.edu. However, you will have to replace "dd" with the letters in your course-specific account. I typed in the command ssh cs15lsp23dd@ieng6.ucsd.edu because the letters in my course-specific account were "dd". *Screen shot here* As you can see in the screenshot, under the heading "Additional Accounts", the letters for my course-specific account were the letters where the dashes are in "cs15lsp23--" on the button text.

3. You may get the message The authenticity of host 'ieng6.ucsd.edu (128.54.70.227)' can't be established.
RSA key fingerprint is SHA256:ksruYwhnYH+sySHnHAtLUHngrPEyZTDl/1x99wUQcec.
Are you sure you want to continue connecting (yes/no/[fingerprint])? . *(Change to screenshot)* If this occurs, type in "yes" into the terminal.

4. You will then be prompted to enter your password. If you get an error message, make sure you wait 15-60 minutes after changing your CSE15L account password before trying again. When I attempted to do this, I got the following error message *Screenshot her* I waited around 20 minutes before trying again, and then everything worked as it was supposed to.

5. Once you enter your password, you will get this *Screenshot here*. You are done!


## Trying Some Commands

1. Using the terminal in VScode, run the following commands: cd, ls, pwd, mkdir, and cp. Try various combinations of these commands, noting when they work and when you get an error. I ran all these commands.
* cd 
![Image](Screen Shot 2023-04-10 at 11.49.36 AM.png)
* ls
![Image](Screen Shot 2023-04-10 at 11.47.08 AM.png)
* pwd
![Image](Screen Shot 2023-04-10 at 11.47.16 AM.png)
* mkdir
![Image](Screen Shot 2023-04-10 at 11.47.57 AM.png)
* cp
![Image](Screen Shot 2023-04-10 at 11.48.07 AM.png)

I also ran the following combinations. For some of the commands I didn't get any ouputs and for some I got errors.
* cd and cp
![Image](Screen Shot 2023-04-10 at 11.48.18 AM.png)
* pwd and ls
![Image](Screen Shot 2023-04-10 at 11.48.51 AM.png)
* mkdir and pwd
![Image](Screen Shot 2023-04-10 at 11.49.29 AM.png)



2. Run the following commands and note the output. 
* cd ~
![Image](imageName.png)
* ls -lat
![Image](Screen Shot 2023-04-05 at 5.53.55 PM.png)
* ls -a
![Image](imageName.png)
* ls <directory> where <directory> is /home/linux/ieng6/cs15lsp23/cs15lsp23abc, where the "abc" is a group members’ username
![Image](imageName.png)
* cp /home/linux/ieng6/cs15lsp23/public/hello.txt ~/
![Image](imageName.png)
* cat /home/linux/ieng6/cs15lsp23/public/hello.txt
![Image](imageName.png)

3. I ran all these commands and the following is what I got. *Screenshots here
