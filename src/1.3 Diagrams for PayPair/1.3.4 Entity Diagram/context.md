Entity diagram describes entities in the system and relations between them.

Merchant. This entity represents merchant account. It is company which use PayPaid. Each merchant has personal agreements with creditors, settings.

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