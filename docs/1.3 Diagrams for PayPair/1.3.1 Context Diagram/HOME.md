# 1.3.1 Context Diagram

![diagram](https://www.plantuml.com/plantuml/svg/0/bL9DJ-Cm4BtdLmmzWM2R2oTEL2o2HG6YD1NYL4sJQUkLQmVFcAh_dd4QQE76AOxdVVdPromO96viTc9SOsDBi1Rf-2hF0sx7AoFhk8XCeV5EoCcuyPiSss3GlTlOnVpcyazfqSdiiSWj2h7erln6qMWSXN6NjBDYyleyg-Sl_-hxUN5xT_lqz_GioqeAxDrfrysntHXt0QCIToMQ09FqRrW2YWyZ7VGRu9VmYU0T2sr6PqSYAQP2P_hfAT3r8zYkFMmr8eDuMCGTY0d45xfFP1aMEx0UdKfbNx6JtDxX42ffLb7HFa25HfddK14sClxFQLQlQKW5IuMeaN6hlHTeYYPGQqHT3YQ2YQO0cAoqMs0Zz4kN90-CblXxVakkrTCheTYl4hVGHbE7mp0nAh9zZEFpJdKCgKn0NJJwFg15mQJmC7r-ok_hkfmgEN6_QZyMgEWjigZvkw6jVlJDTDXNZar3dLv4AfmF4iFr7siyeiELDfVKbJX4xXFvvNAVVc1_SWvdlYFr660_KsVN2akFyWC0)

**Level 2: Container diagram**

Once you understand how your system fits in to the overall IT environment, a really useful next step is to zoom-in to the system boundary with a Container diagram. A "container" is something like a server-side web application, single-page application, desktop application, mobile app, database schema, file system, etc. Essentially, a container is a separately runnable/deployable unit (e.g. a separate process space) that executes code or stores data.

The Container diagram shows the high-level shape of the software architecture and how responsibilities are distributed across it. It also shows the major technology choices and how the containers communicate with one another. It's a simple, high-level technology focussed diagram that is useful for software developers and support/operations staff alike.

**Scope**: A single software system.

**Primary elements**: Containers within the software system in scope.
Supporting elements: People and software systems directly connected to the containers.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.

**Notes**: This diagram says nothing about deployment scenarios, clustering, replication, failover, etc.