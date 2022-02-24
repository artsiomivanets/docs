# 1.4.1 Context Diagram

![diagram](https://www.plantuml.com/plantuml/svg/0/bPDDRzim343l_XLSBcknBhxij5E3DbWxf6sG3mmx1QpD9XfaIH2f5VdtevmuRf0KGq-MAFBfcQQlMJ1AQcpnoRZAfffW8nBuUrb6V1skZMpISsAAbNT2JeQLRqgieq7trwQGofjlNwSMdImV9gL58HODhMuq6usZE0oPNKn6lv-MYzMl-yNTQZB-CNwylRWiYYb5zkw2Kw2umhenxWe6yxo3KTuPbeZYuq33RG3y2zmxLRPMSuAFkXfSTXpJdHnOVUxxl4CLO5NvvAG7KXEitn9f-dY_pAKB4mb6Q-q6T1bQKnpU-Ot8Jl78P6-jiLbwteAFC4DZkGLl27ZBGWsyQ9oh3TN96hU-WWOThdK5wEfEkTs6u8sJHcLO9Ne7mMDJDa8dby8Nc15MClnpxdx9rOoMChcOaMsXPrvkJYhbOwrTWrUTc2u7nNZjSSYFpFyvVteixnQBwLo1cNVAQhMNeTP9sX4_CsYEf0-GTwv7KtL6-Y5tbFeJxhu_dyZz3yBzaUhk6h67z2Fqle96-wBYMfkP_vb_)

**Level 2: Container diagram**

Once you understand how your system fits in to the overall IT environment, a really useful next step is to zoom-in to the system boundary with a Container diagram. A "container" is something like a server-side web application, single-page application, desktop application, mobile app, database schema, file system, etc. Essentially, a container is a separately runnable/deployable unit (e.g. a separate process space) that executes code or stores data.

The Container diagram shows the high-level shape of the software architecture and how responsibilities are distributed across it. It also shows the major technology choices and how the containers communicate with one another. It's a simple, high-level technology focussed diagram that is useful for software developers and support/operations staff alike.

**Scope**: A single software system.

**Primary elements**: Containers within the software system in scope.
Supporting elements: People and software systems directly connected to the containers.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.

**Notes**: This diagram says nothing about deployment scenarios, clustering, replication, failover, etc.