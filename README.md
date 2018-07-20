# gitPracticeRepo

### Node/NPM
Node.js is a JavaScript runtime built on Chrome's V8 JavaScript engine.  NPM is the package manager for JavaScript and the world's largest software registry.  You will need NPM (which comes with Node.js) to install watch-http-server and git, which will in turn allow you to launch a server for your cloned project and start practicing version control.

#### Mac
1.  You will need to install Homebrew (a package manager for macOS) to install Node.js and NPM.
2. To install Homebrew simply enter ```/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"``` into your terminal.
3. In your terminal, enter ```brew update```.
4. Then enter ```brew install node```.
5. To check if NPM and Node.js are installed on your Mac, check the versions of each program.  ```node -v``` should return the version of node you just installed.  ```npm -v``` should return the version of NPM you just installed.

#### Windows
1. Windows requires the installation of a package manager called Chocolatey.  Click the link below for instructions.
*https://chocolatey.org/*
2. After installing Chocolatey, you will then need to use it to install Node/NPM.  Click the link below for instructions on how to install Node/NPM using Chocolatey.
*https://chocolatey.org/packages/nodejs.install*


### watch-http-server
Watch-http-server is a simple zero-configuration command-line http server.

1. In the home folder of terminal command, type ```npm install watch-http-server -g```
*note: Terminal might tell you to try installing again as root user, in which case, type ```sudo npm install watch-http-server -g```*
2. Once successfully installed, you can go into the main directory of the project you just cloned (cd => terminal command for change directory and then the file path of the directory you are navigating to.  If you are in the folder that contains the directory you cloned, you can simply write cd followed by the name of the directory. For example: ```cd gitPracticeRepo```  gitPracticeRepo will be the name of the project you clone from github.com), and enter the command watch-http-server.  This will launch your newly cloned project at ```http://0.0.0.0:8080/firstHTML.html```.
*note: When making changes to your new project, you must first select inspect from your right click menu.  This will open a menu on the right side of your browser.  You can then hold down your refresh button and select Empty Cache and Hard Reload to see any changes you make.  There is also a console tab in the right side browser menu (AKA developer tools).  Keeping your console open is essential to programming, as it will show you error messages and gives the capabilities necessary for further debugging.*

### Git and Github Instructions
Code Repository and Version Control
1. Clone a repository: ```git clone <specific url from github.com>```.  In this case, you will be entering: ```git clone https://github.com/steveflint3/gitPracticeRepo.git```.
2. Make a new branch: ```git checkout -b <name of your new branch>```. This will create and switch you to your new branch.
3. To stage, or add what files you would like to your commit: ```git add <file name>```.  In this case, you can simply add all of the files in your project to the next commit by entering ```git add .```.
4. Make a commit: ```git commit -m"Your descriptive yet succinct commit message here."```
5. Push your changes to GitHub: ```git push```.
*Here is a list of commonly used Git commands, if you would like to practice more!! https://github.com/joshnh/Git-Commands*

### HTML and CSS resources: #### There are various excellent resources for HTML and CSS online.  Below are some of my favorites.
1. https://www.w3schools.com/htmL/
2. https://www.w3schools.com/css/
3. https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started
4. https://developer.mozilla.org/en-US/docs/Learn/CSS/Introduction_to_CSS/How_CSS_works
