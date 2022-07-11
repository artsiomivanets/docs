# 1.3.2 Containers Diagram

![diagram](https://www.plantuml.com/plantuml/svg/0/XLLDRzim3BtxLt3TOIsMDJlqDBH5qw-rGz9c-K2nKy3OTA95bZn9hkSD_U-ZP2TpcWtnnHQbnqS-aVI5TMXSaSdeZL2nB1A2fNEv_TJj6YoF5y8jYtbXoSHQELBkEDPP5nCZK3tB8Y-wLoSVXXALcmxwNOcEh6FJx8fFer1aZdFlE-htlZrE9xEd-ydTh7_p-URX-l0eYknAg1mDPc0eTgWMaavFlOlpS_WT0J_Z9IQw56e1AKfBjSsH8Usgd6wPPIn-4NmC6tvvfQKsyFOaFC5wgKr2vd_siQiaGO9sIKbjndYrCBfGIGEv3K_q4aL3CbQhmpoVOP89rO638LP350PwVYsiC-YqEU2DO02Tmlg4hQoZxE2evSIhoaUd_0eGoCCMb4iD9IjgmMcO5nKuOSXss4uaBSmha1eLkuh6mUdiqaUBfl9EQvvMQEE6k15qSp7-y9nccEUjmpvvKeaFPrGm4KSpGY6jDmoDVXO9sKrAQQ5Y9xH2ALm5pmBXo_ZneNitcGp77DqEMn1jbgCY-LewzidM7Lfupow3DbBgqaBm01agN11u-TYa4fOvvSz_KQQl4tmIoO9S82ACtV5tst9VU-Jz3iHBYbV1URpKsbAGV8VYUdwOp1b_ZGxdQ2d8fArRy7rzxVlLcEk1QiyWLAepz8frmhUf5vp3N1UkFcFeHy7rN-ULrugRT_PlYY60JRV0mTbPdo_Cxy6cTT22h8rDEJHtlorFQcTh0WxqLj9FkzGvrs03zk4t2R_IrRM1hApJcJP6b_k0UjK6FdBp5tOVfj1jp5INQX_2vMt4XB9SqpuCfcrCBqtt0k8jG2mot8MyrBSr8jbkjkshyJN2Xlhs4wwZ1kj1hq-sEpQ0DbN1J0rBFLJQfJ_YakAAwd27Kial7k0yS_r0mJYcd6jjNTkDYsQuxNJi8FHTqoQRFBOxi76n9cz7FC0LGMzu3p7AUg9iZOis-Pgo3USnsI9OcqFxSIidTHob4Tm3eRt3_EZnW7ec5ZFcOG-Feu7le0iEtF-K_W00)

The System consists of the following elements:


PayPair Admin Panel. This application is used by the administrator to provide functionality for it. Admin Panel based on [Rails View](https://github.com/ruby/erb)

PayPair Widget. This application delivers to the end-user browser and provides functionality through it. This application is based on [React/Redux](https://github.com/reduxjs/react-redux).

PayPair Backend. This application provides functionality through JSON/HTTP interface. This application is based on [Ruby](https://www.ruby-lang.org/en/documentation/)/[Ruby on Rails](https://github.com/rails/rails). It has integration with many Lenders services. 

Lenders. It is lenders API. They provide loan offers for the end-user

Database. This element is responsible for the data store: users data, offers, providers data, etc.