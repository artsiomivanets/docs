# 1.3.3 Components Diagram

![diagram](https://www.plantuml.com/plantuml/svg/0/jLPDSzem4BtxLsov5AO9N7hggIHayZ4GA2QJwSaZsmiebMLNag6PJlzxLn8VTkraQ3hb4h7iUxlxTbVAPssOCcKcWdTS9g9C4TR65FhJOA3Ojh_YPbt6fKQLvDAWDFqapmOiLPp9ZIYBSd3vyNmcc3GFa_50C8FQa2cw96_69Qf-yH-uioANrjzn1-FXr-d38dgyNTn4uwlhg_jHjnS4XmowHH4jCM95SGQT6NkUCQxWaQShD1sop94bfl-axNccyWrFKGCJ0fQbJ0pF9HFSF4E-1BD6sEDD3YZJSviyR3Y3MELREdTwzRWipRYC2YPHL88FhPMeoEeoA6FYLp1dN6Zu07UXjGw584fm390noLO8DXoPP4hfBEbO3JUAksbCk14pB6OQNJsvDYk5-ilOVWjDJcT70bmkyupPyixSMValH1xdfV4-2h-N9BaFM7Xfr7jzZ1q-QuDPTFN3T0MfGKQAClOdLyBirkgMSWkWVa6YCEMKnHzWdLbWc6dGpkYITIUWp40JeuPm4X9g3xl8IvaozMn5zg2AlXSi-KOOyBwT7lmCW3w7kUdkYz77dlkCQwsm1i9afUI97JxOqi32hj8-X2wjlKXdT4gGR_0WLu9QOqMjUWgkbHJWGRyKUZS0lkSqRoGUPM6da4eKEPDDqenMQKtxOead-_Dhv7wwY7mtO8Sslf2rG9eikqh2Ic87ndMSZCEAhJKYhLMYU64T6hJxVaI9uEZJFxG5lAsLizu2MyUXiuqOhBHN35_kahGQr2sj4KPeK956r4XkRm1EVqasaBYrVWfDgIINAzUcHioyCCGnDGKDYzhm19inUi6l89YZQD7Wk5FNQFQ3P3SYgvH9lzw5q_l1pM8nimjYgLnOlrGqNaqV7-zuArPciPsmubjTdLFyMoVc562pNo-Y6gvUzrThhztCrRrvBRSQw1JLQe1JfQk1_bg_6lf44Hss8a9RfjFu2HEwmkbfFCXuT6lPuDE0xisYDpZrz-PMSUDX_ZKSqXEyGPXZagiKflF9hj2T-6z4judwHggAQcza-3SnFjCbOVyB-Wq0)

**Level 2: Container diagram**

Once you understand how your system fits in to the overall IT environment, a really useful next step is to zoom-in to the system boundary with a Container diagram. A "container" is something like a server-side web application, single-page application, desktop application, mobile app, database schema, file system, etc. Essentially, a container is a separately runnable/deployable unit (e.g. a separate process space) that executes code or stores data.

The Container diagram shows the high-level shape of the software architecture and how responsibilities are distributed across it. It also shows the major technology choices and how the containers communicate with one another. It's a simple, high-level technology focussed diagram that is useful for software developers and support/operations staff alike.

**Scope**: A single software system.

**Primary elements**: Containers within the software system in scope.
Supporting elements: People and software systems directly connected to the containers.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.

**Notes**: This diagram says nothing about deployment scenarios, clustering, replication, failover, etc.