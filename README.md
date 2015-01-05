#Makers Academy Week 6 Project (Part 2): Angular.js
   
![angularshieldlogo](https://cloud.githubusercontent.com/assets/9297921/5607782/9326b4ba-9461-11e4-94aa-67560f807e5e.png)
   
AngularJS is an open-source web app framework that simplify both development and testing of such applications by providing a framework for client-side model–view–controller (MVC) architecture, along with components commonly used in rich internet applications.
   
###New Programs, Languages, Technologies employed.  
    
+ [Angular.js](https://angularjs.org/)
+ [Bower](http://bower.io/) package manager
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
+ Created an Angular module (gitUserSearchController.js), linking it to the HTML page. 
+ Set up a test environment using **Karma** as a test runner
+ Build an Angular Controller with accompanying unit test
+ Built out some mock search results in a static manner... 
+ ...then replaced them with Angular magic (2 way data binding) to dynamically render the search results on to the HTML page
+ We wired up the GitHub API to return the actual results from the API
+ Finally we added an auto-complete functionality to the search box so that it runs a search after a User has finished typing
   
####Lessons Learned

Github's API endpoint is heavily rate limited - and we broke it repeatedly! Its something I hadn't previous encountered but it's quite an important consideration when developing Apps using external API's
    
First time I'd heard the phrase 'Boilerplate' whilst setting up the testing environment. Time and again I'm seeing new phrases crop up that take a little bit of time to google and roughly understand. It's making my knowledge of the programming world slightly richer, and more concepts can be put into some kind of context - which wasn't the case before! 
    
**END**
