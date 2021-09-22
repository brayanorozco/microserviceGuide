# Microservices guide 2

* Let's create a new folder and init a npm project inside it to create our first microservice.

* It can be a random name, the most important thing is make the microservice run.

* Package JSON: we can copy it from the HTTPS project and install the dependencies.

* configure the .env file / .babelrc / index.js

* Create new folders src, services, models, controllers, adapters. Every module needs an index.

* The purpose of the microservice is to make it as small as it can be done.

* Database engine is Posgrest

* The "settings" file from the SRC folder: data taken from .env to communicate with the database

* A research about the main index needs to be done, this function is in charge to show a message indicating
that we are stopping the container or process, it waits two seconds and then stops it.

* The database is going to be defined from the "index.js" file in the model folder, it's going to create the
structure of the model and execute it using sequelize.

* Controler is the one doing the action, and the service is the one calling the controler to execute
the action.

* Now is time to create the controler, and the first thing we need to do is to import the model we already
created.

* Now we have to create the service and here is where the logic is going to be.

