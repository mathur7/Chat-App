
##What is Meteor?        

![Alternate text](http://mrcoles.com/media/img/meteor-js-animated.gif)


* is a an open-source, Javascript framework
* it uses Javascript on both front and backend
* it has it's own hosting service and allows for easy deployment
* it speeds up your Web app by transforming it into a single-page Web app. 


#####How is Meteor different from other JS based frameworks?
    
* Since Meteor is a full-stack framework, you don't have to go through the hassle of configuring it to work with your backend like in the case of using angular with rails.

* the fact that mongoDB comes with the package when you install Meteor is awesome! it means you never have to worry about installing anything once you have installed meteor

* the server side of Meteor runs on top of node.js 

* it comes with it's own command line tool and just one single command compiles all the resources and outputs a standalone, ready-to-run application bundle.

* it uses DDP(Distributed Data Protocol) to send information back and forth between server and client


#####More info on DDP
    
    DDP is a standard way to solve the biggest problem facing client-side JavaScript developers: 
    querying a server-side database, sending the results down to the client, and then 
    pushing changes to the client whenever anything changes in the database. 
    
	DDP intelligently pulls your database to pick up changes and pushes 
	them down to the client. And it can simulate your model code on the 
	client, so your users see their screens update immediately without waiting for the network.


#####Getting started with Meteor

Meteor was designed for beginners with little to zero backend experience! So getting setup and having an app up and running will not take you more than a few minutes.

Here are the steps to get started.

Install Meteor:

		curl https://install.meteor.com | /bin/sh		
Create a project:
		
		meteor create <your-app>
		
Run it locally:

		cd your-app
		meteor 
		=> Meteor server running on: http://localhost:3000/
		
Unleash it on the world!

		meteor deploy your-app.meteor.com


    

#####METEOR IN A NUTSHELL

* Uses JavaScript on both client and server side. 
* Applications which act in realtime. 
* Powerful data synchronization. 
* Your client code can directly access database. 
* Realtime code updates. You can update code even when users are online. 
* As soon as you distribute the new code, updates are available on each browser frame with the app opened. 
* One stop application bundle - You can compile the entire code with a single command. 
* Code Security - You can make the sensitive code run in a privileged environment. 
* By default, Meteor uses the Handlebars templating library. 
* Meteor runs on top of node.js and uses MongoDb database.

RESOURCES

* [http://docs.meteor.com/#sevenprinciples](http://docs.meteor.com/#sevenprinciples)
* [https://www.meteor.com/blog/2013/12/13/why-web-beginners-should-start-with-meteor](https://www.meteor.com/blog/2013/12/13/why-web-beginners-should-start-with-meteor)
* [http://sebastiandahlgren.se/2013/07/17/tutorial-writing-your-first-metor-application/](http://sebastiandahlgren.se/2013/07/17/tutorial-writing-your-first-metor-application/)
* [http://differential.io/blog/meteor-killin-rails](http://differential.io/blog/meteor-killin-rails)

