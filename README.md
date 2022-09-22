## PolygonScan:

# Technologies used:
-  Node JS: Backend
-  MongoDB database is used
-  ethers is used to connect and catch the event of smart contract


## Project Setup
- Clone Repo : https://github.com/Dipak-G-Dev/polyscanCOntract
- cd polyscanCOntract
- npm install (for setup backend dependency)
- node app.js (for starting development server and starting the event listening)


# Feature 
  it will listen to the doubleOrNothing contract event of userWon and userLost, it will keep listening the event and save it to db then show all the events in console.

# Note: 
- I have done a setup of mongoDb atlas for easing the user experience. so you don't have to setup momgodb or anything.
- All the keys used in the project are of testing network, please change keys accordingly from where you raise event.

