# A02

Welcome to Delali's Github Tutorial!

The first step is to download WebStorm. Apply for a student license through https://www.jetbrains.com/student/ .
This is where you will be programming. Once you are apporved, you will recieve an email with instructons on how to download the software, acoording to your operating system. 
Your OS should guide you directly through the downloading process. If you have any questions, visit https://grok.lsu.edu/article.aspx?articleid=18853 for additional support.


**Downloaded Webstorm?** 
Time to Create a Github Account. Visit https://github.com/ and create a free acount. I would recommend applying for the Student Developer Pack for extended access to everything Github has to offer, but the free version works fine for what you will need to do.


Now you'll want to download Git as a local file. Visit https://git-scm.com/downloads and download git onto your computer via a local file. 
For the sake of an example, I will sample how I donwloaded git onto my MacOS. 

1. Open the 'Terminal' app on Mac.
2. Copy and paste this into the terminal: /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
3. From there the script will explain what it will do and then pauses before it does it. Just press enter to continue. Congrats, you've downloaded HomeBrew! This is a Package Manager that will allow us to access and download git as a local file on our computer.
4. Copy and paste: $ brew install git
5. To test brew was properly installed, run "brew help". If it runs without error, you're ready to proceed.
6. It will then tell you to run two commands, depending on the name of your directory (Example: Run these two commands in your terminal to add Homebrew to your PATH:
   (echo; echo 'eval "$(/opt/homebrew/bin/brew shellenv)"') >> /Users/delalikumapley/.zprofile
   eval "$(/opt/homebrew/bin/brew shellenv)"))
7. With that, you have successfully downloaded Git! You're ready to move forward :)

Great! Now that you're all set up, it's time to connect everything. This way when we save our project, we can push any updates directly to Github which is online, allowing us to access it from anywhere.
In Webstorm, visit the "System Settings" (Ctrl + Alt + S) > Version Control > Git --> Enter the path to the git file you've just downloaded.

Switching gears back to Github for a second, sign into your new account and press "Create New Repository". Make sure you check off the button to add a README file and make it public. Press 'create' once you are satisfied with the given settings. Copy the public repository link.

Back to WebStorm, press 'File' > ' Project from version Control' and paste your repository link in the "URL" field. Press 'Clone'.

Congrats on creating your first file! Let's commit this directory before we forget. Right click the file and select "Git". Press "Commit Directory". Add a description of what you just did  (This is important for documentation purposes!). Once you're done, press "Commit and Push". 
Off it goes! Take a look at your Github. You should see the repository there. Now if you create any additional files or make any updates, as long as you commit and push the changes it will be reflected there.


========================================
_GLOSSARY_

**Branch**: A branch is a parallel version of a repository. It is contained within the repository, but does not affect the primary or main branch allowing you to work freely without disrupting the "live" version. When you've made the changes you want to make, you can merge your branch back into the main branch to publish your changes.
**Clone**: A clone is a copy of a repository that lives on your computer instead of on a website's server somewhere, or the act of making that copy. When you make a clone, you can edit the files in your preferred editor and use Git to keep track of your changes without having to be online. The repository you cloned is still connected to the remote version so that you can push your local changes to the remote to keep them synced when you're online.
**Commit**: A commit, or "revision", is an individual change to a file (or set of files). When you make a commit to save your work, Git creates a unique ID (a.k.a. the "SHA" or "hash") that allows you to keep record of the specific changes committed along with who made them and when. Commits usually contain a commit message which is a brief description of what changes were made.
**Fetch**: When you use git fetch, you're adding changes from the remote repository to your local working branch without committing them. Unlike git pull, fetching allows you to review changes before committing them to your local branch.
**GIT**: Git is an open source program for tracking changes in text files. It was written by the author of the Linux operating system, and is the core technology that GitHub, the social and user interface, is built on top of.
Github
**Merge**: Merging takes the changes from one branch (in the same repository or from a fork), and applies them into another. This often happens as a "pull request" (which can be thought of as a request to merge), or via the command line. A merge can be done through a pull request via the GitHub.com web interface if there are no conflicting changes, or can always be done via the command line.
**Merge Conflict**: A difference that occurs between merged branches. Merge conflicts happen when people make different changes to the same line of the same file, or when one person edits a file and another person deletes the same file. The merge conflict must be resolved before you can merge the branches.
**Push**:To push means to send your committed changes to a remote repository on GitHub.com. For instance, if you change something locally, you can push those changes so that others may access them.
**Pull**: Pull refers to when you are fetching in changes and merging them. For instance, if someone has edited the remote file you're both working on, you'll want to pull in those changes to your local copy so that it's up to date. See also fetch.
**Remote**: This is the version of a repository or branch that is hosted on a server, most likely GitHub.com. Remote versions can be connected to local clones so that changes can be synced.
**Repository**:A repository is the most basic element of GitHub. They're easiest to imagine as a project's folder. A repository contains all of the project files (including documentation), and stores each file's revision history. Repositories can have multiple collaborators and can be either public or private.

==============================
_REFERENCES_
https://grok.lsu.edu/article.aspx?articleid=18853
https://docs.github.com/en/get-started/quickstart/github-glossary#remote
https://brew.sh/
"Introduction to Github and Webstorm" by Arthur H. Hendela, Ph.D