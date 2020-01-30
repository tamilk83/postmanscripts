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

1.Download the files and store it in a location
2. How to run the collection from CLI:

newman run -d company.csv Code_reusabilityHackathon2020.collection.json -e Hackathon2020.postman_environment.json --delay-request 500
3.How to run the script from postman:
  1.Import the collection json to postman
  2.Import the env variable to postman
