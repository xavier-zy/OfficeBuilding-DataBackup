# OfficeBuilding-DataBackup
OfficeBuilding 数据和备份
* **原始数据**，爬取自[安居客](https://shanghai.anjuke.com/)，并进行初步处理
* **SEARCHNEARBY**， 利用 百度API 搜索各楼盘周边信息所得
>     搜索范围：方圆600m
>     搜索内容：
>     酒店-hotel，公园-park，地铁站-underground，便利店-store，商场-mall

* **说明**（数据缺失条数：N个楼盘 **没有该周边信息** 或 **未成功获取该周边信息**）

|             |  hotel  |  park  | underground |  store  |   mall  |
| --------    | :-----: | :----: |   :-----:   | :----:  | :-----: |
| 数据缺失条数  |   38    |  525   |     443     |    65   |   246   |

