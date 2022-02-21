# 1.1.1 Diagram for all system

![diagram](https://www.plantuml.com/plantuml/svg/0/ZLHDRnen4BtlhvXo2XBDNdhg9Q4qIYCb3MA9K4_8U0VMhTTsRIyhLFM_TxpBUla8QP0Go9xtPkOzpzmwpwolIfby48hBAaSel3VkSvfQLbzlX2-gLUNGSgqyAd_DTPcot0gcjh8oLJhvz74gcV8lJu-fP1wTfwFbXAAPK6YlJU1E7iS_db_coyN3_DloyUx-xllNgs6IJD4whQuyMxAy56e4Wxcm26D3YM0SZeJpbdbj1tGt1jF4GrreC5PpT0uTQ9lJyM3OiHaJsQPiDsN2lfjAeWfSm5GEUhq-eXKzxOCYqQGCaLDjwUz_4d2B90meh454w15poHJRe3taXgVsx8roV-eLMFnTaUOz6uaPx2BKYti5NPDL3ho6LRK3Jsgx4PqZIlf5puadoNREOxdyeYkLCxiBZAuvYlviWZzjs608VnAWJtIyiTEOOpCpuJ7Kqdo79u3WM0Fe_5g8V8F-Ohpeui-Ck0Xn7IIhZ97Y7OYwGooOnKAJfkU81Z936LkEdSmmf-PvaBf028O4pUbExc2jBJ2Gcgb0yqpwT0qFpmXZgnazpUO57PhUrts8wNlL9Vf2gCtDpSs5sFgDsBz9qeMs3pyQEpqVldra-_HYO8RCygAPfullxGWP1Rn7qYvev48rTxHxoBBs7TEyvSop4KmAv8NRJ-e8CfIDuY7Rc7Cqz5yhfFjWGhbFrQ-7cAkTjDUcV--FIoTIXtPfzhOYRx9j1TPzxXckQLeeZYbElQKpTA61xZfK-YimCxdpWdU2zJj5dDJIxuccd0FJMprouIbPirVSGN3CT0I8oUAQEKrtoX_KJpDUO5v9Z5sTijwIO66x_mC0)

**Level 2: Container diagram**

Once you understand how your system fits in to the overall IT environment, a really useful next step is to zoom-in to the system boundary with a Container diagram. A "container" is something like a server-side web application, single-page application, desktop application, mobile app, database schema, file system, etc. Essentially, a container is a separately runnable/deployable unit (e.g. a separate process space) that executes code or stores data.

The Container diagram shows the high-level shape of the software architecture and how responsibilities are distributed across it. It also shows the major technology choices and how the containers communicate with one another. It's a simple, high-level technology focussed diagram that is useful for software developers and support/operations staff alike.

**Scope**: A single software system.

**Primary elements**: Containers within the software system in scope.
Supporting elements: People and software systems directly connected to the containers.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.

**Notes**: This diagram says nothing about deployment scenarios, clustering, replication, failover, etc.