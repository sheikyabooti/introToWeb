# introToWeb
Introduction to Local Web Development

This project will install several tools to prepare for web development.  These tools are

1. git:  An open source source control system.  (https://git-scm.com)
    Specifically this installs a set of tools in C:\Program Files\Git\bin

     - bash.exe - a shell program
     - git.exe - git
     - sh.exe - another name for the bash shell program

2. Node.js:  A Node runtime.  A runtime is a system that interfaces between a language and the underlying hardware. (https://nodejs.org/en/)
    Specifically this installs a set of tools.

     - node.exe
     - npm.cmd
     - npx.cmd

3. Visual Studio Code:  A free to use Integrated Development Environment developed by Microsoft.  It provides access to the file system, source control, and terminal.  I use this to check out, compile, and develop web projects.  
  Specifically this installs a set of tools in C:\Program Files\Microsoft VS Code\


We will then install and run a node package, create-react-app.  This package will create a npx script that you can run.  This npx script will
set up all of the tools and technologies needed to create a local react project.

After we have installed the create-react-app package, we will run it, and create a local project, named reactproject1.  Once we have created this project, we can run it at any time by calling npm start from the reactproject1 folder.  Running npm start on this package will do two things.

1. Start up a local Node.js server, running on port 3000.
2. Start up a web browser, and connect to localhost:3000.  If the stars align, this will show a spinning react logo.

Install Node.js (tested 12.15.1 LTS)
-----------------------------
1. Navigate to https://nodejs.org/en/download/ in a web browser
2. Click LTS (Long Term Stable) build and click Windows Installer, this will install file node-v12.18.1-x864.msi
3. Install choclately when the prompt shows up (choclately is a package sever for certain C++ binary packages, required for some node modules)

Install Visual Studio Code (tested v1.42.1)
-----------------------------
1. Navigate to code.visualstudio.com in a web browser, preferrably chrome
2. Click Download for Windows (Stable Build)
3. run the installer program VSCodeUserSetup-x64-142.1.exe

Set up local workspace for react
-----------------------------
1. Inside VS Code, run Terminal.  I prefer powershell, but you can use whichever makes sense
2. Decide where you want your local development environment to be.  I like mine in c:\dev, so I will put my react projects in C:\dev\react.

   cd c:\<br>
   mkdir dev<br>
   cd dev<br>
   mkdir react<br>
   cd c:\dev\react<br>
   pwd          ' prints working directory, should show you are in c:\dev\react<br>

Install create-react-app and then create a test react project
-----------------------------
1. Inside VS Code, in a terminal, in c:\dev\react, run two commands
2. npm install -g create-react-app
3. npx create-react-app reactproject1
4. You can now test the app by typing

     cd reactproject1<br>
     npm start<br>

Links:
-----------------------------
nodejs.org
code.visualstudio.com
react.org

https://reactjs.org/tutorial/tutorial.html