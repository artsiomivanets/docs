# 1.6.3 Components Diagram

![diagram](https://www.plantuml.com/plantuml/svg/0/jLPBSzem4BxxLwXS2jC4BZtrL9BG9XaIA8_9zEHPsufH8aiQIGvbEltlNSbFiEaXC-M2sCUtgzrlLtmr5hJDCnvyO2BcUKB9pbfblamc6lRZbDbT7kM6wbWAIuKTnpARGA8PY3UUgtno_VbooK7OxSDymi5IOr4KNgCrC47rMFq7x4n9uUmzTZ2V_bniD-7JtUOsdC--pnvlXgCWg3COCXL2aZ4HAX2KNv31EbUACwh9KceBd4oTbYoTTe3gLHuTY1Ha1OmRyedSIhjdcZhLb7EvDyJ3aGm4f9IO4Wt58Y6W91Csm-pCODGaSHCDamW1Ri121CQ3BQMngQRcnzpzMbk9Px87JNSIY-BH6cmcdgNEm38f47TzC9PcuUoN7T8mmpmHO7Rf3iHubKVq9u9-n52HC94IwaoE4XjQGDCDtezCKyoQ66PfNnLM568xVZ5EjzdHCev7jyxR0ASEkShjIkOY0NrmvIziUof_1V4hfaOAdy68_0u8VkeE3o5tn63FBFPNToqubdHIRRN9KSiGA_5EgS0ANXI7NFdQQXhBDweFH84nUwaJJFuuU5NzTkBJECQBsN-5RPg6eKkIr6qjM8BHKDy9M5iXs5DrxWrLQpqnFEPff8_cN1WlHf25--w5zveJpXrZk9w38qo8mojeN7QdHQJhMjuRecMvHigHErm1-XbYsWcbF5T2KCpLU7dN2rSnwJnCb8OlCZAbRQeTFyazIdhnLjXabb7FxwYnjs1UkmKrEwRyo3kcLETUs5fxKjm_GR2YlBEgMWpS8dSSmlrwyJYvtMoMQtJhy-cEp5dNZcbJepNr8v8oOxLNDhl3UTQ6zVfn3gOnybPD-XNbV2gZ4sMRzYs3bhZ7lHITuU5M9VXU57u4dpYR6n83vwwLLNPjNbK1bbBblFOiXZNlObLNQFf-9ezlrCOxWlvGHUqtz5lOSnUthDlKUtmSoUcC89bA_dTQwG2E1gK35XKJql7kPu9_hN3d9qKDzXhZ5vJsxy4KWTyeFWenbeKiLW-TfhuJe6p4ExrRb7a7Gl0Lw-F-Klm5)

**Level 2: Container diagram**

Once you understand how your system fits in to the overall IT environment, a really useful next step is to zoom-in to the system boundary with a Container diagram. A "container" is something like a server-side web application, single-page application, desktop application, mobile app, database schema, file system, etc. Essentially, a container is a separately runnable/deployable unit (e.g. a separate process space) that executes code or stores data.

The Container diagram shows the high-level shape of the software architecture and how responsibilities are distributed across it. It also shows the major technology choices and how the containers communicate with one another. It's a simple, high-level technology focussed diagram that is useful for software developers and support/operations staff alike.

**Scope**: A single software system.

**Primary elements**: Containers within the software system in scope.
Supporting elements: People and software systems directly connected to the containers.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.

**Notes**: This diagram says nothing about deployment scenarios, clustering, replication, failover, etc.