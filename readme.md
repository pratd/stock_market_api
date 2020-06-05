# Project: Stock Market 
- Develop a REST API for delivering stock market data (DBMS of our won choice)
- Develop a Vue.js SPA that consumes the data provided by the API (Using Charts.js)
- Develop a NodeJS/Express app that consumes the data from the API(Using Charts.js and render engine from our own choice)



## Arquitecture, technologies and applications
In this project we are going to develop a REST API that will provide data for 2 extra apps: a NodeJS/Express app and a VueJS SPA:

WEB API:
- Implement a DB. (You can decide which DBMS to use and whether if your DB has to be relational or non relational)
- Backend has to be developed in PHP / Laravel v.7.

APP - COMPANY1
- This is a hypothetical customer for the API.
- It has to be developed in NodeJS to query the API so the responsability to obtain data relapse on the backend. It's important to properly design Classes and Methods that abstract data the cleaner the better.
- It won't be using AJAX as data will be consumed from the Backend and will be conveyed to the views.
- Views have to be responsive being Bootstrap allowed.
- It has to use Chart.js as a requirement.

SPA APP - Company2
- Create a SPA (Single Page Application)
- Implement VueJS and query data from the WEB API using AJAX.
- Using npm, webpack and sass is mandatory
- It has to use Chart.js as a requirement.

## Data Arquitecture
Analise and design a storage and control system that fulfills this requirements:

Values/Actions / Company
- Name of the action, for instance: TESLA MOTORS, IBEX 35, GOLD, etc
- Unic code pro example: TESLA, IBEX35, etc
- Description
- Logo or img
- Current price:
- qty / current price
- Relationship with the value / Action to which it belongs
- Datatype that includes microseconds

## Requirements and features of the WEB API
Using Laravel for the WEB API is mandatory. You must use all good practices that Laravel provide (Eloquent, Migrations, Routing, Controllers, etc.)
The main goal of the WEB API is to provide the client with endpoints to allow:
- List all Values / Actions / Companies available.
- List all registered prices within a date range. (Maximum 1 year)
- View detailed Value/ Action / Company (name, description, etc)
- List the values / Actions / Company that have increased the most in the last 24H

## Requirements and features of the APP - Market Basket
The application in NodeJS has to query the API from the BACKEND. It's important that all printed data comes from the NodeJS and not from the AJAX.
It must cover:
- Show value listing (including the last registered price)
- Top results page
- Detailed value page with its corresponding graphic
- Search results view + search form
- Menu bar with access to all of the pages

## Requirements and features of the SPA APP - Visual Market
The SPA built in VueJS will have to query the API from the FrontEnd by using AJAX. You are not allowed to use any Backend language to query the WEB API within the SPA.
It must cover:
- Show value listing
- Top results page
- Detailed value page with its corresponding graphic
- Add a value to be follwed
- Searcher Form
- Search results view

## Links that helped us developing this project

## Authors
* **Tech Lead: Axel Louis Fernández Brink**
* **Product Owner, Deployment Officer: Cristina Moreno Medran**
* **Prattya Datta**
* **Mani Tahriri**
* **André Joyo**
