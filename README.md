To run this app please follow the following steps :

1 - clone the repo : 
---

to clone the repo run this command : `git clone --recursive git@github.com:Abdullah-F/products_demo.git`<br>

2- to run the backend run the following commands:
---
 first: go to the backend directory inside the repo : `cd products_demo/products_backend` <br>
 second: run `docker-compose up -d` , this could take some time for the first time <br>
 the backend will be now running on <a href='http://localhost:3000/'>localhost:3000</a><br>
 
3- now run the front end as follows:
---
 first: go to the front end directory : `cd products_demo/products_front_end`<br>
 second: run `docker-compose up`<br>
 the project will be now running on <a href='http://localhost:3001/'> localhost:3001 </a><br>
 
 Runnig the tests:
 ===
 
 1-to run the backend tests run: `docker exec -it products_backend_app_1 bundle exec rspec`<br>
 2- to run the front end tests, from the project directory run: `docker exec -it products_front_end_frontend_1 npm test` or `docker exec -it products_front_end_frontend_1 npm test a`

TODO
-

1- use `useReducer` instead of `useState`
2- use `useContext` for better data sharing between components
