# gitPracticeRepo

###Git and Github Instructions
Code Repository and Version Control


### Node/NPM
Node.js is a JavaScript runtime built on Chrome's V8 JavaScript engine.  NPM is the package manager for JavaScript and the world's largest software registry.  You will need NPM (which comes with Node.js) to install watch-http-server, which will in turn allow you to launch a server for your cloned project.

1.  You will need to install Homebrew (a package manager for macOS) to install Node.js and NPM.
2. To install Homebrew simply enter ```/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"``` into your terminal.
3. In your terminal, enter ```brew update```.
4. Then enter ```brew install node```.
5. To check fi NPM and Node.js are installed on your Mac, check the versions of each program.  ```node -v``` should return the version of node you just installed.  ```npm -v``` should return the version of NPM you just installed.

### watch-http-server
Watch-http-server is a simple zero-configuration command-line http server.

1. In the home folder of terminal command, type ```npm install watch-http-server -g```
  *note: Terminal might tell you to try installing again as root user, in which case, type ```sudo npm install watch-http-server -g```*
2. Once successfully installed, you can go into the main directory of the project you just cloned (cd => terminal command for change directory and then the file path of the directory you are navigating to.  If you are in the folder that contains the directory you cloned, you can simply write cd followed by the name of the directory. For example: ```cd gitPracticeRepo```  gitPracticeRepo will be the name of the project you clone from github.com), and enter the command watch-http-server.  This will launch your newly cloned project at ```http://0.0.0.0:8080/firstHTML.html```.
  *note: When making changes to your new project, you must first select inspect from your right click menu.  This will open up a menu on the right side of your browser.  You can then hold down your refresh button and select Empty Cache and Hard Reload to see any changes you make.*
