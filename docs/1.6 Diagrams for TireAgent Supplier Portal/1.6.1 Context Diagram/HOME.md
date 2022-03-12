# 1.6.1 Context Diagram

![diagram](https://www.plantuml.com/plantuml/svg/0/XLDBJyCm3BxtLvXT007hXHCd9fWOQC2qTKAS9jCQ6YbDgiHXsh_7sTQrOpnkYMD__XxAjMTq72gT72cJwr0GbCorlqfJXyl-X-8ol0LFBhU6oN0_jrMAXLDeFdMeGtfpUJ7HQ7Z-E4urCdcMqk96kb4PSlqwOYVZmUlpF5kyt6UZnNXuDtowFJbDaWavRys93pMv1HQLCkVGcyKR3E9DUNR8rlMal2w0VGTvhxMIbjewHjqxxS2i7xf8cyvVm12Q4S0yjy5m2qPLhUsAI9g7ssCSp9GZ_10VO5SL7JkrBOSDkIw9oOQkbARXRGNMmHILzd068yjBmLtZbmH-vPagO0ibcaAJj1P22Xn5VmjOIYOjSu5QegFIIaZ2fQN23TKjRHZ4oy7-mwqUPMUSzb7RbFH-G8SI7z78ejs3RzoKWobQTX5kYxQNqx-0nxwJJqHem_bnLaPHwwrjZOQE7J-4H4BqJvltb4JF7cRFJ-aeooQpxx8Qr6u0yxeGqCqAaIEVZeC_W4ckXSVwltm1)

<<<<<<< HEAD:docs/1.3 Diagrams for PayPair/1.3.4 Entity Diagram/HOME.md
# 1.3.4 Entity Diagram

Entity diagram describes entities in the system and relations between them.

Merchant. This entity represents merchant account. It is company which use PayPaid. Each merchant has personal agreements with creditors, settings.
=======
**Level 2: Container diagram**
>>>>>>> master:src/1.6 Diagrams for TireAgent Supplier Portal/1.6.1 Context Diagram/context.md

Admin. This entity represents an employee who manages customers (users), creditors, offers and approvals

MerchantLpConfiguration. This entity represents the provider setting and contains the personal credentials of each provider.

Setting. This entity represents merchant settings. This contains settings such as choosing an SMS service for sending a OTP code and setting up work with providers

Subscriber

Trending. This entity represents logs. This shows whith screens user visit and where user close PayPair.

User. This entity represents the end-user in the system.

NewUser. This entity was creating for analytics. This also represents end-user but with needed data for analytics.

ApplicationRequest. This entity represents loan request from user to PayPair system.

LeaseApplication. This entity represents responses form providers. It shows whether the provider approved the loan request or not, information about payment schedule. It is also updated if the user took advantage of the offer or if the user after a while did cancel, refund or settle.

OrderItem. This entity represents user's cart. It contains product information.

RefundedItem. This entity represents items whith was refunded.