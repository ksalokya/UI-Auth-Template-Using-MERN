# UI-Auth-template-Using-MERN
  
## Installation
- Make sure that you have node installed in your computer or [Install Node](https://nodejs.org/en/)
- Inside the local directory here you have downloaded this repo, open your terminal
- Run this command to download all dependencies for this project
  ```SH 
    npm install
- Add `config.env` file in `root` directory
  ```JS 
    PORT=`Port Number`
    MONGO_URI=`MongoDB Url`
    JWT_SECRET=`JWT Secret Token`
    JWT_EXPIRE=`JWT Session expire time`
    EMAIL_SERVICE=`Service Provider Name`
    EMAIL_USERNAME=`apikey`
    EMAIL_PASSWORD=`Email Password`
    EMAIL_FROM=`Email Address`
- In `root` directory run command to start server
  ```SH
    nodemon server.js
- Now we can run this site locally 
- To see the site in your localhost run this command in your terminal inside `client` directory
  ```SH 
    npm start
  ```  
### Hope this will be helpful for your next project
