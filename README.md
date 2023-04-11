# Welcome to the Location Project By Nest

## Technology stack

This repository is built on top of Nest.js, Postgres, MongoDB.


Details frameworks and packages can be found in the package.json files in server-nest directory.

## Running the application

### Visual Studio Code

#### Prerequisites

- Node.js : To run npm packages
- Postgres : As a database for the application
- MongoDB : As a database for the application

##### Steps

- To run via vscode, we should run the server-nest projects, and also make sure postgres and mongodb is up and running.
- Create a `.env` file inside the `server-nest` directory. Add the below entries or change accordingly. You can follow the `.env.sample` file to see the format.

  ```
  APP_NAME=server-nest
  PROJECT_PATH=server
  PORT=8080
  DEFAULT_PAGE_SIZE=20
  
  MONGODB_HOST=localhost
  MONGODB_PORT=27017
  MONGODB_PASSWORD=strongpassword
  MONGODB_USER=admin
  MONGODB_NAME=test
  IS_MONGODB_CLOUD_URL=true
  MONGODB_CLOUD_URL=mongodb+srv://<USER>:<PASSWORD>@cluster0.abcd.mongodb.net/myFirstDatabase?retryWrites=true
  
  SENDGRID_API_KEY=123
  
  JWT_SECRET=JWT_SECRETfsdfsdfsdsd3435353
  JWT_EXPIRES_IN=10000
```

#### Server commands
```sh
cd server-nest
npm i
npm run start
```
