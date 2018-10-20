# Node-Project-Boilerplate
Starter files to get a simple node project going faster without having to set up from scratch. 

## Installation
Note: The Git Bash terminal is great if you're using Windows <br />
Note: If you're not familiar with [linux](#Useful-Linux/Terminal-Commands) or [git](#Useful-Git-Commands) commands, there's a list of commands with explanations below

1) In your terminal `cd` into the location where you want to download this project 
1) `git clone https://github.com/Alma-Sanchez/Node-Project-Boilerplate.git`
1) In the same terminal `cd` into the project folder i.e. `cd Node-Project-Boilerplate/`
1) Install the necessary libraires needed by running `npm install`
   - Feel free to use yarn commands if you already klnow them, but I'm leaving that out of this project for now
1) Now you're ready to being working! To start a local server run `npm start`
    - I have customized the start command to include [nodemon](https://nodemon.io/), which restarts your server for you so you can view your changes after saving your code and refreshing your webpage. To see what would happen without the nodemon command run `npm simple_start` instead of `npm start`

## Useful Linux/Terminal Commands
Note: the tab key autocompletes commands and file/folder names, makes your life easier
1) `cd` which stand for change directory
   - `cd Folder-Name/` this will open Folder-Name if it exists in the current directory/folder 
   - `cd ..` Moves up a directory/folder, so if you're in `~/Documents/JS_practice` you will end up at `~/Documents/` after running the command
  
2) `ls` lists most files in the current directory, may not show hidden files i.e. .gitignore
   - `ls -a` Let's you see all files including hidden ones. <br/>
   Note: `-a` is called a flag, the `ls` command has more flag commands available not just `-a` so feel free to explore

## Useful Git Commands
Note: I wrote the following commands mostly in the order that they are used
1) `git status` - This lets you view changes you've made in your project

2) `git add <file or files>` - This adds files you want to commit to your repository. There's multiple ways to use this command:
  a) `git add .` will add all the files with changes since your last commit which is also everything you see in red after running `git status`. The dot at the end of the command means all files in the current directory so you can use it
  b) `git add app.js` will add app.js or add any changes made to the file if it already existed 

3) `git commit -m "your message here"`

4) `git remote origin -v`
