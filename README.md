# ESP32Cam-PyController
 Control ESP32Cam image/stream settings with python


## Settings

Only  integer values

| Setting  | Value   | |
|:-:|:-:| :-:| 
| quality  | 0 - 63 | |
| denoise  |  0 = disable , 1 = enable | |
| contrast  | -2 to 2  | |
| brightness  | -2 to 2  | |
|  saturation | -2 to 2  | | 
| colorbar  |  0 = disable , 1 = enable | | 
|  special_effect | 0 to 6   (0 - No Effect, 1 - Negative, 2 - Grayscale, 3 - Red Tint, 4 - Green Tint, 5 - Blue Tint, 6 - Sepia)  | | 
| whitebal  |  0 = disable , 1 = enable | | 
| awb_gain  |  0 = disable , 1 = enable | | 
|  wb_mode |  0 to 4 - if awb_gain enabled (0 - Auto, 1 - Sunny, 2 - Cloudy, 3 - Office, 4 - Home) | | 
| exposure_ctrl  |  0 = manual , 1 = auto | no manual exposure control support | 
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

| Value  | size  |
|:-:|:-:|
| QQVGA2  | 128x160  |
|  QCIF |  176x144 |
| HQVGA  | 240x176  |
| QVGA  | 320x240  |
|  CIF |  400x296 |
|  VGA |  640x480 |
|  SVGA | 800x600  |
|  XGA |  1024x768 |
|  SXGA | 1280x1024  |
|  UXGA | 1600x1200  |


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