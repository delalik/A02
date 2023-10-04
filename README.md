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

