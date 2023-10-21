# <Prework Study Guide Webpage>

## Description

- This prework Study Guide was created for boot camp students who were going through the Prework. 
- My motivation is myself, spouse and the will to want to succeed in an awesome career.
- I built this project so I could have a better understanding of the processes and flow.
- I learned to take my time within the terminal, proof read, timebox, google to find answers to issues. - I also learned the very basic coding skills in HTML, JavaScript, and CSS.
- Through learning those skill above I also learned how to debug code and have a positive end result.

## Table of Contents (Optional)

If your README is long, add a table of contents to make it easy for users to find what they need.

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

- CREATE A REPOSITORY IN GITHUB

1. Make sure that you’re logged in to your GitHub account.

2. Click the plus sign in the top bar next to your profile picture.

3. Select "New Repository" from the dropdown menu.

4. Next, give the repository a name.
    a. Example:  prework-study-guide. 

5. When naming a repository, it's important to remember the following conventions:
    a. Be unique and descriptive for each repository name.
    b. Use all lowercase letters.
    c. Use dashes; we can't have spaces in our repository names, so we use dashes instead.
    d. Be consistent! Our GitHub account will follow us throughout our web development career, so show it some love.

6. Add a description to your repository. 
    a. Be concise and clear with your project descriptions.

7. Select whether or not we want this repository to be public or private.
    a. Since we want to share this with others, we will set it to Public.
    b. If we were to set it to Private, only invited collaborators would see it.

8. Next, select  (example file created) "Add README".

9. Now we have the option to give our repository a license so other developers can use our hard work fairly.
    a. For this project, we will select an MIT license, which gives us and others the ability to use our code commercially.

10. Click the green "Create Repository" button to create a new repository.

11. IF you are redirected to "Quick Setup- if you've done this kind of thing before" click <Code> header on the top left corner.

12. Now your screen with show your newly made repository

13. You should have a file called "README.md"
    a. .md extension indicates that this is a Markdown file.
    
- NAVIGATE IN GIT AND CREATE A FILE

1. We want to be able to see a list of files and directories on our computer. 
    (The ls command will allow us to do just that!)

2. Open the terminal and enter ls. A list of files and directories should appear.
    (The cd command allows us to change directories.)

3. Downloads should be among the directories that were listed in the terminal in the previous step. 
    a. We can navigate into the Downloads directory by entering the command, cd Downloads.

4. The pwd command, which is short for "print working directory," will print out the directory that we are currently in to the terminal. 
    a. Let's check to see if we successfully navigated into the Downloads directory by entering pwd.

5. Depending on how your machine is set up and where the directory was created, 
something like the following output should appear in the terminal, with your username in place of the <username>:
    a.     /Users/<username>/Downloads

6. The cd .. will allow us to navigate backwards one directory at a time. 
    a. Enter cd .. once and we will end up back where we started!

7. Next, we will create a directory for all of our boot camp files. 
    a. To create a directory, we can use the mkdir command. 
    b. In the terminal, enter mkdir bootcamp to create a new directory called bootcamp.

8. Check to see if this was successful by running the ls command again. 
    a. The bootcamp directory should be in the list!

9. We can navigate into the new bootcamp directory that we just created using the cd command by entering 
    a. cd bootcamp into the terminal.

10. To make sure that we successfully navigated into the bootcamp directory, enter pwd into the terminal.

11. Depending on how your machine is set up and where the directory was created, something like the following output should appear in the terminal, with your username in place of the <username>:
    a.    /Users/<username>/bootcamp
 
12. Now that we are inside of the bootcamp directory, let's create a new file by using the touch command. 

13. To create a new file called your-choice.txt, enter touch your-choice.txt in the terminal.

14. Now, let's try opening this file.
    a. If you are using macOS, enter open first-day.txt. 
    b. If you are using a computer with Windows, enter start first-day.txt. 
    c. These commands will open this new file within a default text editor.

