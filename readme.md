# README
To run the current version of the program successfully, please follow the steps below:

1. Unzip the file and open it using Visual Studio Code.
  
2. If you haven't already, install the latest version of Node.js.

3. Open a new terminal window in Visual Studio Code, then execute the following commands in order:

```bash
npm i express ejs
npm i --save-dev nodemon dotenv
npm i bcrypt express-flash express-session passport method-override sqlite3
```

# RUN THE SERVER
In a terminal window, enter the following command
```bash
npm run devStart
```
Open a browser, and go to localhost:3000, it should direct the user to log in.

# TERMINATE THE SERVER
If at any point the user would like to terminate the program, simply open the terminal window in which it was started and press control+c.
