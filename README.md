Flask-y
=======
A Bash script to create the file structure and required files for a flask application. By default, the script generates a single app; other apps can be made using the same folder structure, if needed.

Why?
----
The script is meant to fill the void in the FLask community where there isn't really a quick way to start a project like there is for something like Django. 

Requirements
------------
- A Linux (Unix) based computer (the script was tested on a Mac)
- **virtualenv** installed at an OS wide level

Instructions 
------------
1. Place the script in a folder where you want to create the Flask application
2. Open up terminal and change your directory to the folder where you placed the script
3. Run the following to give the script the required permissions ```sudo chmod 700 flasky.sh```
4. Run the script using ```./flasky.sh```
