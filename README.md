NaviCode is Android client for QR code based inside building navigation system.
It allowes to capture QR codes containing map name and coordinates of location attached to current code.
Captured code being decoded and corresponding map with marker at given coordinates is rendered. Map is searched at sdcard/navicode map on android device. 
If map is not found at specified folder it could be automatically downloaded from HTTP server (map repository).
Project depends on ZXing Decoder library and ImageView Zoom and Scroll library by Sephiroth.it. Correspondent jars/sources must be downloaded from respective authors repos. Links are given below. 

https://github.com/sephiroth74/ImageViewZoom
https://github.com/zxing/zxing