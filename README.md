# NLFFF-3D-Dataset
**太阳活动区非线性无力场3D数据集** 

在线文档：https://nlfff-3d-dataset.readthedocs.io/zh_CN/latest/

太阳活动区非线性无力场3D数据集，使用改写[Thomas Wiegelmann](mailto:wiegelmann@mps.mpg.de)的LINFF(An IDL-widget program for force-free coronal magnetic fields.)程序，对2010到2019年[HMI活动区补丁矢量场数据](http://jsoc.stanford.edu/ajax/lookdata.html?ds=hmi.sharp_cea_720s)进行抽样预处理和计算。

整个处理流程如下：

![workflow.drawio](docs/img/workflow.drawio.svg)

2010到2019年的HMI原始数据抽样细节将在**原始数据及抽样**部分进行介绍。程序改写内容包括，改写由IDL语言编写预处理等部分代码，需要配置自定义参数部分的代码，改写细节将在后面**数据预处理及计算**部分进行介绍。产品数据及使用方法可以在**产品数据及使用**和**工具包**部分查看；数据使用和合作申请详见**数据支持**，基于该数据库的相关成果和合作详见**成果与引用**。

| 2022年第一批计算信息 |                       |
| -------------------- | --------------------- |
| 数据时间跨度         | 2010-2019             |
| 数据计算跨度         | 2021.12.10-2022.03.19 |
| 数据总存储量         | ~160T                 |
| 数据磁图总量         | ~74000                |
|                      |                       |

