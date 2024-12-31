# Bistro Boss Server with Auth
Client Repo Link - [bistro-boss-client-with-auth](https://github.com/ProgrammingHero1/bistro-boss-client-with-auth)

<i> Today we did not work on This . It is same as the previous work changes . </i> 
## Overview
BistroBoss is a comprehensive restaurant management system designed to streamline operations, enhance customer experience, and improve overall efficiency. The system leverages modern web technologies to provide a robust, scalable, & high-performance solution for managing complex data structures and interactions within a restaurant environment.

## API End Points 

### Menu
- GET /menu: Retrieve all menu items.

```js
app.get('/menu', async (req, res) => {
    const result = await menuCollection.find().toArray();
    res.send(result);
});
```
### Reviews
GET /reviews: Retrieve all reviews.

```js
app.get('/reviews', async (req, res) => {
    const result = await reviewCollection.find().toArray();
    res.send(result);
});
```


## Technologies Used

### MongoDB
MongoDB is a NoSQL database that stores data in flexible, JSON-like documents. It offers:


### Express.js
Express.js is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications. It simplifies the development process with:


### CORS (Cross-Origin Resource Sharing)
CORS is a mechanism that allows restricted resources on a web page to be requested from another domain. This is crucial for enabling the frontend of BistroBoss to communicate with the backend server by:
