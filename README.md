#Makers Academy Week 6 Project (Part 2): Angular.js
   
![angularshieldlogo](https://cloud.githubusercontent.com/assets/9297921/5607782/9326b4ba-9461-11e4-94aa-67560f807e5e.png)
   
AngularJS is an open-source web app framework that simplify both development and testing of such applications by providing a framework for client-side model–view–controller (MVC) architecture, along with components commonly used in rich internet applications.
   
###New Programs, Languages, Technologies employed.  
    
+ [Angular.js](https://angularjs.org/)
+ [Bower](http://bower.io/)
+ [Karma](http://karma-runner.github.io/0.12/index.html) test runner
+ Use of a Model View Controller (MVC) design
   
###Briefing
   
The object of the project was a simple Github user search, using Github's API. 
   
Also in this walkthrough we're going to build a simple Angular application that demonstrates a few new concepts:
   
+ Two-way data-binding
+ Dependency injection
+ Using bower, a package manager for the web
   
As always - TDD wherever possible
    
###Execution
   
The project was completed in the following stages:
   
+ Installed Node, and the package manager for the App (Bower) 
+ Drawn up an index.html page 
+ Created an Angular module, linking it to the HTML page. 
+ Set up a test environment using **Karma** as a test runner
+ Build an Angular Controller with accompanying unit test
+ Built out some mock search results in a static manner... 
+ ...then replaced them with dynamic
   
####Lessons Learned

Github's API endpoint is heavily rate limited - and we broke it repeatedly! Its something I hadn't previous encountered but it's quite an important consideration when developing Apps using external API's
   
First time I'd heard the phrase 'Boilerplate' whilst setting up the testing environment. 


**END**
