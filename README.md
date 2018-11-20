题目：kepler.gl：交通数据可视化分析平台介绍及典型案例
====

利用kepler.gl进行交通数据可视化分析和探索

特点
-------
1. 无需编程，上手简单

2. 适用于大多数交通出行的业务场景

3. 适用于分析、研究、监测等应用场景

4. 高效、安全，支持大数据集，美观有设计感


相关链接
-------
[kepler.gl平台](http://kepler.gl/#/)

[kepler.gl项目主页](https://github.com/uber/kepler.gl/blob/master/docs/a-introduction.md)

[kepler.gl官网](http://kepler.gl/)

[uber可视化团队](http://vis.gl/)


预备内容
-------
* 0.0 wgs84坐标系

* 0.1 mapbox

[mapbox 官网](http://www.mapbox.com/)

[mapbox studio](http://www.mapbox.com/studio/)

>默认地图参数

>>access_token=pk.eyJ1Ijoid3V4aW5yYW4iLCJhIjoiY2prOTJ5amdsMGZobTNscXhvd3ZyM3hiOSJ9.GRhFcBxDyhsBSwzElOEeSA

>>mapbox://styles/wuxinran/cjnmqpp8t0xbs2qlgpd8rwcoh


数据分析
-------
* 1.0 地铁出入站,3d六边形柱状图

* 1.1 地铁进出站分屏观看，调整半径level（5km时一致由城市决定）

* 1.2.1 自行车hubs点图,使用opacity & additive 配置 

* 1.2.2 自行车hubs的3d六边形柱状图，在时间轴播放

* 1.3 自行车autority/hubs热力图分屏观看，调整半径level（5km时一致由城市决定）

* 1.4 自行车和地铁 平六边形图，不同颜色，切换校验


geojson输入
-------
* 2.0 [geojson](http://geojson.io/)

* 2.1 geojson导入线路热力图，并进行时间轴播放


关联分析
-------
* 3.0 建立地铁进出站关联arc，在3d模式下用brush查看

* 3.1 建立自行车家庭工作地关联arc，在3d模式下用brush查看

* 3.2 地铁、自行车 平六边形图，不同颜色，切换叠加观测。家|早高峰入站 / 工作地|早高峰出站


数据下载
-------
mobike hubs/authority 数据(https://pan.baidu.com/s/13ntm92gBxA0PnKJNWm0baA)

metro morning afc 数据(https://pan.baidu.com/s/1GxiAxhDixRYghAiA0JFq9w)

北京1号线 geojson 数据(https://github.com/wuxinran2001/wuxinran2001.github.io/blob/master/tmp1.geojson)

