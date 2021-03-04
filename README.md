# Geofence
基于百度地图uid的地块地理围栏爬取代码

## 通过本程序主要可以完成以下任务：
- 通过名称寻找poi的uid，如通过"哈尔滨工业大学（深圳）"，将检索到uid为"d5577613b853c00e85420ef7"
- 通过uid寻找poi的AOI(Area of Interest)也就是常规意义的地理围栏
- 通过uid寻找poi的经纬度

## 详细代码
运行地点检索uid.ipynb即可

geo_boundary.py 用于地理围栏（AOI）爬取
transCoordinateSystem.py 用于坐标系转换（由百度坐标转换为WGS1984)

## 最终生成的文件均为shp文件
