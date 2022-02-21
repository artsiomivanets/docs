# 1.3.2 Containers Diagram

![diagram](https://www.plantuml.com/plantuml/svg/0/XLLDRzim3BtxLt3TOIsMDJlqDBH5qw-rGz9c-K2nKy3OTA95bZn9hkSD_U-ZP2TpcWtnnHQbnqS-aVI5TMXSaSdeZL2nB1A2fNEv_TJj6YoF5y8jYtbXoSHQELBkEDPP5nCZK3tB8Y-wLoSVXXALcmxwNOcEh6FJx8fFer1aZdFlE-htlZrE9xEd-ydTh7_p-URX-l0eYknAg1mDPc0eTgWMaavFlOlpS_WT0J_Z9IQw56e1AKfBjSsH8Usgd6wPPIn-4NmC6tvvfQKsyFOaFC5wgKr2vd_siQiaGO9sIKbjndYrCBfGIGEv3K_q4aL3CbQhmpoVOP89rO638LP350PwVYsiC-YqEU2DO02Tmlg4hQoZxE2evSIhoaUd_0eGoCCMb4iD9IjgmMcO5nKuOSXss4uaBSmha1eLkuh6mUdiqaUBfl9EQvvMQEE6k15qSp7-y9nccEUjmpvvKeaFPrGm4US_GY6jDmoDVXO9sKrAQQ5Y9xH2ALm5pmBXo_ZneNitcGp77DqEMn1jbgCY-LewzidM7Lfupow3DbBgqaBm01agN11u-TYa4fOvvSz_KQQl4tmIoO9S82ACtV5tst9VU-Jz3iHBYbV1URpKsbAGV8VYUdwOp1b_ZGxdQ2d8fArRy7rzxVlLcEk1QiyWLAepz8frmhUf5vp3N1UkFcFeHy7rN-ULrugRT_PlYY60JRV0mTbPdo_Cxy6cTT22h8rDEJHtlorFQcTh0WxqLj9FkzGvrs03zk4t2R_IrRM1hApJcJP6b_k0UjK6FdBp5tOVfj1jp5INQX_2vMt4XB9SqpuCfcrCBqtt0k8jG2mot8MyrBSr8jbkjkshyJN2Xlhs4wwZ1kj1hq-sEpQ0DbN1J0rBFLJQfJ_YakAAwd27Kial7k0yS_r0mJYcd6jjNTkDYsQuxNJi8FHTqoQRFBOxi76n9cz7FC0LGMzu3p7AUg9iZOis-Pgo3USnsI9OcqFxSIidTHob4Tm3eRt3_EZnW7ec5ZFcOG-Feu7le0iEtF-K_W00)

**Level 2: Container diagram**

Once you understand how your system fits in to the overall IT environment, a really useful next step is to zoom-in to the system boundary with a Container diagram. A "container" is something like a server-side web application, single-page application, desktop application, mobile app, database schema, file system, etc. Essentially, a container is a separately runnable/deployable unit (e.g. a separate process space) that executes code or stores data.

The Container diagram shows the high-level shape of the software architecture and how responsibilities are distributed across it. It also shows the major technology choices and how the containers communicate with one another. It's a simple, high-level technology focussed diagram that is useful for software developers and support/operations staff alike.

**Scope**: A single software system.

**Primary elements**: Containers within the software system in scope.
Supporting elements: People and software systems directly connected to the containers.

**Intended audience**: Technical people inside and outside of the software development team; including software architects, developers and operations/support staff.

**Notes**: This diagram says nothing about deployment scenarios, clustering, replication, failover, etc.