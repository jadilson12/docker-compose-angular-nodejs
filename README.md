# Stack built with Docker Compose

This is a basic stack environment built using Docker Compose. It consists following:

* Node 12
* Angular 9.x
* MySQL 5.7
* MongoDB:latest

## Installation

Clone this repository on your local computer and switch to branch `master`.

Run the `docker-compose up -d`.

```
git clone https://github.com/jadilson12/docker-compose-angular-nodejs.git
cd docker-compose-angular-nodejs/
docker-compose up -d
```

Your  stack is now ready!! You can access it via

- api (Nodejs):          http://localhost:3001
- app-ui (Angular)    http://localhost:4201
- database (mysql)  http://localhost:3306
- database (mongoDB)  mongodb://localhost/node

  ```txt
   // access mysql
   ROOT_PASSWORD: node
   NM_DATABASE: dbnode
   USER: usnode
   USER_PASSWORD: pwnode

  // access mongodb
   NM_DATABASE: node
   PORT: 27017
  ```
## Author

Jadilson Guedes <jadilson12@gmail.com>  
License MIT <https://jadilson12.mit-license.org/>