- GIT COMMANDS TO SWITCH BRANCHES

1. The Git commands are git checkout main to switch to the main branch

2. Git pull origin main to pull in the latest changes.

VS CODE

1. Open Visual Studio Code (VS Code)

2. When you have installed VS Code, you can open it via the command line interface (CLI). 
    a. To do that, open the CLI and cd (change directory) into the directory you created (example bootcamp).

3. Type,    code .    to open VS Code
    a. For Windows users, this command is already installed and ready for use, but you must restart your CLI console for the command to work.
    b. For Windows users, this command is already installed and ready for use, but you must restart your CLI console for the command to work.

4. Clone our directory (example prework-study-guide) GitHub repository onto our computer.
    a. This will not only clone all the folders and files, but also a .git file that contains Git version control.
    b. Go to the prework-study-guide GitHub repo and select the green "Code" button.
    Select the SSH option and copy the value.
    
    c. Go back to the command line and navigate into the bootcamp directory if you haven't already done so. 
        1. Remember, when cloning a repo, you need to be inside the directory you want the repo directory to be in!

    d. In the command line, enter the following command, replacing <paste copied SSH value> with the SSH value you copied from GitHub:
        a. git clone <paste copied SSH value>

5. Take a look. Inside the bootcamp directory, there should now be a new folder called prework-study-guide.

6. Navigate to the prework-study-guide folder using the command cd prework-study-guide.

7. Because we already set up VS Code so that it will open from the command line, type code . in the command line to open the prework-study-guide in VS Code. 
    a. VS Code and the file should open after you press the Enter key.


 SAVE WORK TO GITHUB

1. In the terminal, navigate to the prework-study-guide directory. 

2. Use the following command to stage your changes:
   a.   git add -A

3. Add a commit message replacing <your message here> with a message that describes the changes you made during this edit:
    a.  git commit -m “<your message here>”

4. Once the changes are added and committed locally, make sure the local branch is up to date before pushing up the changes. 

5. Pull in the base branch main to your feature branch (for example: feature/add-js) by running the following Git command:
    a. git pull origin main

6. To complete the Git flow, use git push to push up your changes to the remote repository by running the following Git command:
    a. git push origin (for example: feature/add-js)

7. Now that the changes have been committed to the remote repository in GitHub, we can merge the branch and close the issue.

SYNC TO LOCAL BRANCH W/ REMOTE BRANCH IN GITHUB REPO

1. In the command line, navigate to the prework-study-guide directory. 
    a. If not currently in this directory, use the following commands from the current user's home directory:
        1. cd bootcamp
        2. cd prework-study-guide

2. Once inside the prework-study-guide directory, open the directory in VS Code if it's not currently open.
    a.  code .

3. In VS Code, check to make sure all of the starter code files for the project are still in there.

4. To check what branch we are currently on. we enter the following git command in the command line:
    a. Enter the following git command:   git status
        1. Right now, we should be in the main branch but remember, we don't want to add our work there until it is done and approved. So for now, we need to create a new branch to hold our work.
    b. To add a branch where we can save our work-in-progress, we will create a new feature branch.

5. Create a feature branch named (example:) “starter-code” by writing the following git command in the command line:
    a. git checkout -b feature/starter-code

6. Now, let's take a look at what we just did. In the preceding command, a new branch, feature/starter-code, is created and the working branch is changed to the new branch.
    a. The git command must precede every Git statement.
    b. The checkout command is to move the working branch to a new branch.
    c. The -b flag creates a new branch.
    d. The feature/starter-code is the name of the new branch. 
        1. We have added the prefix, feature, to indicate that it is a feature. 
        2. It is good practice to name the branches for the feature that will be developed by them to help indicate the purpose of each branch.

7. Now that we have created a new feature branch and made it the current working branch, let's verify this is true with the command git status once again. We should now be working in our new feature branch.
    a. git status

