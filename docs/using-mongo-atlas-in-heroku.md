# Using Mongo Atlas in Heroku

## Create a cluster in Atlas
- Atlas account
- Create cluster with a name ( e.g. testing), and select mongodb version

## Create a database user for cluster
- Create a database user with password

## Configure network access
- Access from anywhere(not production)

## Use mongoAtlas in project by environment variable
- Configure Heroku under application **"Settings -> Config Vars"** 
  - for example, `MONGODB_URL="mongodb://...."`



