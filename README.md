# postmanscripts
API simulation of Cybercube Apps

## Getting Started

These instructions will get you started with postman run in CLI 

### Prerequisites

* postman
* newman

### Installation

Install postman App from - https://www.getpostman.com/

Using NPM:
$ npm install -g newman

Using Brew:
$ brew install newman



### Deployment

* Download the files and store it in a location
* How to run the collection from CLI:

newman run -d company.csv Code_reusabilityHackathon2020.collection.json -e Hackathon2020.postman_environment.json --delay-request 500

* How to run the script from postman:
** Import the collection json to postman
** mport the env variable to postman
