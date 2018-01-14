# About JBlog

JBlog is created for educational purposes and not a production ready application. You can find a tutorial to create such applications on [http://arslansoftware.com/tutorials/MSA.mp4](http://arslansoftware.com/tutorials/MSA.mp4).

JBlog has three parts as following:

## JHipster-Registry
You need to download JHipster-Registry from [https://github.com/jhipster/jhipster-registry](https://github.com/jhipster/jhipster-registry) or run following command ```git clone https://github.com/jhipster/jhipster-registry.git```. An instance of Jhipster-Registry must be run before other services. 

Next: In the 'jhipster-registry' folder path, run following commands to start jhipster-registry instance ```./mvnw``` & ```yarn``` & ```yarn start```.

## JHipster Gateway: jblog
The folder called 'jblog' contains a jhipster microservice gateway, where you can provide a graphical user interface to users. This gateway is ready to be implemented to work with other services. There is no connection between 'hello' microservice and 'jblog' gateway at the moment.

```./mvnw``` command starts the application.

## JHipster Microservice: hello
The folder called 'hello' contains a simple jhipster microservice application.

```./mvnw``` command starts the application.
