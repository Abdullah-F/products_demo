To run this app please follow the following steps :

1 - clone the repo : 
---

to clone the repo run this command : `git clone --recursive git@github.com:Abdullah-F/products_demo.git`

2- to run the backend run the following commands:
---
 first: go to the backend directory inside the repo : `cd products_demo/products_backend` <br>
 second: run `docker-compose up -d` , this could take some time for the first time <br>
 the backend will be now running on <a href='http://localhost:3000/'>localhost:3000</a><br>
 
3- now run the front end as follows:
---
 first: go to the front end directory : `cd products_demo/products_front_end`
 second: run `npm install && npm start`
 the project will be now running on <a href='http://localhost:3001/'> localhost:3001 </a>
 
 Runnig the tests:
 ===
 
 1-to run the backend tests run: `docker exec -it products_backend_app_1 bundle exec rspec`<br>
 2- to run the front end tests, from the project directory run: `npm test` or `npm test a`
