# 原始数据及抽样

原始数据基于[drms](https://docs.sunpy.org/projects/drms/en/stable/)工具包下载[HMI活动区补丁矢量场数据](http://jsoc.stanford.edu/ajax/lookdata.html?ds=hmi.sharp_cea_720s)，抽样规则如下：

| 2022年第一批计算信息 |               |
| -------------------- | ------------- |
| 时间范围             | 2010年-2019年 |
| 活动区序号范围       | 1-7400        |
| 时间间隔             | 96分钟        |
| 数据类型             | Bp，Bt，Br    |
| TODO其他规则         |               |

例子
```
hmi.sharp_cea_720s.4225.20140617_142400_TAI.Bp.fits
hmi.sharp_cea_720s.4225.20140617_142400_TAI.Bt.fits
hmi.sharp_cea_720s.4225.20140617_142400_TAI.Br.fits
```







