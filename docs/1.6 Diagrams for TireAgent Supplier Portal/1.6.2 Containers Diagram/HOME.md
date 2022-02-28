# 1.6.2 Containers Diagram

![diagram](https://www.plantuml.com/plantuml/svg/0/XPHDRzim38Rl_XLSBaknBhdij5FJ9bWtfAsN3mmx6OpD9jfaIP3e1C6m_pxAJckxQR6SOeby-8fyfQl0wBagTV9EcLnN1S6EsONFux77msYhU5Tjga0-juR9y2YtvHWBhz3iTUMgySsdZwb6m-kx-LWZKs1Pocua6fKXFtAHdSmdFn_Mg-p7rzLjDfzzcTrFXnT9af8FrWn3vSXdM9JANC9W6RzW4hzKO8zi_K2MwmMmZo3xJYi9IQrdr8EB3gRUw9AQo3TW24yfW7bkAyCjZ4gdxP58WcUdlp5nfJp1P2kDWAS8oNa-xP2n7nGKrtcBQdC4ws61IWVu00l2d4U_GitS4OHZO2hXKK8uPWVK58ISBEkDx5hK5UYFG-Uo9hPxlgOJqCGEBk1F0l9hLIcNRIX3vrv9kiRyDvdYJ6HSIBtTguB2ovx3OsLoLjQWLdo4lKBujdou7z-kLkbIL9zLhoUIEJIaNv7GJ2EDkw_rwjRoGNfIpqrhUmXGuw14WrkIo496TWa7zBIpObNPDyNpQCDBFTFDiDW8QugC6mmrDxM1jvx2ztdyMefBXF8_C2WZyoenDaAA_4sI1Uc-cS-EVjTeRXadupNejfBmJh2UfT_WXMVW-oVP9q1huxUaeDRzb8vPwZw9LOkJF2zkhetHZ6OY7jYJU3aN03mixbf2hrJNVklsSF6kz9mfDZn90K_nBP6IylvqRcctHr57ptKlnDTNSUqAuJHKwOqyTbo5iypaIah7T-eV)

**Level 2: Container diagram**

Once you understand how your system fits in to the overall IT environment, a really useful next step is to zoom-in to the system boundary with a Container diagram. A "container" is something like a server-side web application, single-page application, desktop application, mobile app, database schema, file system, etc. Essentially, a container is a separately runnable/deployable unit (e.g. a separate process space) that executes code or stores data.

The Container diagram shows the high-level shape of the software architecture and how responsibilities are distributed across it. It also shows the major technology choices and how the containers communicate with one another. It's a simple, high-level technology focussed diagram that is useful for software developers and support/operations staff alike.

**Scope**: A single software system.

**Primary elements**: Containers within the software system in scope.
Supporting elements: People and software systems directly connected to the containers.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.

**Notes**: This diagram says nothing about deployment scenarios, clustering, replication, failover, etc.