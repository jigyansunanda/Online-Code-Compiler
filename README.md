<h1 align="center">Online Code Compiler</h1>

Welcome. This is a web application that compiles and runs code in `C++` and `Python`. <br /> <br />
<img src="https://github.com/jigyansunanda/Online-Code-Compiler/blob/master/media/app.png" height="70%" width="100%" >

### How to use
- To try the compiler locally, download the codebase. 
- Make sure you have following installed in your system: `react`, `NodeJS`, `Mongodb`, `Redis` and `Bull`. I have also used `nodemon` for help in development while working in `NodeJS`. 
- To run the client-written code in their corresponding languages, you need to have `GCC` compiler and `python` installed in your machine.

Then follow the below guide to start (client) frontend and server (backend) part of the application.

### Activate Client side
- Open Terminal
- Go to `client` directory inside the project codespace
- Write `npm start`. This will open the client side build with react on `port:3000` on your local machine

### Activate Server side
- Open Terminal
- Go to `backend` directory inside the project codespace
- Write `npm run`. If you have the above mentioned entities installed on your machine, you should be able to see a log of `Listening on port 5000` and `Successfully connected to Mongodb database` on terminal window.
- Optional: If you have `nodemon` installed on your machine, then you can use `npm run dev` instead of `npm run`. This will keep the backend in check on any changes made by you, and refresh the server accordingly.

#### Change programming language
<img src="https://github.com/jigyansunanda/Online-Code-Compiler/blob/master/media/language-selection.gif" height="30%" width="60%" align="center">

#### Code exceution status
<img src="https://github.com/jigyansunanda/Online-Code-Compiler/blob/master/media/execution-status.gif" height="30%" width="60%" align="center">

#### Switch theme
<img src="https://github.com/jigyansunanda/Online-Code-Compiler/blob/master/media/theme-change.gif" height="70%" width="100%" align="center">
