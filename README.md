link to clone fake rest api-:: https://github.com/nbkhope/fake-restful-api

First Time use heruku command for new user--
1- go to heroku page 
2- where you first login 
3- then clone the github api to vs code
4- open terminal and type command
   1- heroku login
   2- heroku create (type project name without space)
   3- git add .
   4- git status
   5- git commit -m"done"
   6- git push heroku mastar
 
 


# Fake RESTful API

A fake RESTful API for testing purposes, running using the npm module **json-server**. You can easily deploy the API to services like Heroku by simply pushing the repository there.

## Installation

Run npm to install all dependencies:

```sh
npm install
```

Now you are ready to deploy to Heroku:

```sh
# Login with your Heroku account
heroku login

# Create the project
heroku create your-api-project-name

# Deploy to Heroku
git push heroku master
```

Test your API by running:

```sh
heroku open
```

## Editing the initial data

The database is in the file **[db.json](db.json)**. You can edit the JSON information there.

## HTTP Requests & Endpoints

Refer to the [json-server documentation](https://github.com/typicode/json-server) for how to use your API.
