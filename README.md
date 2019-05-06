# Try Out VS Cloud Environments: Node.js

This is a sample project that lets you try out VS Cloud Environments in a few easy steps.
   
## Things to try

This sample has been cloned into your VS Cloud Environment. You're able to work with it like you would any local code.

Some things to try:

1. **Install language extensions**
  - From the Extensions gallery, install ESLint by Dirk Baeumer 
  - View the list of `Cloud Environment - Installed` extensions
    > Note: The ESLint extension has been installed in the remote environment
  - Reload VS Code
    > Note: VS Code automatically reconnects to your cloud environment

2. **Use node:** 
  - Restore npm packages: `npm install`

3. **Edit code:**
   - Open `server.js`
   - Try adding some code and check out the IntelliSense & ESLint features

4. **Terminal:** 
  - Press ctrl+shift+[backtick] to open the terminal
  - From the terminal run `node --version`
    > Note: node is not installed on the local machine, yet you're able to use it! 
  - Type other Linux commands (`uname`, `ls`, etc.) to interact with the underlying environment
    > Note: The local machine is Windows, yet you're able to issue Linux commands! 

5. **Build, Run, and Debug:**
   - Open `server.js`
   - Change the message to "Hello {your name} from Node.js!"
   - Add a breakpoint (e.g. on line 21)
   - Press F5 to launch the app
   - Once the breakpoint is hit, try hovering over variables, examining locals, and more.
   - Continue, then open a local browser and go to `http://localhost:3000` and note you can't connect to the server

6. **Forward port:**
   - Stop debugging and remove the breakpoint.
   - Open `server.js`
   - Change the server port to 5000. (`const PORT = 5000;`)
   - Press F5 to launch the app in the container.
   - Run the **Cloud Environments: Forward Port from Environment...** command
     - Enter port 5000
     - Name it anything you'd like
     - View the forwarded ports in the Environment Details panel
   - Open http://localhost:5000/ and show the booth attendant the running site

7. **Finish**
  - Complete steps 5-7 on the Challenge Worksheet