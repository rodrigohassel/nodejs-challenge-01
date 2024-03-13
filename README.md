# nodejs-challenge-01

Challenge 1, fundamentals about node.js using routes, JSON, CRUD, Streams and importing a CSV file.


Import tasks from an CSV file

Description
This project is a JavaScript application built using Node.js that utilizes streams, csv-parser, and JSON for processing CSV files. It provides functionality to read CSV files, parse them, and convert them into JSON format.

Installation
Clone the repository:
bash
Copy code
git clone https://github.com/rodrigohassel/nodejs-challenge-01.git
Navigate to the project directory:
bash
Copy code
cd nodejs-challange-01
Install dependencies:
Copy code
npm install csv-parse
Usage
To use this application, follow these steps:

User CSV file in streams directory called "tasks-data.csv".
Run the application:
Copy code
npm run dev

Example
Suppose you have a CSV file in streams directory named as tasks-data.csv with the following content:

Copy code
title,description
Task 01,Descrição da Task 01
Task 02,Descrição da Task 02
Task 03,Descrição da Task 03
Task 04,Descrição da Task 04
Task 05,Descrição da Task 05

Dependencies
csv-parser: Used for parsing CSV files.
fs: Node.js file system module.
path: Node.js path module.
License
This project is licensed under the MIT License.