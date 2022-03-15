# 1.4.3 Components Diagram

![diagram](https://www.plantuml.com/plantuml/svg/0/jLPBSzem4BxxLsov5AO9N7hggIHXccH8e3ocqvD7jXMZH9PSIGvbEltlNSbFOgKFPie5eTtzzjlTJn8VjI7A51aFtZ0HyoAXi3Ccrnyc4qNsuvIPNH4LcgfO2aE56SSocv14CIAUUP4NayltvqjEXDdUpIUS6AeDReMNw4sOe6gS_mViB9V2-ZliO3xzkjXkmYytc-jmFliqkxyQZeAWOJ1aUKYIZ8am9uBoCnZS22oQSwfWAHMkO6hDiBJc0TfNHNG0AM156DVm3gwbsJD5hMdAkTnhS7YG4K5I2go6mtsH0Cab4oP3VdemQcbSHSCaGeGhOaX4j4DRIcrIHVNdkVsrDXBN6Dy2EC0EFXCFKcN4C2aGUttGXcRXxBiPqZ13iWWoExSBqCxaKDqAC0uq5GaJAL3hSaHkQ0YwRh18cAQO63GprDUA5IMn6JzgQzliQ9N7eHiRhGcd5hdcTY4BaH1ri4CeVNtzlo3n4tA3CcWmWXy1uASPz90KLX_iWSMkTZk8uvqUrywmhC8q68b5fG9RU5OkYjnrLz5OFbDrW9nelPSgGVOlahS3iQ3jBs_ITRoZIS5fCpV7JuDy00Id2WssKxgNfXdpKOUcSOmjDB-hhwCFBB8IPLT5lLIE208ixBSNUYdpmfwu1D1WTK4QMLHTAwrxFCCj0I0LsvS9TTMKJd_-kQ8QemTkQdeXtYE2nfL2Ecg-RFRz8qFjQIpfMu4tZ4lPnlQoSTbeS2x_B3vlAJL63pnAmqSPQGotHo9LzlJ0BUvuKwomrIoZxlH5hRyX-idE_6SGh2ZlNN_7Sjvgwh1krulxoVLcirnZf2-iAy-_3kgVsrT3UwvjB-nyS3mfqqOvOtk3sSZ6iRa4ou4sJYMrbdz7ZOxEwAL3VJxyreu2_0wU3bSrTWr-5bNgLo4g-okQxpZwFTmzlyqJFBnbbMyr86zJwAEZN7PPvhMwZwOL-EVbNZTy7vBorTehl2jAcRgtOueCdYa-837cXSNgpjUJ4p4wlJyHeHt6YG3LN4wCRYLr0a3m4ULk_mdz0W00)

**Level 2: Container diagram**

Once you understand how your system fits in to the overall IT environment, a really useful next step is to zoom-in to the system boundary with a Container diagram. A "container" is something like a server-side web application, single-page application, desktop application, mobile app, database schema, file system, etc. Essentially, a container is a separately runnable/deployable unit (e.g. a separate process space) that executes code or stores data.

The Container diagram shows the high-level shape of the software architecture and how responsibilities are distributed across it. It also shows the major technology choices and how the containers communicate with one another. It's a simple, high-level technology focussed diagram that is useful for software developers and support/operations staff alike.

**Scope**: A single software system.

**Primary elements**: Containers within the software system in scope.
Supporting elements: People and software systems directly connected to the containers.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.

**Notes**: This diagram says nothing about deployment scenarios, clustering, replication, failover, etc.