# Breezy-Pickles

> Plan a custom route to save and share.
![HomePage](readme/HomePage.png)


## Table of Contents

1. [Team](#team)
1. [Architecture](#Architecture)
1. [Setup](#setup)
    1. [Installing Dependencies](#installing-dependencies)
    1. [Running Local](#local startup)
1. [Usage](#Usage)
1. [Requirements](#requirements)

## Team

  - __Product Owner__: Kimberly Ha
  - __Scrum Master__: CJ Apel
  - __Development Team Members__: Andrew Deal, Tracy Duong

## Architecture
![PathFinderArchitecture](readme/PathFinderArchitecture.png)


## Setup

### Installing Dependencies

From within the root directory:
```sh
sudo npm install -g bower
npm install
bower install
```

### Local Startup
#### Install MongoDb
```sh
brew update
brew install mongodb
```
####Run MongoDB
Create data directory from root directory:
```sh 
mkdir -p /data/db
```
Run from data directory:
```sh 
mongod
```
OR 

Specify path of data directory if default data directory not used:
```sh 
mongod --dbpath <path to directory>
```

#### Start server
```sh
node server/server.js
```

## Usage
Once dependencies are installed and local server is running, access application at localhost:3000. 

Create an account to make and save custom paths on the dashboard. 

## Requirements

  - "angularjs": "0.0.1",
  - "bcrypt-nodejs": "0.0.3",
  - "body-parser": "^1.14.1",
  - "bower": "^1.6.5",
  - "express": "^4.13.3",
  - "mongoose": "^4.2.5",
  - "path": "^0.12.7",
  - "url": "^0.11.0",
  - "angular": "~1.4.7",
  - "skeleton": "~2.0.4",
  - "bootstrap": "~3.3.5",
  - "angular-route": "~1.4.7",
