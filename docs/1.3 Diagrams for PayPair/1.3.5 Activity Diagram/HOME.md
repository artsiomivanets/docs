# 1.3.5 Activity Diagram

According to the flow, the process of obtaining a loan will be as follows:

1. On the Tire Agent side, the User clicks on payment with PayPair. Tire Agent sends user info and cart info to PayPair.
2. Widget opens with phone input field
3. User enters phone number
4. Backend gets phone, generate OPT code and send this code to User by SMS.
5. Widget renders OPT input field.
6. User enters OPT code. Widget sends request to Backend.
7. Backend validate OTP code.
8. Widget renders Application Details form.
9. User enters Date of birth, Gross monthly income, How often do you get paid, info about paycheck dates and SNN/ITIN.
10. Frontend part adds to this data user info from Tire Agent and security keys (BlackBoxID, TevId, ThrtMetrixId, ect).
11. Backend builds payload and sends requests to active providers in [Parallel](https://github.com/grosser/parallel)
12. Each provider processes the request and returns a decision.
13. Backend processes responses from providers and returns this data to Widget.
14. Widget processes provider's offers and shows for User in user frindly format.
15. User checks all available offers, can compare and choose one of them.
16. Widget sends selected offer to Backend.
17. Backend sends request to the selected provider.
18. Provider returns payment URL.
19. Backend sends this URL to Widget.
20. Widget puts this link in Iframe.
21. User fills needed data like card info, personal documents data (depends on provider).
22. Widget gets callback from provider that User successfully completed the contract signing process. Sends request to Backend.
23. Backend updates offer status.
24. Widget shows a message about the successful signing of the contract.
