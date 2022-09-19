# 1.1.1 Diagram for all system

![diagram](https://www.plantuml.com/plantuml/svg/0/ZLHDZzem4BtdLqmvBH8bbvvwMahHTYMsY_ZGQa_8E0DnwzYkxO2Ygl-zuuGuV2pj8aL4zhmtyzxCvDvvPdrPoEI3K5oM6KBklN6VqzIomt0dV5vkIeUMQ-LH-I7NHSeoAvZQozAKwVZJnvbaog-Ufgba7fsde_MOefbGQ8ScS2VJqUlpQhb-ULn-Mqyd3vFlN-_wIJ93wxIwyspDiaAe0VIMmYACTfG8Hk58E6-PrxP7ToCmTJmSSWt6QexEeGDjCphkzLisOoBRZ5Kp9koxgIIgm0LCPQ2tspDQqT4-AZ9DoX0vqvPU_vE0MoHZGE41H8IUCHTCiHtQKsvuQix-KUuFlG6Blqhol6CZCqEx2BLoRw0Fr2e7NiEchC2Jssv0vuYI_j5puaaMbVDOhB_eKcNCLe7HrKVd_Md2UdtudG3zOiVhTXfp4ImyXbhgfty121sh0Ms_NaIsGtypNhJnLusu2N4jP54Q8yKx48SMyS8ivfeylKRKa3dAA3agcMD6udcmEaS83GcUqvsiOAijC92QgK3pR52rWljNX57gWaQpdg3JfZTL_4cI5j8CQ6p0x7f9Zf7DYCJ01JBBythkRyx56J8AVK3I6BIuKCs4lX5aRJDlj1SPysm0unnvxeuRDO05ojgPa6t4EHfwrmhfFfXL75DrQnnpDHlnrfOUVNJfMEeWbtPaBx8wsrxWeSiznorDDSKnnKbREaSN1BJNeTAVWPd9oWlU6jRjlhYefTldkfoJvZH-PC9Jidh_tKbmp7G6YCdYv-0otIL_S3zTy1opKc9KTSbwJuQ5h_1V)

**Level 2: Container diagram**

Once you understand how your system fits in to the overall IT environment, a really useful next step is to zoom-in to the system boundary with a Container diagram. A "container" is something like a server-side web application, single-page application, desktop application, mobile app, database schema, file system, etc. Essentially, a container is a separately runnable/deployable unit (e.g. a separate process space) that executes code or stores data.

The Container diagram shows the high-level shape of the software architecture and how responsibilities are distributed across it. It also shows the major technology choices and how the containers communicate with one another. It's a simple, high-level technology focussed diagram that is useful for software developers and support/operations staff alike.

**Scope**: A single software system.

**Primary elements**: Containers within the software system in scope.
Supporting elements: People and software systems directly connected to the containers.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.

**Notes**: This diagram says nothing about deployment scenarios, clustering, replication, failover, etc.