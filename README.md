# KSCoordinateConverter - 坐标转换工具
这个工具用来对地图坐标进行纠偏和加偏等操作，可以在GPS坐标（WGS-84）、火星坐标（GCJ-02）和百度坐标（BD-09）之间进行相互转换。更详细的介绍请查看我的博客文章：[GPS坐标纠偏和加偏](http://skx926.com/2017/03/04/gps-correction/)

### 用法示例（百度坐标转GPS坐标）
```objc
CLLocationCoordinate2D gpsCoordinate = [KSCoordinateConverter gpsCoordinateFromBDCoordinate:CLLocationCoordinate2DMake(22.592458, 113.998904)];
```
