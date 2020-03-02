
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