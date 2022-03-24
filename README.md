# Taylor ECommerce with MongoDB, load sample data, product inventory, and user accounts, cart

https://github.com/coding-to-music/denver-poverty-map

https://denver-poverty-map.herokuapp.com/

By Michael Barry https://github.com/MB13534

https://mb13534.github.io/denver-poverty-map/

https://github.com/MB13534/denver-poverty-map

## About

This is an open-source collaboration with the volunteer group, 'Code for Denver.' We build apps, software, and websites for non-profits, local government, and the community that serve their needs. This project uses the Mapbox API along with Denver public records to render a map that is more visually functional to possibly better aid future pover…

javascript api mapbox volunteering nodejs

## Setup

```java
  "scripts": {
    "start": "node backend/server",
    "server": "nodemon backend/server",
    "client": "npm start --prefix frontend",
    "dev": "concurrently \"npm run server\" \"npm run client\"",
    "data:import": "node backend/seeder",
    "data:destroy": "node backend/seeder -d",
    "heroku-postbuild": "NPM_CONFIG_PRODUCTION=false npm install --prefix frontend && npm run build --prefix frontend"
```

## Deploy to Heroku

```java
heroku create denver-poverty-map

heroku logs --tail
```
