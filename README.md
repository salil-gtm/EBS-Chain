<p align="left">
  <img width="100" height="100" src="https://raw.githubusercontent.com/salil-gtm/EBS-Chain/master/Logo.png">
</p>

# Energy Backed Securitization using Blockchain
Solar power gives long term returns however the initial cost of setting up is quite high. India
being a tropical country has huge potential for generating solar energy, but the citizens need
to be further incentivized.
<p align="center">
  <img src="https://raw.githubusercontent.com/salil-gtm/EBS-Chain/master/Concept.png">
</p>

# Architecture Flow

<p align="center">
  <img width="650" height="200" src="images/arch.png">
</p>

1. The administrator interacts with Decentralized Energy UI comprising of Angular framework
2. The application processes user requests to the network through a REST API.
3. Implements requests to the Blockchain state database on Hyperledger Fabric v1
4. The REST API is used to retrieve the state of the database
5. The Angular framework gets the data through GET calls to the REST API

# Included Components

* Hyperledger Composer
* Angular Framework
* Loopback

# Screenshots

<p align="center">
  <img src="https://raw.githubusercontent.com/salil-gtm/EBS-Chain/master/Screenshot%20from%202018-10-14%2010-50-31.png">
  <img src="https://raw.githubusercontent.com/salil-gtm/EBS-Chain/master/Screenshot%20from%202018-10-14%2010-50-50.png">
  <img src="https://raw.githubusercontent.com/salil-gtm/EBS-Chain/master/Screenshot%20from%202018-10-14%2010-51-25.png">
  <img src="https://raw.githubusercontent.com/salil-gtm/EBS-Chain/master/Screenshot%20from%202018-10-14%2010-51-50.png">
  <img src="https://raw.githubusercontent.com/salil-gtm/EBS-Chain/master/Screenshot%20from%202018-10-14%2010-51-56.png">
  <img src="https://raw.githubusercontent.com/salil-gtm/EBS-Chain/master/Screenshot%20from%202018-10-14%2010-51-17.png">
  <img src="https://raw.githubusercontent.com/salil-gtm/EBS-Chain/master/Screenshot%20from%202018-10-14%2010-53-55.png">
</p>

# Running the Application
Follow these steps to setup and run this code pattern. The steps are described in detail below.

## Prerequisite
- Operating Systems: Ubuntu Linux 14.04 / 16.04 LTS (both 64-bit), or Mac OS 10.12
- [Docker](https://www.docker.com/) (Version 17.03 or higher)
- [npm](https://www.npmjs.com/)  (v5.x)
- [Node](https://nodejs.org/en/) (version 8.9 or higher - note version 9 is not supported)
  * to install specific Node version you can use [nvm](https://davidwalsh.name/nvm)
- [Hyperledger Composer](https://hyperledger.github.io/composer/installing/development-tools.html)
  * to install composer cli
    `npm install -g composer-cli`
  * to install composer-rest-server
    `npm install -g composer-rest-server`
  * to install generator-hyperledger-composer
    `npm install -g generator-hyperledger-composer`

## Instructions to Run
- Similar to [Here](https://github.com/IBM/Decentralized-Energy-Composer)

## Authors

* **Salil Gautam** - [salil-gtm](https://github.com/salil-gtm)
* **Anirudh Murali** - [Anirudh-Murali](https://github.com/Anirudh-Murali)
* **Rohan Chougule** - [rchougule](https://github.com/rchougule)

## Additional Resources
* [Hyperledger Fabric Docs](http://hyperledger-fabric.readthedocs.io/en/latest/)
* [Hyperledger Composer Docs](https://hyperledger.github.io/composer/latest/introduction/introduction.html)

 ## Acknowledgments
* Made with &#9829; during #HackathonPune 2018 in 24 hrs.
