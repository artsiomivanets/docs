# 1.3.3 Components Diagram

![diagram](https://www.plantuml.com/plantuml/svg/0/jLPDSzem4BtpAxPSIgO97DfJJo4Vau-1G36PJ4-Ci1UYL9PSIORIJlzxLn8sTd0oD9rooRBiUxlxTYNbr5YcRPwArZikOv4d28_MPkPphwVPkhlazZ6VvmPrhAH5QRknIdiiqPp9bSYpl7V-wMGicBJtmq5FC8l6acjsJj6CIzJTx3zmfvcIBjvpjmRzhwFxwUpXPdez6rnUNTvTT8vQhRA2JfRD5ZXZMNOCxJ7RZ1dNyC2J9TesUIR8OjjzCiuUQxNY2HfWGi0Ybx7bIZB1xGRK0kmZGe6t2b0c9wvuM746SwtMPBUFwdbPad8vovX4KKdUTrwY8g-l89yJluO9uyB01xYDdBSl1562Pu2KIRP4SEd89HCgPq5cDTt5l9FC2NV1B9ipWxuVPUnIe_aoSDyYgyZs9C3bGgNCjNViRHs-4FbSvJR4QFoUa-GXOHQaqU_DBdUqCHRJsUKFsn6a1Zafoo1OleNnZTCjuGv0yu9OOyAfYcTWapfWb1emtkcBzHPGPM28qK0qZEeebhAVhlnstniGVIoQ9Aaej8WzKxbCcDwuUGJ-oYZEMFoDw274je_WLmleKwvOf-ZRxDOZD5URcdCG9iqbZzsUmffs6xQYT27o7HHw7fCL8rzXgMoCnc15s7e9VkgKuDwyb7gxAs4zQ3L9Pwh2BIorA1IJ-wGfdRf7EbgEU5ZOhv67HIJoxIwM4t-XQe6qXExK2IU9sos_7EI4ViNPc9AEOAnvvWBsU8k1p6B1CTHVpWM2hv6pFWFNI3dQlHmiTzSHNsoBT2BKFOqPBj2Y9f5eajpT5fp-acuWSUtYDDfSIowNVavxELLcYMDaCzeMlU8nxkTu3j6OAMtz7UQCbu7RzY407D7lLck2ea7CtK6-Gbkif3k6QKKl-lKs6jtrhgVJiJkLZihN7quoBUf-JCYtkuehMzrCM8cj7i93uXjtxn3W_k1VH6th3sDxjUFQ8r0zTwzLL0CTebKDSAXWDT1VgrP37oYTnrP4QAfqD7_2c5uBUeLB6NTX3HV0OK3_FD9pduHxTwsv3R3myFRfjLyXJ31MEe7HP5WVz1lHJQA-aQgYsXiP_bsClIc_aQUukif7l7pSQjjoIhUH-n_l3m00)

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
