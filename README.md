# Mobify Progressive Framework docker image

To run this simple do:

0- Build the docker image (needed once)
    `docker build . -t  mobify-progressive-docker` 

1- Start the container and attach to it: 
    `docker run -P 443:8443 -v `pwd`:/server -ti mobify-progressive-docker bash`

2- Change to project directory
    `cd  project_folder`

3- Install dependencies
    `npm install`

4- Run the app
    `npm run `
    
