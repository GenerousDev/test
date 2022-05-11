# PREREQUISITE

## Operating System
* MacOS 10.9 and above (64-bit only)
* Windows 7 and above
* Linux Ubuntu 12.04 and above.

## Supporting Libraries

Node.js (12 or Higher) - Cross verify the Node.js installation by running the command: node –version in the terminal. To verify the npm version, run the npm –version command.

## Cypress and Docker Installation guide

[Follow these instructions to install Cypress.](https://docs.cypress.io/guides/getting-started/installing-cypress#npm-install)

[Follow these instructions to install Docker.](https://docs.docker.com/desktop/)



## SETUP WITHOUT DOCKER 

#### Fork and clone this repo to a local directory
* git clone https://github.com/<your-username>/<repo-name>.git

#### cd into the cloned repo
* cd <repo-name>

#### install the Dependency
* npm install

#### start the local webserver
* npx cypress open

## SETUP WITH DOCKER 

#### clone this repo to a local directory
* git clone https://github.com/<your-username>/<product-name>.git

#### cd into the cloned repo
* cd <product-name>

#### Build the Docker Image 
* docker build -t test .

#### Run the Docker Image 
* docker run test

Script Focus: What Does The Script Do?

The following activities were carried out on the Script


