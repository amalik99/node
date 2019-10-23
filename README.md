
THIS IS CHANGED

# Try Out VS Cloud Environments: Node.js

This is a sample project that lets you try out VS Cloud Environments in a few easy steps.
   
## Things to try

This sample has been cloned into your VS Cloud Environment. You're able to work with it like you would any local code.

Some things to try:

1. **Terminal:** 
  - Press ctrl+shift+[backtick] to open the terminal
  - From the terminal run `node --version`
    > Note: node is not installed on the local machine, yet you're able to use it! 
  - Type other Linux commands (`uname`, `ls`, etc.) to interact with the underlying environment

2. **Use Node:** 
  - Restore npm packages: `npm install`

3. **Edit code:**
   - Open `server.js`
   - Try adding some code and check out the IntelliSense & ESLint features

4. **Build, Run, and Debug:**
   - Open `server.js`
   - Change the message to "Hello {your name} from Node.js!"
   - Add a breakpoint (e.g. on line 21)
   - Press F5 to launch the app
   - Once the breakpoint is hit, try hovering over variables, examining locals, and more.
   - Continue, then open a local browser and go to `http://localhost:3000`.

5. **Forward port:**
   - Stop debugging and remove the breakpoint.
   - Open `server.js`
   - Change the server port to 5000. (`const PORT = 5000;`)
   - Press F5 to launch the app in the container.
   - Run the **Cloud Environments: Forward Port from Environment...** command
     - Enter port 5000
     - Name it anything you'd like
     - View the forwarded ports in the Environment Details panel
   - Open the local browser and go to http://localhost:5000/ to see the app running on a different port.

6. **Source Control:**
    - From the Source Control side bar:
      - Stage changes.
      - Commit changes.
      - Push changes.
