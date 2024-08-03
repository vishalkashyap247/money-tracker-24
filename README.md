get top 5 coins details instantly.

## about project
money-tracker-24 webpage helps user to get info about top 5 coins, page it self gets refreshed in 30 seconds.
This is a single page webpage which has table and info about update time and all
<img width="1440" alt="homescreen" src="https://github.com/user-attachments/assets/69abe5b0-74af-49ca-b1bd-735a85f7bde4">

## Technology used : ReactJS, Redux, MongoDB, Node, ExpressJS
## Project setup guide


Open Terminal.

Change the current working directory to the location where you want the	Open Terminal. Change the current working directory to the location where you want the cloned directory. Type git clone <url>
> git clone https://github.com/vishalkashyap247/money-tracker-24.git

Now project is successfully cloned

Some info: 
This project itself has two components
1. API - Backend (Express & MongoDB Based)
2. Client - Frontend (React & Redux based)
   
So backend has some environmental keys which can’t add publicly
1. MONGODB_URI
2. COINGECKO_URI

So to add this environmental keys just create a file names as  ‘.env’ in ./api directory (Image added for reference)
<img width="303" alt="info" src="https://github.com/user-attachments/assets/9082ea7f-094e-4cb6-897d-582bdc574830">


It is similar to txt file open 'env' file and paste below two lines and save it.
```javascript
COINGECKO_URI=https://coingecko.com/
MONGODB_URI=mongodb+srv://vishl@cluster.vv77mbn.mon.com/taskManagerDB
```

(These are dummy url not real one please contact me for these urls will guide how to create these)

backend all set:
just run few cmd on terminal (while being in /api directory)
> npm install

to install all dependencies to run the express backend

> node index.js

now backend start working on port 3000
to quickly test this open browser and search this link: ‘http://localhost:3000/' and if you are able to see ‘ Welcome to the root URL of the Server ‘ on the screen then it is good to go backend all set.


Now frontend

move back to client directory in terminal
> run rpm install ( To install all dependency to run react project)

> npm start press ‘y’ since port 3000 is already busy so it will start on some other port 

all set react will request backend to fetch 5 top coin from own backend and store the data in monogoDB 


after each 30 seconds interval re-fetching request is being made by react app and it will reflect same on the screen.

Feel free to reach me.
Thanks for reading.
