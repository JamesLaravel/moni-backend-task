# Moni Backend Engineering Test

- A simple P2P wallet system with the following features
  - User can fund their wallets on the system
  - User can send funds to other users on the system
- The documentation for the server API : https://documenter.getpostman.com/view/5021068/UyxgJTMJ

## How to run this project

### Getting Started

- Clone the repository
- `yarn install` to install dependencies
- Make a copy of the .env.example
- `yarn start:dev` to start the server
- `yarn start:build` to build the application for production


## Project can be tested on the following

- From POSTMAN using: https://moni-typescript-test.herokuapp.com/
- POSTMAN DOCS: https://documenter.getpostman.com/view/5021068/UyxgJTMJ

## How to test the API
- step 1: Create a user account
- step 2: Login as a user
- step 3: Fund your wallet
- step 4: Complete payment on paystack checkout page by copying the checkout url returned from step 3
- step 5: verify the transaction using the reference code returned from step 4
- step 6: Transfer funds
- step 7(optional): Check user details to view current balance