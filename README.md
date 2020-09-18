# ESP32Cam-PyController
 Control ESP32Cam image/stream settings with python


## Settings

Only  integer values

| Setting  | Value   | Description |
|:-:|:-:| :-:| 
| quality  | 0 - 63 | image quality, lower better |
| denoise  |  0 = disable , 1 = enable ||
| contrast  | -2 to 2  |  |
| brightness  | -2 to 2  | |
|  saturation | -2 to 2  | | 
| colorbar  |  0 = disable , 1 = enable | adds colorbar to image | 
|  special_effect | 0 to 6   (0 - No Effect, 1 - Negative, 2 - Grayscale, 3 - Red Tint, 4 - Green Tint, 5 - Blue Tint, 6 - Sepia)  | | 
| whitebal  |  0 = disable , 1 = enable | white balance | 
| awb_gain  |  0 = disable , 1 = enable | Automatic White Balance gain | 
|  wb_mode |  0 to 4  (0 - Auto, 1 - Sunny, 2 - Cloudy, 3 - Office, 4 - Home) | if awb_gain enabled | 
|  aec |  0 = manual , 1 = auto | automatic exposure control | 
|  aec2 |  0 = disable , 1 = enable | | 
| ae_level  | -2 to 2  | | 
| aec_value  | 0 to 1200  | | 
|  gain_ctrl |  0 = disable , 1 = enable | | 
| agc_gain  |  0 to 30 | | 
| gainceiling  |  0 to 6  | | 
| bpc  |  0 = disable , 1 = enable | | 
| wpc  |  0 = disable , 1 = enable | | 
| raw_gma  |  0 = disable , 1 = enable | | 
| lenc  |  0 = disable , 1 = enable | | 
| hmirror  |  0 = disable , 1 = enable | | 
| vflip  |  0 = disable , 1 = enable | | 
| dcw  |  0 = disable , 1 = enable | | 
| colorbar  |  0 = disable , 1 = enable | | 
 
Framesize

|Value| Resolution  | size  |
||:-:|:-:|
|0| QQVGA  | 160x120  |
|1| QQVGA2  | 128x160  |
|2|  QCIF |  176x144 |
|3| HQVGA  | 240x176  |
|4| QVGA  | 320x240  |
|5|  CIF |  400x296 |
|6|  VGA |  640x480 |
|7|  SVGA | 800x600  |
|8|  XGA |  1024x768 |
|9|  SXGA | 1280x1024  |
|10|  UXGA | 1600x1200  |


reference : https://lang-ship.com/reference/ESP32/latest/sensor_8h_source.html#l00107


exposure : https://github.com/igrr/esp32-cam-demo/issues/81 

https://esp32.com/viewtopic.php?f=19&t=11126&sid=73b833e5d4122651dba9e2653ee5f469&start=30

https://www.arducam.com/manual-exposure-ov2640/

 <!-- FRAMESIZE_QQVGA,    // 160x120
     FRAMESIZE_QQVGA2,   // 128x160
     FRAMESIZE_QCIF,     // 176x144
     FRAMESIZE_HQVGA,    // 240x176
     FRAMESIZE_QVGA,     // 320x240
     FRAMESIZE_CIF,      // 400x296
     FRAMESIZE_VGA,      // 640x480
     FRAMESIZE_SVGA,     // 800x600
     FRAMESIZE_XGA,      // 1024x768
     FRAMESIZE_SXGA,     // 1280x1024
     FRAMESIZE_UXGA,     // 1600x1200
     FRAMESIZE_QXGA,     // 2048*1536 -->