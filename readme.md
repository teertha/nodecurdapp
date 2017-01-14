This is basic example of CRUD application using Node.js, Express and mySQL.

## Installation
1. Clone/Download project
2. Go to project root directory and run this command
	"npm install"
3. Run this commnd run application
	"node app.js"
4. Open the URL in browser
	http://127.0.0.1:<app_port>/customers

## Configuration (database)
app.js

        host: 'localhost',
        user: 'root',
        password : 'root',
        port : 3306, //port mysql
        database:'nodejs'	

prerequisites:
- Install Node and nps in windows/Linux
- Install Mysql
- Create DB named nodejs and import customer.sql

