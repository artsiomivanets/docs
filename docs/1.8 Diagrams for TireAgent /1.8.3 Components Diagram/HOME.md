# 1.8.3 Components Diagram

![diagram](https://www.plantuml.com/plantuml/svg/0/jPNDSjem483lVeej9pEJmg4zzPGqeKqx950Ca-c9MUm5D9KbZoIJk9s-UrUoSI2OJ7keJ-lz-IIjTbUNrg5nPIwZDqAbiim8jiuLziDmQF1ni15kMwvAIoRLof5oWrJdGyoCGBMJPL4Ehz-_dKfKRd4t7afqP1shbjViZKAH6HJ_WPqNMdd_m8x6LzydY_douSlyTZaUVHxTtyJzA6ft4DkoAAGWiooqSIWle9Sq6fW6JOzLit9LWLOmGo6jLqoDtecCBA2KW3jMuqeI11W9Os6j3So58TpmLdhzvmLlLd6sOi8DEboXfK3JrcqCsMzZ_vSuRHgoK6kTenDQCIAfhADyENfoSO5LWSBuKAocBFcuiKPbeQXtPeu3_kgKBrN715BPneYC_KOvdnTii8Mu887Ju9s0yf2besZCyQTMx7iL14ZUxK_A2NhXAYLNdIFlt8Z0wNQKXZom-W6DuNklZkFeYQiaR2y8vsFsGHzrgJ8qLUnmMH-6_TexWzghruTV4V3NrbMi3QVNikya29trKPiWHuKReJQywZ73RaMHi-0noLxk9BNMyp2kXZrhseZTHTiOpvFMfLmBAVUqJmU_dSG3X_FGHpIqrTp9jhw7vgSJM9jjIQyTr-YiJElZDkAv7Wr6m2mN2WfK94ylWfpZHS8zD6BtDJJ6qDYeAk1WuOAFstBZ2qSdR4E-spnwHaKGEz6psWsuwiYWwpgo7uEUix3d2YvO3dFsEufc90zhk-t1C620ByxVIBj9aNFT1zRNP78_l9tFfmbpNa32xAe16Kymxtx5JROZc57AdG7nP7RNR-AEo-bq1l41yrA9D4muFp-Q00Wj5b9j2qh5MgHjTES6zorvCAGI5ZaJpJJokUBtWuUpps_DvyEGv9sR2loKAIsaMrIR4EJImSMhAnrCgMkU686wru5_iGoc3iGQ5556sQkiTdArf5hphvpdL-4EVtYCv1V1fvKD8Pd1yGHnoKlvf_8F)

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

