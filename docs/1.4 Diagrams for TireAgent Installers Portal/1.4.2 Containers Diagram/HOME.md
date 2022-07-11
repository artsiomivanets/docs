# 1.4.2 Containers Diagram

![diagram](https://www.plantuml.com/plantuml/svg/0/bLHDZzem4BtdLqov5DIMN7hgQTa5TRU29IMWggTeaXXmwzYMxO1GrV_UiGE4B71eJlwOz-RDp8iVh4FZwaf4xxWiH5qos3gdxPSuDhWVRhZRrdbjcIcKT4owOQ6g64l3KUv4hUluwVEdHA1qgzaq5kYOTNIKFL4qSidCK7lkQ3hwELyjinylo-TiElawUHtt1r6KC6ELxDjQCvDXMN7v4Ngfty78xxXr1fqoFJeE1w3My299iX0KaoX3gzxWnCDFDsUkDlO-tna5M1IgbgubP9KMwi0OXK-EImzTSiDWjA5km2c2CEUI-mwxGPQxW5lK-G6KX0LoOU43B1WMRlZB1iuj0tkmZbMmLWQSHriKp19pb8QBx97KbMWEVQsp9hPJOjCEQ89x0_WJ0NsjBAwpd6MezItK8nQ_cIolPFg3nAWTBvczQZsiQrauhYGAxWwmumZVqlbh_BnS9Ya9lyeVvf9fb4pS4j7C9F7NDuMCX51x2u45l2b9KuKIDmoeBCMbgwZVzctcSTulSuAFqM6EDimYKTPj2FzzwdSfcOAuBaa0PTbwmzAIvbAXhvRu_qRHWeckSw_gcpNIBaYE3lCAFVpAi7SeRClnte8o9N4TALgBtajFi2xamWUXBMJ3iYbtRyYfeTEDHKSqt1qZdnP40FF5h6NefBfqrigoKoB_7rnUfMImenJOqyDogYeq5PGElQMuZeVUA0x_ragNzD8qLDGG8d7rVr163oJ4Fql_0000)

**Level 2: Container diagram**

Once you understand how your system fits in to the overall IT environment, a really useful next step is to zoom-in to the system boundary with a Container diagram. A "container" is something like a server-side web application, single-page application, desktop application, mobile app, database schema, file system, etc. Essentially, a container is a separately runnable/deployable unit (e.g. a separate process space) that executes code or stores data.

The Container diagram shows the high-level shape of the software architecture and how responsibilities are distributed across it. It also shows the major technology choices and how the containers communicate with one another. It's a simple, high-level technology focussed diagram that is useful for software developers and support/operations staff alike.

**Scope**: A single software system.

**Primary elements**: Containers within the software system in scope.
Supporting elements: People and software systems directly connected to the containers.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.

**Notes**: This diagram says nothing about deployment scenarios, clustering, replication, failover, etc.