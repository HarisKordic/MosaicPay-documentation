# MosaicPay-documentation

<a href="https://github.com/HarisKordic/MosaicPay-backend/tree/main">Backend</a></br>
<a href="https://github.com/HarisKordic/MosaicPay-frontend">Frontend</a>

**SETUP**

Download the project files on this [link](https://github.com/HarisKordic/MosaicPay-backend/tree/dev)

Setup the .env file **in the root of the mosaicpay** project for the backend service MosaicPay-Backend/mosaicpay. Setup the .env.development file in **the root of the frontend** folder for the Next.js application MosaicPay-Backend/mosaicpay/frontend.



**Navigate to the root folder MosaicPay-Backend/mosaicpay and run the following command**

<code>docker compose up --build </code>

Wait for the services and containers to load and go live. 



**API TESTING**	

You can test the API endpoints via Swagger on this [link](http://localhost:8000/swagger/). **Be careful to run the docker compose command before accessing Swagger**

**APP TESTING**

App [link](http://localhost:3000/login)

The app is fully functional from the base start. Dummy logins and accounts are:

​      "email": "johndoe@example.com",

​      "password": "password123"

​      "email": "janesmith@example.com",

​      "password": "qwerty456"

​      "email": "michael@example.com",

​      "password": "abcdef123"

​      "email": "emily@example.com",

​      "password": "p@ssw0rd"

​      "email": "david@example.com",

​      "password": "secret123"

Choose one of them and login. Feel free to explore the app. Create accounts, transactions, delete, edit and upload documents.



**KAFKA UI**

[Link](http://localhost:8080/)

Here you can see the different producers and events triggered in Kafka. You can also see different partitions and serialized message data.



**PG ADMIN**



You can use the [Postgre SQL DBMS](http://localhost:5050/browser/)

The master **password is codecta all lower case.**



Happy testing.
