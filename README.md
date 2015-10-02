# bt

This project contains two folders, web server and app server.

To start the web server do the following

1. Install Node JS 
	https://nodejs.org/en/
2. Install bower by running npm install -g bower
3. clone the repository
4. open command prompt and go to server directory and execute following commands
5. npm install (this will install node dependencies, this might take some time)
	Python should be installed at your system, if not run "npm install -g python"
6. bower install(this will install bower dependency)
	bower will need Git to be installed. Install git from https://msysgit.github.io/ and follow the link to download .exe file.
	Try "git" command in cmd. If its an error, add the installation path of git to environment variables. 
	Follow: http://stackoverflow.com/questions/20666989/bower-enogit-git-is-not-installed-or-not-in-the-path
5. grunt serve (this will start http server) 
	If grunt is not installed. Use "npm install -g grunt",  "npm install -g grunt-cli"
