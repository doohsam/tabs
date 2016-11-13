How To: Tabs
----------
-----------

This is the source code for the "How To: Tabs" 
To try the code on your computer:

Install Node.js
Install Git.
Open a command prompt.
Change to the directory that will contain the project. In your command prompt, type: cd <directory> (where <directory> is the directory that will contain the project).
Copy the source repository to your computer: git clone https://github.com/jamesshore/how_to_tabs.git
Change to the project directory: cd how_to_tabs

To run the build:
-----------------
-----------------


Install jake: npm install jake -g
Run jake: jake


If you made any changes, check them in.
Erase generated files: git clean -fdx
Reset any changes: git reset --hard
Check out old version: git checkout episodeXX (For example, git checkout episode1.)
After changing versions, look at your copy of the readme.md file. It will have information about working with the code for that episode. In particular:

Look at the "Install Node.js" line in the readme to see which version of Node the code is designed to work with.
If it's different than the version you have installed, find and install the correct version of Node.
Read the rest of the readme to see how to run the code.

To use Gulp
----------
-----------

Check out: https://css-tricks.com/gulp-for-beginners/