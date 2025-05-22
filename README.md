Fork From xiaozhi project

# 使用说明

1. IDF配置芯片选择esp32s3, IDF版本需要用5.4.1
2. IDF menuconfig搜索boardtype，选择“正点原子ATK-ESP32S3自定义”
3. 编译、烧录
4. 需要下载 ESP32的蓝牙配置app
   [https://github.com/espressif/esp-idf-provisioning-android/releases/tag/Provisioning_App_Release_2.2.3](https://github.com/espressif/esp-idf-provisioning-android/releases/tag/Provisioning_App_Release_2.2.3)
   配置WIFI时，
   1. settings关闭Encrypted Communication
   2. 扫描需要连接的设备，选No QR Code
   3. Prefix选my_device
