## Goals and objectives

### What is the purpose of this version?
- Play Monopoly game without using the money with a simple system architecture

### What are the expected outcomes of the system?
- A simple app that enable the players to know how much money they have
- Be able to make transactions, like spend or receive money
- Create the initial architecture of the mobile app
- Setup internationalization in the mobile app

### Who are the stakeholders of the system?
- Who wants to play Monopoly and maybe don't have a friend to be the banker 

## Requirements and constraints
    
### What are the functional and non-functional requirements of the system?

#### Functional
- Make how much money the player have visible to him
- Enable the player to spend money
- Enable the player to receive money

#### Non-functional
- Internationalization, the system should support pt-BR and en-US
- The system should support light mode and dark mode
- The app should be published on Play Store

## Capacity planning
    
### How much traffic, data, and other resources does the system need to handle?
- None, this version doesn't have integration with the server side

### What are the expected growth rates for these resources?
- None

## High-level design
    
### What are the main components and modules of the system?
- Accounts 
- Transactions 
- Start game control

### How will these components interact with each other?
- Accounts display how much money the player has
- Transactions will increase or decrease how much money the player have in the account
- Start game control will set up the initial amount of money the player will have when the game is starting, adding some money in the account

## Testing and validation
    
### How will the system be tested to ensure that it meets the requirements?
- This version will start only with unit test and manual test

### What are the plans for validation and deployment?
- We can set up a code coverage to ensure validations in the deployment process
- Also, the tests can run in GitHub actions that shows the code coverage in some way