# US Drone Strike Visualization App


## Getting Started

Email me if you have any questions: pbindustriesapps@gmail.com

### Prerequisites

- Docker and Docker-compose (Docker CE is recommended)
- NPM Version >=v v8.11 (NVM is recommended for NPM version management)

### Set Up The Dockerized Nginx Server and Angular 6 Frontend

- Clone this project or download the zip from github
- Open the project in your terminal
- Create an .env file with your environment variables
- Run docker-compose.yml(leave this terminal running)
- Open new terminal in project directory
- Change directory to app directory
- Install npm dependencies
- Start frontend 

#### Example setup in Mac terminal:
```
git clone https://github.com/pbindustries/drone-strike-site
cd drone-strike-site/build
vim .env
docker-compose build
docker-compose up

### New Terminal Tab###
<Enter Project Directory>
cd /app
nvm use 10.9 (optional)
npm install 
npm run develop

```


# Dope Commands

`pkill mongod`



