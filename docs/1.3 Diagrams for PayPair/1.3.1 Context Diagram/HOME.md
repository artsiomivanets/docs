# 1.3.1 Context Diagram

![diagram](https://www.plantuml.com/plantuml/svg/0/JL7DKi8m4BxtALPEE6fxyUH91ntGATYfPHnFpD8kD4v8QhAHuUtTb2ASqkn-lysZPtGSTZgvKgRMeI5ecJl_a6KEz-bMSHlMmPEhhM4odDPsbs7Z59fV7RgGJUxl2es6b_CyqyZaMKQhYQ1H6N9f5xMJ_EdhVLcjFb-hsIf_cRuidiVNILAGyzQCksw5pKwPMnWLU2XGENYAT-NP8LitaaK_0Bk14y8VFDDkT7qX4cCAT2b7Ju6kNy6-jR2NY1xOmZeSW9KZVojp8krXVG1jqOXKyXyxoXqTpg6YPXa4RHsKg8Hv0oLXpUctZxkgfI4LR0GYHifiZruWAMf7ZUBeSc6ZoJGIKjZvyIiAvL8yLXsMaLAIFZUyp5RIJ_0i0h-AzdB8ytJOjyEwfauwnsvHOv0O_lIbnXmDRYLaL1VYO0je6acnEIOOs2VEEVUKn6E0oVNjutsHpQgg-8Yn7mNMl_yV)

**Level 2: Container diagram**

Once you understand how your system fits in to the overall IT environment, a really useful next step is to zoom-in to the system boundary with a Container diagram. A "container" is something like a server-side web application, single-page application, desktop application, mobile app, database schema, file system, etc. Essentially, a container is a separately runnable/deployable unit (e.g. a separate process space) that executes code or stores data.

The Container diagram shows the high-level shape of the software architecture and how responsibilities are distributed across it. It also shows the major technology choices and how the containers communicate with one another. It's a simple, high-level technology focussed diagram that is useful for software developers and support/operations staff alike.

**Scope**: A single software system.

**Primary elements**: Containers within the software system in scope.
Supporting elements: People and software systems directly connected to the containers.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.

**Notes**: This diagram says nothing about deployment scenarios, clustering, replication, failover, etc.