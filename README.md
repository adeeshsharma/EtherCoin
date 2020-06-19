# EtherCoin
EtherCoin is a crowd-funding application built on Ethereum Rinkby test network. This application enables contributor participation in all stages of a products development throughout its life cycle.

# NOTE:
This application was developed in 2018 so a few node dependencies might be depricated as blockchain dapp was in its early stages of development.

# HOW TO GET STARTED:

* INSTALL METAMASK BROWSER EXTENSION ON YOUR CHROME BROWSER AND CREATE AN ACCOUNT. YOU WILL BE PROVIDED WITH A 12 WORD PHRASE(SEED) ON     SUCCESSFUL REGISTRATION. KEEP THIS SEED SAFE AND SECURE SOMEWHERE.

* VISIT https://infura.io/ AND REGISTER FOR FREE. SELECT RINKBY TEST NETWORK AND YOU WILL BE PROVIDED WITH YOUR INFURA LINK THAT WILL LET YOU CONNECT TO A NODE IN ETHEREUM RINKBY TEST NETWORK. THIS IS NECESSARY FOR YOU TO DEPLOY THE APPLICATION ON ETHEREUM BLOCKCHAIN NETWORK.

* GO TO ETHEREUM FOLDER LOCATED IN THE ROOT DIRECTORY OF THE PROJECT. EDIT WEB3.JS FILE AND FEED YOUR INFURA LINK UNDER PROVIDER.

* GO TO ETHEREUM FOLDER LOCATED IN THE ROOT DIRECTORY OF THE PROJECT. EDIT DEPLOY.JS AND FEED YOUR METAMASK SECRET SEED AND INFURA     LINK UNDER PROVIDER.
  
* GO TO ETHEREUM FOLDER LOCATED IN THE ROOT DIRECTORY OF THE PROJECT. RUN "NODE COMPILE" TO COMPILE AND BUILD PROJECT.

* GO TO ETHEREUM FOLDER LOCATED IN THE ROOT DIRECTORY. RUN "NODE DEPLOY" TO DEPLOY THE APPLICATION ON RINKBY TEST NETWORK. YOU WILL GET A "DEPLOYED TO" ADDRESS IN THE TERMINAL. COPY THAT ADDRESS AND PASTE IT IN FACTORY.JS FILE LOCATED UNDER ETHEREUM FOLDER.

* RUN "NPM START"

* THE APPLICATION WILL START LISTENING ON LOCALHOST:3000
