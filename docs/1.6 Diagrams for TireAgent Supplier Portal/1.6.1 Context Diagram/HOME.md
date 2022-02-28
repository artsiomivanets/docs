# 1.6.1 Context Diagram

![diagram](https://www.plantuml.com/plantuml/svg/0/XLDBJyCm3BxtLvXT007hXHCd9fWOQC2qTKAS9jCQ6YbDgiHXsh_7sTQrOpnkYMD__XxAjMTq72gT72cJwr0GbCorlqfJXyl-X-8ol0LFBhU6oN0_jrMAXLDeFdMeGtfpUJ7HQ7Z-E4urCdcMqk96kb4PSlqwOYVZmUlpF5kyt6UZnNXuDtowFJbDaWavRys93pMv1HQLCkVGcyKR3E9DUNR8rlMal2w0VGTvhxMIbjewHjqxxS2i7xf8cyvVm12Q4S0yjy5m2qPLhUsAI9g7ssCSp9GZ_10VO5SL7JkrBOSDkIw9oOQkbARXRGNMmHILzd068yjBmLtZbmH-vPagO0ibcaAJj1P22Xn5VmjOIYOjSu5QegFIIaZ2fQN23TKjRHZ4oy7-mwqUPMUSzb7RbFH-G8SI7z78ejs3RzoKWobQTX5kYxQNqx-0nxwJJqHem_bnLaPHwwrjZOQE7J-4H4BqJvltb4JF7cRFJ-aeooQpxx8Qr6u0yxeGqCqAaIEVZeC_W4ckXSVwltm1)

**Level 2: Container diagram**

Once you understand how your system fits in to the overall IT environment, a really useful next step is to zoom-in to the system boundary with a Container diagram. A "container" is something like a server-side web application, single-page application, desktop application, mobile app, database schema, file system, etc. Essentially, a container is a separately runnable/deployable unit (e.g. a separate process space) that executes code or stores data.

The Container diagram shows the high-level shape of the software architecture and how responsibilities are distributed across it. It also shows the major technology choices and how the containers communicate with one another. It's a simple, high-level technology focussed diagram that is useful for software developers and support/operations staff alike.

**Scope**: A single software system.

**Primary elements**: Containers within the software system in scope.
Supporting elements: People and software systems directly connected to the containers.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.

**Notes**: This diagram says nothing about deployment scenarios, clustering, replication, failover, etc.