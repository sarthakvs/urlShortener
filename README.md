# UrlShortener
A simple and fast URL Shortener web application built using a microservice-style backend. It allows users to generate short URLs for long links and redirects them efficiently.
Built using Go, Node.js, Express, and PostgreSQL.
1. Go service handles URL creation (POST /shorten)
2. Node.js service handles fetching & redirecting (GET /urls, GET /:shortcode)
3. Frontend dynamically updates without page reload
4. Uses PostgreSQL for storage

![image]![alt text](image.png)

Live llink: https://shortify-3w0i.onrender.com
   
# How to run
1. Download and extract the project
2. In the command prompt,go to the project Directory and run `npm install`
3. After installing run `npm start` or `nodemon server.js`
4. Enjoy :) 		
