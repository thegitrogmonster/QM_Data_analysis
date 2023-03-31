VSCode has a integrated UI which can be used to track changes and states of git-repositories 

# Using Git with Visual Studio Code 

1. Initialize a folder to reflect your repository. 

    1. With existing folder: go to Source control and click initialize repository 

    1. At the bottom of the corner one can see the branch name: main. 

    1. “U” next to file: file that is new but has not been added to the repository. 

        1. Click on “+” (staging) next to “U” which means that the new file has been added to the repository. 

        1. One can reset/unstage using “-“ 

    1. Commit the file. 

        1. Write into the “Message Field” first commit and click on the tick 

        1. If you commit your change to the wrong branch, undo your commit using the Git:  
            … -> Undo Last Commit; command in the Command Palette (Ctrl+Shift+P) 

    1. Adding a new branch 

        1. Shift + command + p -> command palette 

            1. Type crate branch and type in name 

            1. When adding a code, the added part is marked with coloured stripes. 

    1. Merge branches via “…” -> merch branch 

    1. Publish branch.  
        1. Give permission for GitHub to open vs code. 

        1. Select if public or private repository. 

    1. Copy repository. 

        1. Click “Clone on GitHub 

        1. Open command palette. 

        1. Select git clone and paste the URL. 

        1. Specify where one wants to clone. 

# Adding something to the First Commit 

* Click on “…” 

* Choose “Commit” 

* Choose “Commit Staged “Amend”” 

* Accept commit message. 

* After publishing one can see that this was all done via one commit 

# Creating a new branch 

You can create and checkout branches directly within VS Code through the Git: Create Branch and Git: Checkout to commands in the Command Palette (Ctrl+Shift+P). 

 