# 1.4.3 Components Diagram

![diagram](https://www.plantuml.com/plantuml/svg/0/jLPDSzem4BtxLsov5AO9N7hg9I49qoH30WKpdPuyigqO9RBaId8eq-b_xqh-97RQb9boGMXttpxjUvOvruOeawVSUyT4nFEOmjQOJ7-QJ1JPZHDcjdcOQweYAGmLPXp9T49YnOXuvdcMJou_dYuv4MPpDvzmOgWsk1LSOZPXWgfnzX-mqqmAc--mlVdqssBZ1rzl_EjWFliykxyQZZolPZ1aMK3Yb8aW8uBo4nZS23mqvrJ1KYfSmTI6OMd30uolyd0FKi6ACAxX0zokxUwKSxdJuA0W9O8a55Y5XFiY1f999aoArFHWr32u2eTnY0XNn92GQ6hHbbARH57zPMv_hOt4DTOt00wmXS_4WrGfCKmAn5xljQ5fCFjXXZH8aIU2p4xj0hGBELIt0gm3JKNCH0BKfXoG6ng2gJvJ5AO9DWRD3EsRmegIo8mVjOtvMrhsSUZ6Lcl2gKMkk5t8NCH4xUtyYzpkwE62H4z83OgQmGX-Ue2VMk8XoQqps0EBtD6j3eSx7QejhQotD1Y9Pqe4Jl2aMEIP6wwYaNocQWyPqNedLOpaNpHlzB2WpQ_UfcTdPns4Mi23iq-Z28TZ_aIzfJpoB-tMzaUd5Hx0jLdOxpSJrD6MnZcdrYxbyfzfLHWTSEiBOaqLu1CkQ5Ggs3BRPRtVstMDtj0erFSSdttNqh-fQZlTkAmzCfT_DqVlKIgC3dYO18yor5XkBPieQswunPtU5YjKbwNKFHnXas-8VhB2_VAy5UMTY-dGRXjD7TRjUd4_kVRzvHeh-yhQ7djpKVUvUhMqazhCmkg3yYHC6-M2pGLZA-l4-eug1AsJ2ceD_vOR7PtHouJAvFtHbWFw4tecN9wn7UXdKRP-5QACl-BvLc9_Xhk6DrcChxdYbEyr86-JQzZXYx9IkPYop2ft7wZbzUlbNZvuVSV5IsMdy8OlREgkzYaoUAPulqVO5nQhkxwP78dHclsH28qOHmAKkXnPtLZg203l7Erk_wFy1W00)

**Level 2: Container diagram**

Once you understand how your system fits in to the overall IT environment, a really useful next step is to zoom-in to the system boundary with a Container diagram. A "container" is something like a server-side web application, single-page application, desktop application, mobile app, database schema, file system, etc. Essentially, a container is a separately runnable/deployable unit (e.g. a separate process space) that executes code or stores data.

The Container diagram shows the high-level shape of the software architecture and how responsibilities are distributed across it. It also shows the major technology choices and how the containers communicate with one another. It's a simple, high-level technology focussed diagram that is useful for software developers and support/operations staff alike.

**Scope**: A single software system.

**Primary elements**: Containers within the software system in scope.
Supporting elements: People and software systems directly connected to the containers.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.

**Notes**: This diagram says nothing about deployment scenarios, clustering, replication, failover, etc.