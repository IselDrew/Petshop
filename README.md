# Programming Task

Full-stack application, online e-commerce service that enables users to buy pets. 
Projects also has back-end side pagination, filter, sort and search features. 
Front-End part written using MVC, Publisher and Builder patterns.

## Built With

* [Material Design for Bootstrap](https://mdbootstrap.com/)
* [Node.js](https://nodejs.org/)
* [Express](https://expressjs.com/)
* [Joi](https://www.npmjs.com/package/joi)
* [Sequelize](https://sequelize.org/)
* [PostgreSQL](https://www.postgresql.org/)

## Prerequisites

Install [node.js](https://nodejs.org/en/), [npm](https://www.npmjs.com/) and [PostgreSQL](https://www.postgresql.org/).

## Getting Started

#### Clone repository:

````
git clone https://github.com/IselDrew/https://github.com/IselDrew/Payment-page.git
````

#### Install dependencies:

````
npm install
````

#### Configure config.js:

````
Add to config/config.js information about your database.
````

#### Run migrations and seeds:

````
npx sequelize-cli db:migrate
````
````
npx sequelize-cli db:seed:all
````

#### Start application:

````
npm start
````
Then go to localhost:3000


## Application preview

![Website preview](demo/demo.gif)

## Acknowledgements

This is a team project written along with [staspitsyk](https://github.com/staspitsyk). 
