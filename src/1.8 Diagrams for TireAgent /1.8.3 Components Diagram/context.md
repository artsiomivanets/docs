Tireagnet application is a monolith application based on Ruby/Ruby on Rails/Solidus. Solidus framework is used under the hood. It allows to start developing the main features fast without being distructed to e-commerce components. Authentication/Authorization/Admin panel included into Solidus framework.

Tireagnet application consists of the following parts:

Admin panel Autentification (Solidus). This module is responsible for Admin sign-in/sign up (based on Device)

Admin panel Authorization (Solidus). This module is responsible to assign different roles to Admins (based on CanCanCan)

User (Solidus). This module is responsible for managing users.

Role (Solidus). This module is responsible for managing roles for users.

Order (Solidus). This module is responsible for managing orders made by clients.

Shipment (Solidus). This module is responsible for managing shipments data.

Fulfillment (Solidus). This module is responsible for displaying available suppliers+warehouses to supply current product in the cart.

Order (Solidus). This module is responsible for managing orders made by clients.

Product (Solidus). This module is responsible for managing products available for clients.

Promotions (Solidus). This module is responsible for discounts available for clients.

Payments (Solidus). This module is responsible for managing payments like refund/capture/void payment.

Warehouses (Ruby on Rails). This module is responsible for all available warehouses for Tireagnet system.

