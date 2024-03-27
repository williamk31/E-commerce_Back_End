# E-Commerce Back End

## Description
This back end application allows users to create, view, and update the database for an e-commerce platform. Users can update products, sort them into categories, and apply multiple tags to multiple products.
  
## Table of Contents
  
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Questions](#questions)
  
## Installation
Make sure you have the latest stable version of [node.js](https://nodejs.org/en) and [postgres](https://www.postgresql.org/) installed on your machine. Navigate to this application's directory in your command line interface and run the 
```bash
npm install
```
command to install the required packages. Run 
```bash
psql -U postgres
```
enter your password, and create the database by running 
```bash
\i db/schema.sql;
```
Seed the database with the command
```bash
node seeds/index.js
```
And then start the application by running
```bash
node server.js
```
  
## Usage
Use Insomnia to test Get, Post, Put, and Delete routes for Products, Categories, and Tags. The following video demonstrates the application's functionality.
[Walkthrough Video]()
  
## Contributing
To contribute more, please contact me.
  
## Questions
Visit my [GitHub profile](https://github.com/williamk31)