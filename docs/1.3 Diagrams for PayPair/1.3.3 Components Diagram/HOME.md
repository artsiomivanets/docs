# 1.3.3 Components Diagram

![diagram](https://www.plantuml.com/plantuml/svg/0/jLPDSzem4BtpAxPSIgO97DfJJo4Vau-1G36PJ4-Ci1TGAakk94FJJlzxLn8sTd0oD9rooRBiUxlxTYNbr5YcRPwArZikOv4d22jhC_EvrzDiqrrokyhdkK4TAsbHscwiqXvBD6ToBV8ixvr_EXaB9ktzSD0JpAAnv9gTKpJZ4dKt-m_SQQQaY_VShK7_w-X-EdkucLxF1fTNbtSNdQDMgwoWasMp1SvObXr3UyoUnenhUE394csRF1DaiUq-6cUFjLhp10qm8M2HozXo9PdWzWdK0kmAeS1R1IYJ4rSyh3c3kLORijj7zRmiIRcSPKoYg2JlEozHaTTNaC-9NyE4SM7W0zn6pjiNWYZ1Cq3A95iYk7JaaWcLio2pckvYtadcXBjWbisPGT-FCdQfqNmPk6-HLMHx4k1oeLBcsZlsjWvVY7okSXjYD7xFIVAGC0lIwFTcbpjwCXRJsUKFsn6a1Zafoo1OleNnZTCjuGv0yu9OOyAfYcTWapfWb1emtkcBzHPGPM28qK0qZEeebhAVhlnstniGVIoQ9Aaej8WzKxbCc7voymZybL6SiVWRqKE8RH_1hnRGfronJj6tsQr7QAusDUSWJ9fB7hizXGtjDcn5wKBaEoZqF2OhHhx6KjaOZS6AiFKI_DGfmRrvAVLsLy9wq6gIpbI5MrXgKIWczqbJEdKhEbgEU5ZOhv67HIJoxIwM4t-XQe6qXExK2IU9sos_7EJiLtoD6Ua4nffdBc2FjfZ7B1OSG_dbM23u6Zdh8t1zb9FToy5oTnlnnRP8fq7TqvZX0YrgqeW6oTrbmUaloGOIDovEeysrv7BfnxINKsMME4OsesNHQnxZVexd48sPqjPVOSvu6RXj7mB04VrkjIOe6iJSdUChjCL6kbEOLlIYNs-ZqLtlUZeTkqFfg7pzuI3Jdkx7X7oxcxYorCs4bTZg6Jmald7r3W7k3_v5r5ve6E2hlTTUW-e1VAss6kWGrMg0GwMhWVvQlnhwG14zjY92KwMZ-IF6z6pGSrpAk0jhk0eE0_ftajxz95p06yrjW8KNk4_F_XfXWh7I2OmcmssZM_7VY6uIzOrK5TNUoF3lOXINJ_aAbwzJRSgdT9-uVzB-0000)

**Level 2: Container diagram**

Once you understand how your system fits in to the overall IT environment, a really useful next step is to zoom-in to the system boundary with a Container diagram. A "container" is something like a server-side web application, single-page application, desktop application, mobile app, database schema, file system, etc. Essentially, a container is a separately runnable/deployable unit (e.g. a separate process space) that executes code or stores data.

The Container diagram shows the high-level shape of the software architecture and how responsibilities are distributed across it. It also shows the major technology choices and how the containers communicate with one another. It's a simple, high-level technology focussed diagram that is useful for software developers and support/operations staff alike.

**Scope**: A single software system.

**Primary elements**: Containers within the software system in scope.
Supporting elements: People and software systems directly connected to the containers.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.

**Notes**: This diagram says nothing about deployment scenarios, clustering, replication, failover, etc.