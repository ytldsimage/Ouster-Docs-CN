# ASIC2020或fw1.14以后资源

> 需要说明的是，哪怕是[ASIC2019](/asic2019)，只要固件升级到了fw1.14以后，也只能用ASIC2020的驱动！
>
> 多机锁相，盲区检测，方位角遮蔽，低温冷启，强化串扰抑制等feature 等特殊指令及固件，请单独联系os@oslidar.com 索取。
>
> 官网最新文档下载地址：https://ouster.com/downloads/

### 用户手册（！！！重要！！！）

- **ASIC2019**:
  - **[OS1@ASIC2019 User Guide](https://data.ouster.io/downloads/hardware-user-manual/hardware-user-manual-gen1-os1.pdf)**: User Guide for Gen2 OS1 sensors
  - ~~**[Gen1 Change Log  for v1.14-beta.12](https://go.ouster.io/cs/c/?cta_guid=e16f8dbc-94ab-4b14-ab0d-c65813b3a36c&placement_guid=725df4e2-a148-44ba-ba92-1fe4c0b8008b&portal_id=5054152&canon=https%3A%2F%2Fgo.ouster.io%2Fbeta-program%2Fbeta-10%2F&redirect_url=APefjpFkJK3tyYeakvqGLiR6TIj0F6Ah7-mqaOK3QR1ofTlg4lWIcMdkiW4bkVRfZlQWwA0joxIZFpLAjl9CGzXqEbasRX0gfF5RX7mCRX2GcObSQh3aEMC6CRUhWDkNCYWxiSWX6Fei7E1B5bhniPGZIj0syJv8N9OTxCnpWcUB6jwfJ3is-x_Am4gfQsYO6I5L2NpTqmYqHdl4Ft9EX_neyT3G_dGmOw&click=72d5a18d-3eb3-423c-a344-98fe8e17573b&hsutk=7b1c51587557cc04d5a9038ba7ea88b3&signature=AAH58kGA65kfie3pT-Vn7bfr6GeSO34Q0Q&pageId=29569243223&__hstc=82216777.7b1c51587557cc04d5a9038ba7ea88b3.1601731472859.1601731472859.1601731472859.1&__hssc=82216777.1.1601731472859&__hsfp=432711229&contentType=landing-page)**~~
  - **[Gen1 lidar packet structure changes]https://data.ouster.io/beta-program/v1.14-beta-11/Gen1%20lidar%20data%20structure.pdf)**
- **ASIC2020:**
  - **[OS0 User Guide](https://data.ouster.io/downloads/hardware-user-manual/hardware-user-manual-revc-os0.pdf?__hstc=34987006.3b498ee11237b4e28da832cc795fa6b7.1603177544769.1606967208102.1607045278647.6&__hssc=34987006.1.1607045278647&__hsfp=3202914155)**: User Guide for OS0 sensors
  - **[OS1@ASIC2020 User Guide](https://data.ouster.io/downloads/hardware-user-manual/hardware-user-manual-revc-os1.pdf?__hstc=34987006.3b498ee11237b4e28da832cc795fa6b7.1603177544769.1606967208102.1607045278647.6&__hssc=34987006.1.1607045278647&__hsfp=3202914155)**: User Guide for Gen2 OS1 sensors
  - **[OS2 User Guide](https://data.ouster.io/downloads/hardware-user-manual/hardware-user-manual-revc-os2.pdf?__hstc=34987006.3b498ee11237b4e28da832cc795fa6b7.1603177544769.1606967208102.1607045278647.6&__hssc=34987006.1.1607045278647&__hsfp=3202914155)**: User Guide for OS2 sensors
  - [Software User Menu](https://data.ouster.io/downloads/software-user-manual/software-user-manual-v2p0.pdf?__hstc=34987006.3b498ee11237b4e28da832cc795fa6b7.1603177544769.1606967208102.1607045278647.6&__hssc=34987006.1.1607045278647&__hsfp=3202914155)
  - **[API Guide](https://data.ouster.io/downloads/tcp-http-api-manual/api-manual-v2p0.pdf?__hstc=34987006.3b498ee11237b4e28da832cc795fa6b7.1603177544769.1606967208102.1607045278647.6&__hssc=34987006.1.1607045278647&__hsfp=3202914155)**: HTTP and TCP API Guide for v1.14-beta.10. This guide is located on the sensor under the ‘Documentation’ Tab
  - **[New XYZ calculation](https://data.ouster.io/beta-program/v1.14-beta-11/New%20lidar%20range%20data%20to%20XYZ.pdf)**: If you use your own drivers, it’s important to know that we’ve updated how XYZ should be calculated in v1.14 onwards. This document goes into detail about what has changed what you need to change in your drivers. It is also covered in the User Guides. If you use our example drivers, we use the new method of calculating XYZ.
  - **[Gen2 Lidar Data Format](https://data.ouster.io/beta-program/v1.14-beta-11/Gen2%20lidar%20data%20structure.pdf)**: Starting in v1.14-beta.2, we changed the lidar data format in v1.14. If you have a 32 or 64 channel Gen2 sensor, this document will explain in detail about what you need to know. This is also covered in the User Guides. (If you’ve been with us since early v1.14-beta.2 or later, you won’t need this document.)
  - [Change log for v2.0 for Gen2 OS0, OS1, and OS2](https://data.ouster.io/downloads/changelog/changelog-v2p0.pdf?__hstc=34987006.3b498ee11237b4e28da832cc795fa6b7.1603177544769.1606967208102.1607045278647.6&__hssc=34987006.1.1607045278647&__hsfp=3202914155)
  - ~~Special Notes:~~
    - ~~[多机锁相](https://go.ouster.io/cs/c/?cta_guid=89950dbc-376e-4864-b95a-6c669bb12d84&placement_guid=3b420160-bfab-41ca-87e3-cf7fe2ba945d&portal_id=5054152&canon=https%3A%2F%2Fgo.ouster.io%2Fbeta-program%2Fbeta-10%2F&redirect_url=APefjpGHSGMXRtZYKX58o6YS3sm8HFDtXn2AqEh7JsM7V8p1wyWNPmil1hB-EWvUy2a87_PLu1nN61RR8ra7viVGDcNYPdNKynOurNNS4TGHhT-7JTVElcnJt_5YXLPlHE0GDqMwyyFdv0s7lcICUsMdy2ApkLwDcMLO-hFOvk2Vx24ZY-DfKb2VdvqC_5_bhE2NwR0g3TJosJfVf9J4DydF1vDUeMGn3OJlaP634Ia8O1NSTfMvxQLfidQ3IR5PP5LdU8xQ9prf0EnggNhFk7_GeN0DA1U17vqn5j3oubkbyrTNZJX3qDnoIoIJrxWDA2NEykQbtywDYvOA5he4o2L6MFL8c5q6kKaiGoa51FxPsY93KP8Xm4E&click=e0264b14-6631-445b-a179-7ce9b8cb72f9&hsutk=309af5574f913a30980d651eafa90dd4&signature=AAH58kEyYSCubKgMd7SYSKBDdlrCrZQmWA&pageId=29569244383&__hstc=82216777.309af5574f913a30980d651eafa90dd4.1598932903127.1599982472787.1600863714552.4&__hssc=82216777.8.1600863714552&__hsfp=3417619826&contentType=landing-page)~~
    - ~~[盲区检测](https://go.ouster.io/cs/c/?cta_guid=2a2c468d-ef45-4a3a-8184-0a6044955811&placement_guid=faa557f6-952d-4b17-a298-159379075ad1&portal_id=5054152&canon=https%3A%2F%2Fgo.ouster.io%2Fbeta-program%2Fbeta-10%2F&redirect_url=APefjpEJQhzjZPoEr5uAFmkJYwMiMB2G3OqTwaNuBxPLyZKsEP3zZ8erJ1KNYQpdBKJMB-Z3aLkMEn24iROfjs7FGIJfF_m_01sKfaLbEnktgjz7Py49_VEQiwZk9lILt1u9NNCVeTnGRCoS-cB0bJmRRQKIySzKeQJkUA9i0PsXSHzZv6VR0nXgV2--isseNxNxG40GmSNZDVf0oKEShIiga-FjYBITZyNZD78gpRRKkC8-FfhYIqrnL4LWACdB0DyOB2BpF1EaisNRBI76tsG9DHc3Xgwxll35sMiUZSdC_I5DF2GXX1TfeiFFRspIKIv8Boh2Zw2m_X8KyfJ2x2NSy-0j3pwTXMSkjcGolCCQybZRROD9UJ0&click=f741c7a9-dfde-4530-a3ee-9efb836e47d2&hsutk=309af5574f913a30980d651eafa90dd4&signature=AAH58kEOSowh6M98gMFbt1A3p-hdi9wUVA&pageId=29569360225)~~
    - ~~[方位角遮蔽](https://go.ouster.io/cs/c/?cta_guid=e686bce5-86da-44d8-b95d-1af6fc9d1d87&placement_guid=a7a02ce2-8642-44b6-abfd-c9d2ec3c11a9&portal_id=5054152&canon=https%3A%2F%2Fgo.ouster.io%2Fbeta-program%2Fbeta-10%2F&redirect_url=APefjpFzd00tzaT47K63uvZPSeeuVKiSxZ4VrDWdHpffndnLt0FHboDN1WiJxTQVdfrlRa7jmq4Xlrs0EoI-zvoN3NUS47twZJn56Qi9Jw9k9VS83LmuxShDT8Jl8EpGU7g1lsR8SUHH0XVfnYAVUTO5mytlBJ41JdgAu5LV2xRwdVQCQVcDOIs4me1GCQlTtxTTW08q7wM7eNxoWnMLcOT2seNINjnX4fj7075shkEHqnsFnseBDfjLyblO7XE6jF-I1sZzkIGHOhV2uWzet58BTS5l8RuEcPB3c6bBqhlY_UD81UW2MZM_geOEkyc8Ew0ES-U0ftJwziE4xAr6SrvWvZ73usR759d0G0_D9Ev2w_OMR-D0sB4&click=0c9a82cf-6054-4201-8d2d-9d0d1f64a407&hsutk=309af5574f913a30980d651eafa90dd4&signature=AAH58kHHxN5z6O2s2o-hQkWxu8NgJHn08Q&pageId=29569244219)~~
    - ~~[低温冷启](https://go.ouster.io/cs/c/?cta_guid=985bb9ea-85b7-4e7a-8c02-191f495468ad&placement_guid=1d338d62-cb37-4a0c-bb32-74c0f8ce52af&portal_id=5054152&canon=https%3A%2F%2Fgo.ouster.io%2Fbeta-program%2Fbeta-10%2F&redirect_url=APefjpER8aVF2V4TbgFW59GDO81ckt_mQTfkTD3fSiVhMikMBPRMpxtQtaYAUd84JsQabwdlYq4aXZXG_ogVAmrVKgj8x-SEVehZd7qE3Nwqpvf3pY7t5ACZXfXh6w8Oh0xQsMNvhw0Q7M-LJOd2BSrcS3d8chETYeZLtUmB9LWG5a3r2mHREa4LPNHaIsC2kLFWLWN3vipTNmta1bv4es1CvM4K11gyI57X9Ytu7ufUlzISVyCQ9bvwdY1MU0MkVzAbiw2Q_7Wl-6_k8uPmqvsIWawiRytlSKr37jSW2nW0GF7O8rXEbO2A4PfqBvB1jQqH-MQ6XKQFP9lb14j3t-Do54K2Uy3IibYDTYFZF1SGS3-dfbqehEM&click=49bfc0cd-b0ce-49c5-8106-47fb32f6f57a&hsutk=309af5574f913a30980d651eafa90dd4&signature=AAH58kGwDPTDo8kPKBmws-HbsNtRrPOziw&pageId=29569244332)~~
    - ~~[强串扰抑制](https://go.ouster.io/cs/c/?cta_guid=44783b0c-f7c5-47ff-b14f-ddb08d59103b&placement_guid=85210f60-39b1-4f2b-90ba-644b031c8906&portal_id=5054152&canon=https%3A%2F%2Fgo.ouster.io%2Fbeta-program%2Fbeta-10%2F&redirect_url=APefjpHK9iskpDCBFioBB6fsNspyQciqL5buBO5Lgi9mxPvf5MM1RRPQS4fXKy4-LuvIGVXb-jYPXcYVIM54HzupGGiV64CYC5J1FGDN4O2EwB4qZVsgPNvpvRsE9tPZYxs_qKAyuaOODjYWx9w-pN5HHIeM6rImdYFiqICd2BFoPQn0nlukYSSDkVMq3FwdFgYKjWsdgkigQBdlUK47xW2zGIanT9DK7zYTj3KclPWQ9X9zzlXk2_Qe5IzlDWePKS27u68Cb3ZMK1k0ZVKZD0XlvBcPZyealgn86HUUublwBYZ314IYdt0tk_tjLu_5bGjkk7KHOTwYCD10-v976oCRDKtfVVIqEvYJz8UwHIRHv8r_bsmmb8c&click=137eccd7-d14a-4d44-9f7e-84f880a939d5&hsutk=309af5574f913a30980d651eafa90dd4&signature=AAH58kEHc04UTXmTcIqeBun-Njggbmb06A&pageId=29675795068&__hstc=82216777.309af5574f913a30980d651eafa90dd4.1598932903127.1599982472787.1600863714552.4&__hssc=82216777.16.1600863714552&__hsfp=3417619826&contentType=landing-page)~~



### ROS数据样例 @202007

- [OS0 Sample Data](https://ouster.com/resources/lidar-sample-data/os0-sample-data/download/)
- [OS1 Sample Data](https://ouster.com/resources/lidar-sample-data/os1-sample-data/download/)
- [OS2 Sample Data](https://ouster.com/resources/lidar-sample-data/os1-sample-data/download/)
- [Autonomous Vehicles](https://ouster.com/resources/lidar-sample-data/autonomous-vehicle-sample-data/download/)
- [Smart Infrastructure](https://ouster.com/resources/lidar-sample-data/smart-infrastructure-sample-data/download/)
- [Google Cartographer Sample Data](https://go.ouster.io/download/google-cartographer-sample-data/thank-you/?submissionGuid=e7d57d54-d9ce-40ef-9873-00167aa630db)



### 驱动相关

- ROS/C++驱动及（Viz @[fw2.0](https://data.ouster.io/downloads/firmware/ousteros-image-prod-aries-v2.0.0%2B20201124065024.img?__hstc=34987006.3b498ee11237b4e28da832cc795fa6b7.1603177544769.1606967208102.1607045278647.6&__hssc=34987006.1.1607045278647&__hsfp=3202914155)，含Ubuntu, MacOS & Windows）:   https://ros.oslidar.com
- ROS2驱动：https://ros2.oslidar.com
- Apollo驱动：   [https://apollo.oslidar.com](https://apollo.oslidar.com)
- [Autoware驱动](https://docs.wixstatic.com/ugd/984e93_b4e43111b1dd420cb3bc2c3e13071e71.pdf?index=true)：[https://autoware.oslidar.com](https://autoware.oslidar.com)
- Pcap2Bag: https://pcap2bag.oslidar.net
- Las2Pcd: https://las2pcd.oslidar.net
- Bag2Pcd: https://wiki.ros.org/pcl_ros#bag_to_pcd
- Python SDK: https://pypi.org/project/ouster-sdk/
  - Documentation: https://static.ouster.dev/sdk-docs/index.html
  - Quick Start Guide: https://static.ouster.dev/sdk-docs/quickstart.html