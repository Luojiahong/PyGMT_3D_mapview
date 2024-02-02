# PyGMT绘制三维剖面图
使用PyGMT对地震三维速度（lon,lat,dep,value）进行三维切片并绘制。
# 软件需求
```python
import pandas as pd 
import xarray as xr 
import pygmt
import numpy as np
```
## mapview_3Di.ipynb
使用的速度模型： 
https://github.com/ShouchengHan/USTClitho2.0/blob/main/USTClitho2.0.wrst.sea_level.txt
使用PyGMT提取三维切片并绘制三维速度模型，实现按照经纬度截取剖面，对地形按照一定的形状裁剪。

## mapview_3d_earthquake.ipynb
在上一个例子中增加地震分布剖面。地震数据：http://cses.ac.cn/sjcp/ggmx/2021/132.shtml



