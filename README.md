# Setup Instructions

## Install a Code editor
You'll need a code editor to make changes to your prototype. VS Code is a well established and fairly accessible code editor.

1. [Download VS Code](https://code.visualstudio.com/)
2. Expand the zip file and move the **Visual Studio Code** file to your **Applications** folder.
3. Run the **Visual Studio Code** application.

## Install Node
The kit is designed to work with Node.js version 20 and above.

### Check if you have Node installed already
In the terminal, enter:

> node --version

- If it says command not found you do not have Node and will need to download and install it.
- If the version number starts with 20 you have the correct version installed.
- If it starts with a number lower than 20, you need to download and install version 20.

### Download and install Node
[Download version 20 from the Node.js website](https://nodejs.org/en/)

Run the installer with all default options.

### Once Node is installed
You’ll need to quit and restart the terminal to be able to use Node for the first time.

To check it's installed correctly you can again run:

> node --version

If it’s installed correctly it should show a number starting with 20.

## Install GitHub Desktop
1. [Create a free GitHub account](https://github.com/join) using your Mercator email address.
2. [Download the GitHub Desktop app](https://desktop.github.com/).
3. Run GitHub Desktop.
4. Sign in with your Mercator GitHub account details.

### Using GitHub Desktop
Use GitHub Desktop to work with repositories.

A repository contains all of the files in a prototype. You can use the repository to view the file history and work on your prototype with others.

### Cloning this repository
1. Open GitHub desktop
2. Click **File > Clone Repository**
3. Click **URL** tab
4. In the second **Local Path** field:
	1. Click the **Choose...** button
	2. Enter **prototypes** into the Clone As field
	3. Navigate to your **Documents** folder
5. In the first field paste: **sheldongold-mercator/prototype-kit-training**
6. Click **Clone** button
7. Click **Open in Visual Studio Code** button

## Running the prototype

### Terminal basics
You'll need to use a *terminal* to create and run prototypes. It lets you type in commands and run programs on your computer.

The important thing to remember about the terminal is that you work in one directory (folder) at any one time.

### Navigate to your prototype folder in the Terminal
You need to navigate to your prototype folder in the terminal. Most commands for the kit need to be run in the prototype folder.

Open a **Terminal** window (You can do this by hitting **CMD+SPACE** and starting to type **Terminal**)

To navigate to your prototype, type this command into the terminal and press enter:

> cd ~/Documents/prototypes/prototype-kit-training

### Installing the kit
You only need to do this for the first time you wish to run this prototype.
In the **terminal**, enter:

> npm install

### Run the kit
In the **terminal**, enter:

> npm run dev

The first time you run npm run dev, the kit will ask you whether you want to send anonymous data to help the team improve the service. Enter **y** or **n** to answer yes or no.

In your web browser, go to open [http://localhost:3000](http://localhost:3000).

You should now see GOV.UK Prototype Kit running in your browser and you're ready for the training to begin!

## Useful links and resources
- [GOV.UK Prototype Kit - Tutorials and guides](https://prototype-kit.service.gov.uk/docs/tutorials-and-guides)
- [GOV.UK Design system](https://design-system.service.gov.uk/)
- [HTML Cheat Sheet](https://html-css-js.com/html/tags/)
- [The Accessibility Cheatsheet](https://bitsofco.de/the-accessibility-cheatsheet/)
- [Git and GitHub Crash Course for Beginners](https://www.youtube.com/watch?v=l2yrJtwoC_E&ab_channel=CameronMcKenzie)
- [GitHub Skills - Interactive Course](https://skills.github.com/)
- [Visual Studio Code for Beginners](https://www.youtube.com/watch?v=bfvq_kTbnd8&ab_channel=HeightAboveSeaLevel)
- [Visual Studio Code - Keyboard Shortcut Cheatsheet](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-macos.pdf)
- [Claude.ai](https://claude.ai/new)


