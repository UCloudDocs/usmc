# 步骤一 创建迁移计划

## 操作步骤

进入USMC控制台

![](http://usmc-doc.cn-bj.ufileos.com/stepone001.png)

由于USMC在使用过程中会使用到VPC和云服务器产品，如第一次使用USMC，需要进行一次授权。（如公私钥重置过需要重新授权）

![](http://usmc-doc.cn-bj.ufileos.com/stepone002.png)

创建迁移计划

![](http://usmc-doc.cn-bj.ufileos.com/createSet20210126.png)

### 填写表单

| 参数名   | 说明                                                         |
| -------- | ------------------------------------------------------------ |
| 计划名称 | 自定义的迁移计划名称|   
| 迁移源   | 源服务器位置类型。 阿里云：适合用户将阿里云VPC网络环境下主机进行整体迁移，可同时迁移VPC/子网；IDC：适合用户迁移友商经典网络或自建IDC场景。  |
| 网络类型 | 迁移采用的网络类型。 外网：通过外网迁移；内网：适用于UCloud 公有云平台内部迁移；专线：适用于通过专线将外部与UCloud公有云联通的场景。        |
| 源端地域 | 当迁移源为“阿里云”时， 需要选择地域  |
| 目标地域 | 目标服务器所在地域                             |

注：迁移计划以地域/项目为维度，如用户同地域同项目，建议使用同一个迁移计划。


![](http://usmc-doc.cn-bj.ufileos.com/stepone004.png)
