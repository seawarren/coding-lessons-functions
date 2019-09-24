Web Template
============

This is a web template used for in-class exercises on functions and conditionals.

## Installation Instructions

**1. Fork this repository**

Click the fork button at the top of Github to make a copy of this repository on your own Github repo.


**2. Clone repository**

Next, clone this repository using the Terminal program on your Mac (command line). It is recommended to change your directory using the `cd` command to a location where you want to serve and work on your project. i.e. `cd ~/Desktop`. Then clone the url of your fork to your own computer.


**3. Install this template system**

Next, move into the directory you just cloned, and run the command below to install all of the dependencies. This only installs them within this folder. 

```
$ npm install
```

Now, you're ready to work on the project. Open the folder in Sublime. 

## Running Grunt

To see the web page with sample project, run grunt from the Terminal.

```
$ npm run grunt
```

**How to cancel out of terminal**

You can always cancel out of the watch task by pressing <kbd>Control</kbd> + <kbd>C</kbd> on your keyboard. This will allow you to quit Terminal and go on to other things.


After initial setup, you can always relaunch the site and continue from where you left off by opening your Terminal, and `cd` into the directory of your project, and running `grunt` by itself. This will launch both the connect/watch tasks as well as create the build folder.

```
$ npm run grunt
```

## Modifying exercise files

Once you've run grunt, you can find the exercise files in the `src` folder. In this particular project, they will be under `src/instagram` and `src/form`. 

