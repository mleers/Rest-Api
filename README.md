This project creates a simple rest API service using node/express that connects to a mongodb database.  It demonstrates full CRUD capabilities to maintain products in an imaginary store.

Postman was used to test CRUD functionality.

## Usage:
Clone https://github.com/mleers/Rest-Api.git
run `npm install`
create config.js and wrap your url: 'DB connection string' and serverport:3000 in module.exports{}

Notice: This rest API connects to an external database and therefore uses a personalized connection string.  If you want to see this project in action, you need to connect a mongodb databse using your string.  It should look like:

(mongodb+srv://<yourusername>:<password>@clusterName-lzb4e.azure.mongodb.net/projectName?retryWrites=true&w=majority)


## The following endpoints are available, any products in the store are preceded by the /products URI

* GET `/`
* GET `/products`
* GET `/products/:id`
* POST `/products`
* PUT `/products:/id`
* DELETE `/products/:id`


