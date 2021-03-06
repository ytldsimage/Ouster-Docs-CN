# ASIC2020或fw1.14资源

> 需要说明的是，哪怕是[ASIC2019](/asic2019)，只要固件升级到了[1.14](https://go.ouster.io/beta-program/beta-10/downloads/)以后，也只能用ASIC2020的驱动！
>
> ~~新增加的[多机锁相](https://go.ouster.io/beta-program/beta-10/phase-lock)，[盲区检测](https://go.ouster.io/beta-program/beta-10/blockage-detection)，[方位角遮蔽](https://go.ouster.io/beta-program/beta-10/azimuth-mask)，[低温冷启](https://go.ouster.io/beta-program/beta-10/cold-start)，[串扰抑制](https://go.ouster.io/beta-program/beta-10/crosstalk-mitigation) feature 还在最终调试中，会在稍后的released版本放出，如无必要暂不推荐立即尝试。~~

### 概览

- ~~基本改进总结：https://ouster.ent.box.com/s/i9p4urir7ajr95oqzge2712smjv5ugte/file/636091713899~~
- ~~数据读取指南：https://ouster.ent.box.com/s/i9p4urir7ajr95oqzge2712smjv5ugte/file/636078936379~~
- ~~数据协议变化：https://ouster.ent.box.com/s/i9p4urir7ajr95oqzge2712smjv5ugte/file/636086989820~~
- 坐标修正变化：https://drive.weixin.qq.com/s?k=AEYARQeBAAYUG6XE1RAE4AvQanABU

### 用户手册（！！！重要！！！）

- **ASIC2019**:
  - **[OS1@ASIC2019 User Guide](https://data.ouster.io/beta-program/v1.14-beta-10/OS1-Gen1-User-Guide-v1.14.0-beta.10.pdf)**: User Guide for Gen2 OS1 sensors
  - **[Gen1 Change Log  for v1.14-beta.10](https://data.ouster.io/beta-program/v1.14-beta-10/v1.14-beta.10%20Change%20Log%20for%20Gen1%20sensors.pdf?hsCtaTracking=eabc3da7-8b3b-43b0-9901-695650461f5c%7C376c1b88-c6ca-4a9a-9054-84774c369be4)**
  - **[Gen1 lidar packet structure changes](https://data.ouster.io/beta-program/v1.14-beta-10/Gen1%20lidar%20data%20structure.pdf)**
- **ASIC2020:**
  - **[OS0 User Guide](https://data.ouster.io/beta-program/v1.14-beta-10/OS0-User-Guide-v1.14.0-beta.10.pdf)**: User Guide for OS0 sensors
  - **[OS1@ASIC2020 User Guide](https://data.ouster.io/beta-program/v1.14-beta-10/OS1-User-Guide-v1.14.0-beta.10.pdf)**: User Guide for Gen2 OS1 sensors
  - **[OS2 User Guide](https://data.ouster.io/beta-program/v1.14-beta-10/OS2-User-Guide-v1.14.0-beta.10.pdf)**: User Guide for OS2 sensors
  - **[API Guide](https://data.ouster.io/beta-program/v1.14-beta-10/Ouster-Sensor-API-Guide-v1.14.0-beta.10.pdf)**: HTTP and TCP API Guide for v1.14-beta.10. This guide is located on the sensor under the ‘Documentation’ Tab
  - **[New XYZ calculation](https://data.ouster.io/beta-program/v1.14-beta-10/New%20lidar%20range%20data%20to%20XYZ.pdf)**: If you use your own drivers, it’s important to know that we’ve updated how XYZ should be calculated in v1.14 onwards. This document goes into detail about what has changed what you need to change in your drivers. It is also covered in the User Guides. If you use our example drivers, we use the new method of calculating XYZ.
  - **[Gen2 Lidar Data Format](https://data.ouster.io/beta-program/v1.14-beta-10/Gen2%20lidar%20data%20structure.pdf)**: Starting in v1.14-beta.2, we changed the lidar data format in v1.14. If you have a 32 or 64 channel Gen2 sensor, this document will explain in detail about what you need to know. This is also covered in the User Guides. (If you’ve been with us since early v1.14-beta.2 or later, you won’t need this document.)
  - [Gen2 change log for v1.14-beta.10 for Gen2 OS0, OS1, and OS2](https://go.ouster.io/cs/c/?cta_guid=bc08d480-c9de-4d9f-b12d-3f71ec012569&placement_guid=95685290-70f8-40ad-ac06-852b8a74f18a&portal_id=5054152&canon=https%3A%2F%2Fgo.ouster.io%2Fbeta-program%2Fbeta-10%2F&redirect_url=APefjpE3aypj5JldO8uDTiSou217rELOSngfwUsNoS01w_iy8eQBI_EUqDEgF_3hZTeDg1uiTDo96muBilN_Al-RWBWwQfplxJqqUTyGsVXhT-RL-LniLWVunIMmvD0qZviRp5XU6nzDlvzE2A2j058SWmop3p4SWEAziHah1z_F3PLgSTlmvjnN3Twl6nIEH6a7IbndKntuCq0CRFxvkHTNQX4iVqBj2u_SRzOQ6Erfvxihz_DzUErcjSSvPw5Lp65VHmko0RlH_bG0bnQzT-2YsCV5VboHSgcMuR1N8xexmA_EVDbJZVtCxpDYedPizNrIicIUk_XW&click=17f8ff80-288c-481a-b0c2-f255759c03ad&hsutk=f7f9fa89a9b3a83930a447116d9a1796&signature=AAH58kFUkIAS2aQQO8-2S_kVehTQrBE7PQ&pageId=29569243223&__hstc=82216777.f7f9fa89a9b3a83930a447116d9a1796.1589280439546.1590573594493.1590658690686.3&__hssc=82216777.1.1590658690686&__hsfp=1824881308&contentType=landing-page)
- 



### ROS数据样例 @202004

- OS0/1/2样例： https://pan.baidu.com/s/1dpaw80j12tPlB0LWAcQTrA 提取码: eay9
  - 通用数据：https://ouster.ent.box.com/s/i9p4urir7ajr95oqzge2712smjv5ugte
  - 方城样例：https://ouster.box.com/s/iq0dkv4da5z2p1s2issj2thiie2fxi1z



### 驱动相关

- ROS/C++驱动及Viz B10:  
  - [Linux & Mac](https://go.ouster.io/cs/c/?cta_guid=c33771ad-6ac8-404e-814b-1aa531ba471e&placement_guid=3b0f3e91-633f-4d19-8669-92cf1b28fea5&portal_id=5054152&canon=https%3A%2F%2Fgo.ouster.io%2Fbeta-program%2Fbeta-10%2F&redirect_url=APefjpFyDJoUTD0MqJLP8h6LOEkOyxwp1mcbT38xKf2q6Ih9Xphf7gYdyIVn_FcefJjM8xweSzDVMNuqbQ2u0djukJ4nStuhjFGQ4Vd8eB7hUCzseiIy1HXPh9fJDTzqQuHmWPx9hhVcIEB5UTkTaJ8WF7z77PnQ1F1xZj9s7LLhpVVcWdagg2jNT_84ghYoZgxL6D9nXjXYaTRRz5iVULUOpMi-NeVSzw7ztCv0sfC78ZmhDXtzXzEc5fto_V06ZLrPyZSDXXwh6kmqk1BS8Hjpe2NscVAH5VOT8cL99L1Lh08dPY-aUTo&click=2dc344de-dbb7-47cf-859f-4b6a3eefc728&hsutk=f7f9fa89a9b3a83930a447116d9a1796&signature=AAH58kHb1cA0QO52Xbi0oDjgrl9aa6z4LA&pageId=29569243223&__hstc=82216777.f7f9fa89a9b3a83930a447116d9a1796.1589280439546.1590573594493.1590658690686.3&__hssc=82216777.1.1590658690686&__hsfp=1824881308&contentType=landing-page)
  - [Windows](https://go.ouster.io/cs/c/?cta_guid=57fe6e00-88d1-4ed7-bee5-e328b29c1b32&placement_guid=379ffee8-c96e-45ac-9e1f-d18460b50ad1&portal_id=5054152&canon=https%3A%2F%2Fgo.ouster.io%2Fbeta-program%2Fbeta-10%2F&redirect_url=APefjpHER-0TqvfY0lANWaXy6S7d20_XWfP5zKI8rEr_oo-Gntek_Db0wZ3sYuQ-0547IO1QNBx1Gi0oAHmLCrbQplHrtsUFQaDAt5pau0Np_WZGt-RV_IdqQ_SzDpnACTRg-mLZKp9cHpYIT0J-kVYx9xE8GkKOaYIl8Ue8WpCEiG_OCm-Uzf1um6lSSs1rx8wiwVtYpMl3fa9oLxl9rXZjkf-He-RY9Fuv43NW3s8mn7CLenvGqpKn9j9zTGy7uNtMj2_g9wESAidPFRXnGkIaYRaBc3hBeVhmjhpTdHHBvxN2s9L3Klq91A_CTp9-WR-KfsbETTKe&click=833c0b6e-02a3-4150-8fce-0d672ab1c4ec&hsutk=f7f9fa89a9b3a83930a447116d9a1796&signature=AAH58kFai_xEMjYEj2mTlY8honNOzoPcIg&pageId=29569243223&__hstc=82216777.f7f9fa89a9b3a83930a447116d9a1796.1589280439546.1590573594493.1590658690686.3&__hssc=82216777.1.1590658690686&__hsfp=1824881308&contentType=landing-page)
  - ~~B8：  https://pan.baidu.com/s/19zbZ-8Fnq9vbDfIKSNio-Q 提取码：3vor~~
- Apollo驱动：   https://github.com/ytldsimage/Ouster-fw1.14-for-apollo5.5
- [Autoware驱动](https://docs.wixstatic.com/ugd/984e93_b4e43111b1dd420cb3bc2c3e13071e71.pdf?index=true)：https://github.com/ytldsimage/kinect_ouster_autoware_driver