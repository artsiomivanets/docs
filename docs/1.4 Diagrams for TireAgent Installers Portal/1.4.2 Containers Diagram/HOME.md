# 1.4.2 Containers Diagram

![diagram](https://www.plantuml.com/plantuml/svg/0/bLHDZzem4BtdLqov5DIMN7hgQTa5TRU29IMWggTeaXXmwzYMxO1GrV_UiGE4B71eJlwOz-RDp8iVh4FZwaf4xxWiH5qos3gdxPSuDhWVRhZRrdbjcIcKT4owOQ6g64l3KUv4hUluwVEdHA1qgzaq5kYOTNIKFL4qSidCK7lkQ3hwELyjinylo-TiElawUHtt1r6KC6ELxDjQCvDXMN7v4Ngfty78xxXr1fqoFJeE1w3My299iX0KaoX3gzxWnCDFDsUkDlO-tna5M1IgbgubP9KMwi0OXK-EImzTSiDWjA5km2c2CEUI-mwxGPQxW5lK-G6KWGLoOU43B1WMRlZB1iuj0tkmZbMmfX3dqHO5iyGSfU4YUoHr9Pf3N-kiYUsKsBG3ck3U0Fv4G5yhY-iiPnbgVGlrYCLl9iihcVuWCMh7IsQlMW_hMXQEAuc2kmFiECAtTFuQFo-NIKh2h_A7kMGQ9HEtH3GpIVprJI4Z8TJUGc01RqhILA743GCgIt7fAkgtVPjvdFVBdE1ZT9YZ3RD8b7KRmd-V-brAfY2kIn90MRRUiBIakLJegoN-lr6qOABhtAlwPesq2vAZmxn23xyox1qAstAyjzIHahYE5Ar5xwKdM1TouOFG5h9XsPIxD-JKqEd6eYCQxewHJmiYWFbYrZ9qKbqwQsNPAP7_3owlKZBOKGhiwM4vLHMQ2ag7tb9SnqDl58T_QwLBUcaQAce8aRZwFoYZ1nBYdwL_)

**Level 2: Container diagram**

Once you understand how your system fits in to the overall IT environment, a really useful next step is to zoom-in to the system boundary with a Container diagram. A "container" is something like a server-side web application, single-page application, desktop application, mobile app, database schema, file system, etc. Essentially, a container is a separately runnable/deployable unit (e.g. a separate process space) that executes code or stores data.

The Container diagram shows the high-level shape of the software architecture and how responsibilities are distributed across it. It also shows the major technology choices and how the containers communicate with one another. It's a simple, high-level technology focussed diagram that is useful for software developers and support/operations staff alike.

**Scope**: A single software system.

**Primary elements**: Containers within the software system in scope.
Supporting elements: People and software systems directly connected to the containers.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.

**Notes**: This diagram says nothing about deployment scenarios, clustering, replication, failover, etc.