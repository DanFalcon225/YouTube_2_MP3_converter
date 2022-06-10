# YouTube_2_MP3_converter
HTML, CSS, JS, Express, Node.js - YouTube 2 MP3 Converter Full Stack App

Current application enable to convert YouTube video into the mp3 file and then download it.

**Prerequisites**:

1) In order to run application successfully it is needs to be connected to the relevant API.
For this project https://rapidapi.com/ has been used.

2) To successfully connect API to the application please create following file: .env
Inside the file create following variables:
API_KEY and API_HOST.

3) Into the https://rapidapi.com/ search for "YouTube MP3" API and copy/paste host and key next to the corresponding variables inside the .env file

4) Please note that "node_modules" file has been excluded from the current repository so, please make sure to run following commands in order to install relevant
packages for the application:

* npm i express dotenv ejs node-fetch

* npm i nodemode --save-dev

**PS**

1) Nodemon package - enable to change the application without stopping the server

2) Application does not work with videos more than 10 mins

