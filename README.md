# easy-nas

### 背景

云服务器(国内好像只有百度网盘了）保存文件不安全，速度受限，盗版电影、音乐失效....

手机内存太小...电脑硬盘太小...

5G时代来临，网络存储大有可为...

需要家用存储服务器，但是家庭服务器没有集群、组raid安全性不如（冷）备份, 通常家里的服务器可能是稳定性不高的(淘汰)电脑代替。

市面上常见的开软软件（如NextCloud)，不支持多块硬盘，如果硬盘损坏恢复机制不明确，依赖数据库，服务器奔溃可能会导致数据丢失。
太多额外不必要的功能（视频、团队合作、聊天室...)，最主要的是出了问题不好解决，并且扩展性差，不符合中国国情。

所以需要一款，定位家庭的服务器存储管理系统。

初期整体目标：

* 定位家庭
* 数据安全性、稳定性(系统奔溃了或者某个磁盘坏了，只要备份的地方数据还在就行)
* 易于扩展维护
* 支持硬盘横向扩展，（插入个硬盘，改一下配置就能用）
* 易于硬盘升级
* 支持常见的网盘功能
* 支持同步盘功能
* 符合中国国情（例如加密备份至百度网盘...）
* 迅雷离线下载
* 在线播放视频（电视和服务器在一个局域网内会超级快，相当于本地磁盘了）
* 系统足够的精简，对于普通用户只保留核心功能。
* ...

------
具体见[wiki](https://github.com/easy-nas/easy-nas-doc-and-plan/wiki)
