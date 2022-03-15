API application is a monolith application based on Ruby/Ruby on Rails. Backend logic is separated using [Interactors](https://github.com/collectiveidea/interactor). It means that the functionality of the system is divided into related parts according to the [High cohesion and low coupling](https://enterprisecraftsmanship.com/posts/cohesion-coupling-difference/) principle (the same principles are followed by microservices architecture pattern).

API application consists of the following parts:

Autentification (Ruby on Rails). This module is responsible for User sign-in/sign up. [JSON Web Token](https://en.wikipedia.org/wiki/JSON_Web_Token) will be User for user authentication purposes.

User (Ruby on Rails). This module is responsible for user and admin creating, authorizing etc.

Warehouse (Ruby on Rails). This module is responsible for storing information about warehouse and having Inventory Units.

Inventory Units (Ruby on Rails). This module is responsible for storing information about units and their states.

Invoice (Ruby on Rails). This module is responsible for storing invoice information for inventory units.

Dashboard application is builded over [ReactJS](https://reactjs.org/) library.
