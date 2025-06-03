# PLP Bookstore MongoDB Assignment

This repository contains the MongoDB queries and setup for the PLP Bookstore assignment.

## Setup Instructions

1. Install MongoDB on your local machine or set up a MongoDB Atlas cluster.
2. Run the `insert_books.js` script to populate your database:
   ```bash
   node insert_books.js
The script will create a database named plp_bookstore with a collection named books containing sample data.

Running Queries
Connect to your MongoDB instance using mongosh or MongoDB Compass.

Load the queries from queries.js:

javascript
load('queries.js')
Execute any of the functions, for example:

javascript
findBooksByGenre("Fiction")
getAveragePriceByGenre()
File Structure
insert_books.js: Script to populate the database with sample book data

queries.js: Contains all MongoDB queries for the assignment tasks

README.md: This file with setup instructions

Screenshots
[Include screenshots of your MongoDB Compass/Atlas showing collections and sample data]


## How to Use

1. First run the `insert_books.js` script to populate your database with sample data.
2. Then you can use the functions in `queries.js` to perform all the required operations:
   - Basic CRUD operations (Task 2)
   - Advanced queries with filtering, projection, and sorting (Task 3)
   - Aggregation pipelines (Task 4)
   - Indexing and performance analysis (Task 5)

The queries are organized as functions that you can call individually to see the results. Each function returns the MongoDB query result which you can view in your shell or application.

Remember to include a screenshot of your MongoDB Compass or Atlas interface showing your collections and sample data when you submit your assignment.