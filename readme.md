# DevCamper API

> An in-depth backend API for a bootcamp directory website named DevCamper, based on the NodeJs-Express-Mongoose course taught by Brad Traversy

## Usage

Rename "config/config.env.example" to "config/config.env" and update the values to your own

To view the API documentation, open "public/index.html"

## Install Dependencies

```
npm install
```

## Run App

```
# Run in dev mode
npm run dev

# Run in prod mode
npm start
```

## Database Seeder

To seed the database with users, bootcamps, courses and reviews with data from the "\_data" folder, run

```
# Import all data
node seeder -i

# Destroy all data
node seeder -d
```
