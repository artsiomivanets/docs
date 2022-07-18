# 1.8.3 Components Diagram

![diagram](https://www.plantuml.com/plantuml/svg/0/jLLDRzim3BtxLt0zfLYRN7RQQMaQh2tIDii7YfqCscOTjRPaI7AoODX_7oNdmuuT32Ymd1I9VAJUUwA_6OlQbdaMV18opig4O6LjORuE1Xet_LJOLHcLXdIif2Lf-x7A1vXeWNATbKKv67svdcOexV9nCiZGah6y5Ouu6eKatI_-0tPUAEdYFNOm6VvyNYx2b_l5NJWPVny_tVOkW-3GGKyKOO9c5IdKoHLSlA2cbUAoC5NQOdR1UxCoseAIC4EH6VWCCyBOzj-CEnjccTeOS7qQo55YId0lrrnVwIqifR3cul9OxZRg9H6dtQB520qvYAaoDjLaVapSlpadaZd509G9p5UYo7dNW92lIkTeXPACFjyQItau_cLx5ERS9CEChzq2Z3_ok7u5d0U6P29a2kH26ktrB7BeGcY2OSgLm0XB_w9WiQ9T7OzkNRR1Z1polhSRLSe4zTRHNSLsS0qt6B-JksZLzINy3e1_1qbxM3edY5SH-xix_fixhLvR6bd5bqebKtXLBSh2awifLcjYlWiqPgDqmjqtYukz9679aZ1kKwFEqiqGhvklvYJbjsLBqrL6YPYgPBSw1-pEGEJik1Q6qm2TW24_7adnZgoQiAF3VYTyBNBE5c0xMjAl6BTB5Lww40lXc9xUTyBjXJqF4wNXcuhCBZRLpY_mm3kTUBEIDS_9-oqwnbiqxsr2DtkRrItN2NiqPFE1_Gc26MKdew8EkpJa0Hxcpq-3kyLYEkUiTahRlcSJMw57WkRCf66_fi9OxK-FBzcb7Y8Fmw3AE0HLdPsu-MWxtrC5LRjZo_sriDEpC_PR5WcFQU2tHNhdVeWnovo2-xRgTcgL736ifSxPM5ROTaL27r-MX-pknaywxqUUP6uQRlY30wU-PuFiFDrIo04qpDy2YohNjxAx1VRV1PwhINMXZURwbTdzp1qoy9fuyCRC7ppF7izm_q6Ocj8VG0Y-yJtTv_Ol)

API application is a monolith application based on Ruby/Ruby on Rails. Backend logic is separated using [Interactors](https://github.com/collectiveidea/interactor). It means that the functionality of the system is divided into related parts according to the [High cohesion and low coupling](https://enterprisecraftsmanship.com/posts/cohesion-coupling-difference/) principle (the same principles are followed by microservices architecture pattern).

API application consists of the following parts:

Autentification (Ruby on Rails). This module is responsible for User sign-in/sign up. [JSON Web Token](https://en.wikipedia.org/wiki/JSON_Web_Token) will be User for user authentication purposes.

User (Ruby on Rails). This module is responsible for user and admin creating, authorizing etc.

Warehouse (Ruby on Rails). This module is responsible for storing information about warehouse and having Inventory Units.

Inventory Units (Ruby on Rails). This module is responsible for storing information about units and their states.

Invoice (Ruby on Rails). This module is responsible for storing invoice information for inventory units.

Dashboard application is builded over [ReactJS](https://reactjs.org/) library.
