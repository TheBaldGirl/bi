# LBS地图 {#concept_jbd_ghf_vdb .concept}

您如果已经阅读过[仪表板概述](cn.zh-CN/快速入门/报表制作/仪表板概述.md#)和[仪表板基本操作](cn.zh-CN/快速入门/报表制作/仪表板基本操作/仪表板基本操作.md#)，那么本章将为您介绍如何创建一个LBS地图。

与[气泡地图](cn.zh-CN/快速入门/报表制作/仪表板图表制作/气泡地图.md#)类似，LBS地图以一个地图轮廓为背景，用附着在地图上面的气泡来反映数据的大小。

LBS地图是由地理区域和LBS气泡大小构成的。地理区域由数据的维度决定，如省份；LBS气泡的大小由数据的度量决定，如运输成本，订单数量等。

## LBS地图须知 {#section_frt_hhf_vdb .section}

LBS地图的地理区域最多只能取1个维度，并且维度类型必须为地理信息，如区域，省，城市等；LBS气泡大小区域最少取1个，并且最多取5个度量。

以下场景均以company\_sales\_record数据集为例。

**场景示例：用LBS地图展示各省份订单数量和运输成本的比较。**

1.  登录Quick BI控制台。
2.  单击**数据集**，进入数据集管理页面。
3.  找到company\_sales\_record数据集，单击**新建仪表板**。
4.  在仪表板配置区，双击**LBS地图**图标。
5.  在数据标签页，选择需要的维度字段和度量字段。

    在维度列表中，找到**省份**，并将其添加到地理区域中；在度量列表中，找到**订单数量**和**运输成本**，并将依次添加到LBS气泡大小区域中，如下图所示。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9138/1807_zh-CN.png)

6.  单击**更新**，更新图表。
7.  单击样式标签页，更改图表的显示标题、布局和显示图例。

    在布局模块下，更改地图的底图、缩放和经纬度。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9138/6902_zh-CN.png)

    目前支持的地图底图包括高德电子地图、谷歌电子地图和GeoQ。

    ![](http://static-aliyun-doc.oss-cn-hangzhou.aliyuncs.com/assets/img/9138/6905_zh-CN.png)

8.  单击**保存**图标，保存仪表板。

如果您想删除当前图表，您可用鼠标指向图表的右上方，在自动弹出的菜单中选择**删除**，当前图表即可被删除。

