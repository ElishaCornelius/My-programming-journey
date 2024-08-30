# My-programming-journey
This is just a documented proof of my journey
# Start...
I picked up a git and github tutorial from youtube with Gwen as the host, so I'll be starting with github.

# LESSON 1
       
1. learnt how to create a repository on github.  
2. Learnt how to edit readme file on github and commit changes  
3. To use git, I have to install git on my computer. To do that,  
    I have to first check if git is already installed on my computer. 
    I do that by opening the command line and typing "git --version" in the command line.
    Git wasn't installed on my laptop, 
    so i went to git website and install the one compatible with windows.  
4. Next, I learnt how to clone the repository, 
    which can also serve as a folder, I created on github to my computer. I do that by 
    clicking the repository on github and clicking on the "code" drop down bar and copying the 
    ssh link. I got down to my terminal on VScode terminal and type "git clone" and paste the code after 
    and then click enter. The repository will automatically be downloaded to my computer.          
5. After cloning, there are files that do not appear(hidden). To see those files, 
    I have to type the command "ls -la" command 
    in the terminal. After entering that command, a .git folder appers apart from other visible files. 
    The .git folder stores all the files that saves my commits and code changes overtime.           
# LESSON 2
1. Learnt how to make changes on my computer and save them on git so I can push to  
    github. I do that by first making changes by probably add a text to the readme file then move to the terminal to save changes. 
2. In the terminal, I can check what file was changed by typing "git status" 
    afterthat I can go ahead to save changes by typing "git add ." 
3. To commit the saved file/files, I type the command 
    "git commit -m "whatever message the complements the changes made"" the -m is for message, so that if I am working with other programers, they can also be able to track changes made.
4. The next step is to push to github. To do that i have to prove to github that i am the owner of my account. I have to link my github to my local machine. To connect my account to my local machine, I have need to use ssh keys. Ssh is used for encrypting information over unprotected network. Now I have to generate my ssh key on my local machine using the terminal. I do that by typing "ssh-keygen -t rsa -b 4096 -C "the email of my github account"" After pressing enter, I'll be prompted to give a name to the file where my ssh key wil be save. Then, I'll also be prompted to give a password, I can just leave it blank by pressing enter twicel. After the key has been generated, I need to go to where the file was saved and copy the ssh key (usually starts with "ssh-rsa"). On github, I'll go to settings and then ssh and gpg keys, where I'll see a button that says "new ssh keys" and click on it. I can give it whatever title But it should relate with the project I'm working on and then paste the ssh key in the box below, the cick add ssh key. I'll need to confirm with my password and that's all. To push to git hub, I simple type "git push origin main" The "main" there is the branch I am currently working on. To know the branck I am currentluy workin on, I just type "git branch" and click enter. after pushing this will automatically update my code on github.