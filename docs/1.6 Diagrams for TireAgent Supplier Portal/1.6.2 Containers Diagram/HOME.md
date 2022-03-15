# 1.6.2 Containers Diagram

![diagram](https://www.plantuml.com/plantuml/svg/0/XPHDRzim38Rl_XLSBaknBhdij5FJ9bWtfAsN3mmx6OpD9jfaIP3e1C6m_pxAJckxQR6SOeby-8fyfQl0wBagTV9EcLnN1S6EsONFux77msYhU5Tjga0-juR9y2YtvHWBhz3iTUMgySsdZwb6m-kx-LWZKs1Pocua6fKXFtAHdSmdFn_Mg-p7rzLjDfzzcTrFXnT9af8FrWn3vSXdM9JANC9W6RzW4hzKO8zi_K2MwmMmZo3xJYi9IQrdr8EB3gRUw9AQo3TW24yfW7bkAyCjZ4gdxP58WcUdlp5nfJp1P2kDWAS8oNa-xP2n7nGKrtcBQdC4Qs21IWVu00l2d4U_GitS4OHZO2hXqNhWc1rGKn1oigmticjHLw0_3ftBcjZk-PfEG1Cxk80_2SYlLQLSjg4CdNibwHhptsIACv5n8VLshmeABtiEZvN9MLc3Ml4HzWhXs_BXVdoxMgLBKNrMlPv8vj2GVaL2CuqqxhxMgrlB1-b9FJUjxI50ZOCI3Mu9h2zaP9TmG4yxArQLVLCyZpQyr3FT38kDiAR8kC5GSrCRUEifV9_7hwMuH2Z_0uCoCgyIOoEaoDyaMP3kc_diw7UDvfPnCbw3RYi9xmJhMVeDNdW6ld-IVGAqDdvB2chTJ-cOfUwJMBKuoVFYvjeOpMWcue4zYPTp0S33ugubz4frxRTk3nVlIi-POiEJ5F0Ktn8fAUzFvvPsUnHrz5ptGdnz5TUk44v3bTx8OyTLECjChgHqVAV-0G00)

**Level 2: Container diagram**

Once you understand how your system fits in to the overall IT environment, a really useful next step is to zoom-in to the system boundary with a Container diagram. A "container" is something like a server-side web application, single-page application, desktop application, mobile app, database schema, file system, etc. Essentially, a container is a separately runnable/deployable unit (e.g. a separate process space) that executes code or stores data.

The Container diagram shows the high-level shape of the software architecture and how responsibilities are distributed across it. It also shows the major technology choices and how the containers communicate with one another. It's a simple, high-level technology focussed diagram that is useful for software developers and support/operations staff alike.

**Scope**: A single software system.

**Primary elements**: Containers within the software system in scope.
Supporting elements: People and software systems directly connected to the containers.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.

**Notes**: This diagram says nothing about deployment scenarios, clustering, replication, failover, etc.