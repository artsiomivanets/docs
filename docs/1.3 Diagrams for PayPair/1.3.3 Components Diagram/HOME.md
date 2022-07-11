# 1.3.3 Components Diagram

![diagram](https://www.plantuml.com/plantuml/svg/0/jLPBSnen3BxpArGk9TC43ksffv37v34GA4icqnDZTWLnwhMtjXTAE_tlbMrssGsR34sdN2A4z4dw95avDPPfcwUYzOxBMEG9mgErcVdSwscsxYwvVSpdkK4TAsbHscwiqXvBD6To9V8ixvr_EXaB9ktzSD0JpAAnf9gTapNZ4dKt-m_OQQQai_VOhK7_w-X-EdkucLxF1fTNbtSNdQDMgyoWasMp1SvObXr3UymsOyOrFF1aYRPDcWcos7QVZ9F7MgruWWQO4B38PMovaanmkm6r0Fk8KFXR1IYJ4vSyh3Y3kLPhajj7zRWiIRcSPKoYg0JlEor1aTPdaCy9NyA4SM7W0zn6JjiNWY318q3A95iYk72aaWcbio2n6kvYtadcv7V1B9ipWxuUPUnIe_aoSDyYgqZs8C3bGgNCbNViPHs-4FXSvJROQFoU4-KXO1QeqU_DBdQqCHRJsUKFsn741YafoY18leJnZUCjuSw1-WMnneHJ5i-SJUeSezI0yKgVh9U0CWD3Y0QYOLJtOYdxwT9lzxq0qSUYIAAAJ0lRCvNBXEcDwqV0hxJYZCNV21w2RVi8VhM0FkM8TOgwpMuyGd6rhZa5-QIvvB6RKrZJRCEMb2v4leA2psEIOkGhB9cDqHYi45jFmNUT0joRbq9lPoMC1uqcyKnPk86b4eLYSXyqfQrxfDLomCD2VWqy32A1RsUnxFWBMGka8NHR9nmbRhRyS90I-XLbOqXQmLZpp1diuHODcSM2OyY_x0i4NIDclGUkaBArUp5OxfuZljWcwKYeQneZNA15JIHH9xbxBJZz9Tv0uXgKMoURQydbqlTfBwRAB66CR4RJebSynlqOprqqPafR_uOvuMN7RVaG71pGxrPhWgA1pDqYNw4jHjAjOLhXYtwzZKPtlUlfTEosqa7v_CCcqw3ksuHukwUuCjNDW1NRwX8UOjyuUuSuxZV-HQzj_g5jhrPSEmBLlNijevhJ8LpL70ubhERqrwpLl0-apljMI6ZAT3H_mfYk1LtXaiQTMSC3S9YZFuzqxfFmxgurjy4j7Du-NViLmWHZfHCOJORrHh_HkudKDq9LM7iZmh-JiTVbD-8KJrTvnClZLfkMKtgDtFzuVm00)

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
