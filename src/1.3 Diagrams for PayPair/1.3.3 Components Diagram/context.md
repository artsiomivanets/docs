API application is a monolith application based on Ruby/Ruby on Rails. API application can be divided into two parts: Admin Panel and Backend Part. Backend logic is separated using [Interactors](https://github.com/collectiveidea/interactor). It means that the functionality of the system is divided into related parts according to the [High cohesion and low coupling](https://enterprisecraftsmanship.com/posts/cohesion-coupling-difference/) principle (the same principles are followed by microservices architecture pattern).

API application consists of the following parts:

Autentification (Ruby on Rails). This module is responsible for Admin sign-in/sign up. [JSON Web Token](https://en.wikipedia.org/wiki/JSON_Web_Token) will be Admin for user authentication purposes.

User (Ruby on Rails). This module is responsible for user creating, searching existing users, checking previous approvals, authorizing etc.

Otp Service (Ruby on Rails). This module is responsible for sending OTP code to users by SMS. Module can use two sms providers. These providers are managed by the administrator.

Providers (Ruby on Rails). This module is responsible for building requests to lenders, response This module is responsible for, creating offers data. ect.

Merchants (Ruby on Rails). This module is responsible for Admin functionality - creating admins, managing providers, checking offers and users, ect.

Providers client (Ruby on Rails). This module is responsible for sending requests to providers.

Lease Applications (Ruby on Rails). This module is responsible for storing users requests, calculating taxes.

Report Service (Ruby on Rails). This module is responsible for creating different reports -  new users report, approved offers report, ect.
