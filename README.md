# Winter is Coming: Proxy Server

Project deployment URL: http://34.229.154.23:3000/

## Overview
This proxy server displays all four project members' services on a single page and permits communication with their corresponding API's.
It uses middleware to serve up static asset requests, proxy requests for individual client app bundles, and proxy requests from running client apps to their respective services.

## Instructions
- Run `nvm use 14` to switch the version of node required for this project.
- Run `npm install` to install all the project dependencies
  - Update server/config/services.js as more members finish their services.
- Run `npm start` or `npm start:dev` to start the server