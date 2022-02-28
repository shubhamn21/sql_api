# Node.js Rest APIs with Express & MySQL example

## Project setup
```
npm install
```

### Run
```
node server.js
```
## Files:

DB connection values: ./app/config/db.config.js 
SQL queries: ./app/models/tutorial.model.js (check line 43)
./app/routes/tutorial.routes.js  
./app/controllers/tutorial.controller.js

# To test:
curl --location --request GET 'http://localhost:8080/api/tutorials'
