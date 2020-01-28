By Roker2

## fingerprint.goodix.so

Need to change to NOP

NOP = 1F 20 03 D5 in HEX

Based on comparing Xiaomi Redmi 4X blobs

| Function                           | Patch place | Patch status (patched or not) |
| :--------------------------------- | :---------- | :---------------------------- |
| GxFpDevice::notify                 | B214        | yes                            |
| GxFpDevice::notify                 | B218        | yes                            |
| GxFpDevice::notify                 | B21C        | yes                            |
| GxFpDevice::notify                 | B220        | yes                            |
| GxFpDevice::notify                 | B224        | yes                            |
| GxFpDevice::notify                 | B228        | yes                            |
| GxFpDevice::notify                 | B22C        | yes                            |
| GxFpDevice::notify                 | B234        | yes                            |
| GxFpDevice::notify                 | B238        | yes                            |
| GxFpDevice::notify                 | B23C        | yes                            |
| GxFpDevice::notify                 | B240        | yes                            |
| GxFpDevice::notifyData             | AE2C        | yes                            |
| GxFpDevice::notifyData             | AE30        | yes                            |
| GxFpDevice::notifyData             | AE34        | yes                            |
| GxFpDevice::notifyData             | AE38        | yes                            |
| GxFpDevice::notifyData             | AE3C        | yes                            |
| GxFpDevice::notifyData             | AE40        | yes                            |
| GxFpDevice::notifyData             | AE44        | yes                            |
| GxFpDevice::notifyData             | AE4C        | yes                            |
| GxFpDevice::notifyData             | AE50        | yes                            |
| GxFpDevice::notifyData             | AE54        | yes                            |
| GxFpDevice::notifyData             | AE58        | yes                            |
| goodix_sensor_init                 | BA60        | yes                            |
| goodix_sensor_init                 | BA64        | yes                            |
| goodix_sensor_init                 | BA68        | yes                            |
| goodix_sensor_init                 | BA6C        | yes                            |
| goodix_sensor_init                 | BAF0        | yes                            |
| goodix_sensor_init                 | BAF4        | yes                            |
| goodix_sensor_init                 | BAF8        | yes                            |
| goodix_sensor_init                 | BAFC        | yes                            |
| goodix_sensor_init                 | BB00        | yes                            |
| goodix_sensor_init                 | BB04        | yes                            |
| goodix_sensor_init                 | BB08        | yes                            |
| goodix_sensor_init                 | BB9C        | yes                            |
| goodix_sensor_init                 | BBA0        | yes                            |
| goodix_sensor_init                 | BBA4        | yes                            |
| goodix_sensor_init                 | BBA8        | yes                            |
| goodix_sensor_init                 | BBAC        | yes                            |
| goodix_sensor_init                 | BBB0        | yes                            |
| goodix_sensor_init                 | BBB4        | yes                            |
| goodix_sensor_init                 | BBCC        | yes                            |
| goodix_sensor_init                 | BBD0        | yes                            |
| goodix_sensor_init                 | BBD4        | yes                            |
| goodix_sensor_init                 | BBD8        | yes                            |
| goodix_sensor_init                 | BBDC        | yes                            |
| goodix_sensor_init                 | BBE0        | yes                            |
| goodix_sensor_init                 | BBE4        | yes                            |
| goodix_sensor_init                 | BBE8        | yes                            |
| goodix_sensor_init                 | BBEC        | yes                            |
| goodix_sensor_init                 | BBF0        | yes                            |
| goodix_sensor_init                 | BBF4        | yes                            |
| goodix_sensor_init                 | BC00        | yes                            |
| goodix_sensor_init                 | BC04        | yes                            |
| goodix_sensor_init                 | BC08        | yes                            |
| goodix_sensor_init                 | BC0C        | yes                            |
| goodix_sensor_init                 | BC10        | yes                            |
| goodix_sensor_init                 | BC14        | yes                            |
| goodix_sensor_init                 | BC18        | yes                            |

12 functions, 58 patch places