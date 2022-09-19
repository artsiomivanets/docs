# 1.8.3 Components Diagram

![diagram](https://www.plantuml.com/plantuml/svg/0/jLPDSzCm4BtxLomv9GDj3d3YHDfqsZ9f4v9q64uPnLud0baoafnG6Fuxk_v8RUAK48PUgihxzkFjMstVEI-ipn8Ll90wL5c4iFO-TM_xVIksvolfrzaoSsX3eprgVnwQf2yYAuNUg2pD-fTlpYPAQFzmD-ehuT5vkbfSahMG6krv-Xzy9wdHR9_x3aQ3J-E7-UBZxVncCRgwlheVTdj1iCkWwyKYneNmuXLqvjAYM14MH9eg6GelZUxGXscsV0IZOIgaSl0IfYX2pnycrcnaX0w4KX1dEcI4KDAJUGn-ZV3aqnj07PrnIR2H0fRMREdSwJMp4L4YzI8L6bKZfG7VmuJlzrBYYu5Iv0zoE2H24mgCZT2wUeJXiXijoNf85I-5mxm8u_pAelimuhzctjYo8AbZanGaz8BPe_EOBAw--QwYEiWl6O-AKnv_SiirHpAEqNB2eSL8aZFN13k2hAoCE5JYmELVyi3v2M9ZWMsaNW4cL5qJBXBntMYEbnzWzhfAcWecqyhsmcGw4lQHAIrYDDYy4E4N2WA5TQS7FmAWdvrwkcdHsRpAINLk9PumIQPPBKJRbcGB9J_dCAE30ujVCr8dUR8OejmmknIQ8eJe7Frbc3AcgPa2AuN3FxX3eSkUvuQiBwASic3TIGlA2BtlDA61MjFKiEExwlndGP7pKbExvX_8MY79YWUg6g129tG9WzfbQqYQfD3Aj5HSUqCMeP9OvB_h2nHthJwRFU12TgtTYo4oVcbaN2R993HlMYCCqQCbagYJaeTUqc_Y3JHkQG8fjC-iPZbdnRWtOvhKau-nJqajTYD3t8_nEyHYQYoZfldXCB0i7me0E_eP15DKBMG-pVGr-agIF8n9ZI_w-duslk_VpEUJ6NbZLtd-BYc5kc-J6zLUsPggsntMREj3U8nzg_QE0Uut_Y2gpBzesxCLDrxo-jmzbr43T0nN3S2nX3L0VyrQ0tqaTJcsHa9RfkFbPmnfST3kgH0rivO7u3XWll1ePKV5kxkrqXUmOfqFQ6bla7PwIEiInjExPgDFHBUHUgAh6cidUlXtClQwVAAVwkdQhV7TSckevHszHlplsoy0)

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

