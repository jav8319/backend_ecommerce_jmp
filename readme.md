
# Back-end eCommerce site  
      
## Table of content  

1.[Description](#description)
2.[Installation](#installation)
3.[Usage](#usage)  
4.[Questions](#questions)  

## Description  

This repository contains the back-end of what would be an ecommerce site. In order to see its functionality, it hast to be run in insomia or  simmilar app. Please visit https://insomnia.rest/download to download insomia. 

## Installation  

Make sure Mysql and node are available in the local computer as well as a software like insomia to test HTTP requests. First download the files, then, open a terminal in the folder containing all files, run the command "npm install", following this you need to run the schema file by either opening a mysql session and then copy and paste the commands from the schema.sql file or by running the file from the terminal. Once the database is created in the previous step, go again to the terminal and run the command "node ./seeds/index.js to populate the table or models. Now tthe ecommerce site is ready to process CRUD operations. Start the server by running the command "npm start". this will sync the data base and the server whicn is now listening in the local default port 3001.  

## Usage  

Once the server is synced with the data base you can test the site's functionality by making http request including get, post, put and delete. go to the routes foled  to see the syntax in the .js files. you can also see the video demo to see how it works, please follow the link  


## Questions  

I can be reached at <> or  [github]https://github.com/jav8319>

## License  

none