8. To add the starter code to the current working branch, feature/starter-code, we'll need to do the following:
    a. First enter the following Git command in the command line:
        1. git add -A
            a. The add command adds modifications in the current working branch to the staging area. 
            b. The -A flag indicates that we want to add all changes. 
            c. The staging area informs Git that the changes will be added in the next commit.
            d. In the preceding Git statement, a commit was created that captures a snapshot of the currently staged changes. 
            e. Once committed, feature/starter-code will be updated with the starter code.

9. Before we push this up to our repo, we should double-check if our local branch is in sync with the base branch in GitHub. 
    a. So let’s pull down any changes from the base branch.
        1. git pull origin main
    b. Reviewing that we identified a Git command with the git keyword. 
        1. Then use the pull command to receive a branch's modifications into the local environment. 
        2. The origin keyword indicates the source of the pull will be in the GitHub repo. 
        3. The main keyword indicates the branch. 
            a. In our case, we are receiving a branch called main from the GitHub repository.
    c. It is important to always do a git pull to make sure that you have the latest version of the project on your local computer before you start to work. 
        a. Otherwise, you might be working on outdated code!

10. Now our local branch has synced with the remote base branch, let's push our changes to the remote branch by using the following command:
    a. git push origin feature/starter-code
        1. In review, we are using a new command push to push the changes we have locally to our remote GitHub branch.
        2.  In the browser, navigate to your remote branch on GitHub. 
            a. As you’ll see, there is now a remote feature/starter-code branch in GitHub. 
            b. When using the push command, you can create a new remote branch or add new changes to an existing branch.

- GITHUB    PULL REQUEST, MERGE BRANCH, CLOSE ISSUE

1. Navigate to the prework-study-guide repository in GitHub. 

2. Change the branch to the (for example: feature/add-js) branch

3. Refresh the page to confirm that the changes we pushed up are now in the feature branch in GitHub.

4. Navigate to the "Pull Requests" tab and open a new pull request. 

5. Make sure that you select main as the base branch and (for example: feature/add-js) as the comparison branch. 

6. Click "Create pull request" to open a PR (pull request).

7. Once on the pull request form, give your PR a title and a short description of the changes. 

8. Click the "Merge pull request" button to merge your work into the main branch.

9. Now that our final JavaScript code has been merged, we can go ahead and close the associated GitHub issue. 
10. Navigate to the "Issues" tab and select the (for example "JavaScript") issue. Go ahead and close that issue.

## Usage

Provide instructions and examples for use. Include screenshots as needed.

To add a screenshot, create an `assets/images` folder in your repository and upload your screenshot to it. Then, using the relative file path, add it to your README using the following syntax:

![alt text](assets/images/screenshot.png)

## Credits

List your collaborators, if any, with links to their GitHub profiles.

If you used any third-party assets that require attribution, list the creators with links to their primary web presence in this section.

If you followed tutorials, include links to those here as well.

## License

The last section of a high-quality README file is the license. This lets other developers know what they can and cannot do with your project. If you need help choosing a license, refer to [https://choosealicense.com/](https://choosealicense.com/).

---

🏆 The previous sections are the bare minimum, and your project will ultimately determine the content of this document. You might also want to consider adding the following sections.

## Badges

![badmath](https://img.shields.io/github/languages/top/nielsenjared/badmath)

Badges aren't necessary, but they demonstrate street cred. Badges let other developers know that you know what you're doing. Check out the badges hosted by [shields.io](https://shields.io/). You may not understand what they all represent now, but you will in time.

## Features

If your project has a lot of features, list them here.

## How to Contribute

If you created an application or package and would like other developers to contribute to it, you can include guidelines for how to do so. The [Contributor Covenant](https://www.contributor-covenant.org/) is an industry standard, but you can always write your own if you'd prefer.

## Tests

Go the extra mile and write tests for your application. Then provide examples on how to run them here.