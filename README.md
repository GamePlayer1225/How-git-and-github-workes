# Overall infos

 ## SSH Key Path
    /c/Users/k1ker/.ssh/

 ## SSH link
    git@github.com:GamePlayer1225/How-git-and-github-workes.git

# How to make a pullrequest
1. Create a Folder where you want to create the local repository.
2. Open the Folder in Visual Studio Code.
    1. If Visual Studio Code is not installed, install it from this link: https://code.visualstudio.com/
    2. Complete the installation.
3. Open the git bash terminal.
    1. If git bash is not installed, install it from this link: https://gitforwindows.org/
    2. Press yes-next-next-next-next and then choose the Option "Use Git from Git Bash only".
    3. Complete the rest of the installation.
        1. If git bash is not the default terminal follow the next few steps, otherwise you can skip ahead to step 4.
        2. To set git bash, or any terminal as your default terminal, first open the terminal in Visual Studio Code by going to the top, under "Terminal" open "New Terminal", or by pressing "CTRL + SHIFT + ¨".
        3. After the terminal has opend look to the bottom right where the name of the terminal that you are currently using is written.
        4. Click the Arrow key to the right of the Plus button to open a dropdown.
        5. Click "Select Default Profile"
        6. At the top a dropdown will apear where you can choose your new default terminal.
        7. To use git and git bash properly pls choose git bash at the dropdown at the top.
4. Tipe "git init" this will make a local repository out of your folder.
5. Now you have to copy the SSH link from the remote repository from github.
6. Now tipe "git pull (the SSH link)" into the terminal
    1. if an error cumes up that says that you don't have an SSH key follow the next few steps otherwise jump to step 7.

7. Git will ask you if you really want to trust this pc.
8. Now wait a few more seconds and now you have the context of your remote repository in your local repository.
