# 支持的场景

| 源 | 目标 | 迁移源类型选择 |   
| --- | --- | --- |
| 阿里云 | UCloud 公有云 | 阿里云 |
| IDC 物理机 | UCloud 公有云 | IDC |
| IDC VMware | UCloud 公有云 | IDC |
| AWS、腾讯云等其它云平台 | UCloud 公有云 | IDC |
| UCloud 物理云主机 | UCloud 公有云 |IDC | 
| UCloud 云主机 | UCloud 公有云 |IDC | 

# 支持的操作系统

USMC客户端适用于下列操作系统。

## Linux

| 源操作系统版本 | 源系统架构 | 目标UCloud快杰云主机操作系统版本 | 目标UCloud快杰云主机系统架构 |   
| --- | --- | --- | --- |
| CentOS 6.x | x86_64 | CentOS 6.10 | x86_64 |
| CentOS 7.x | x86_64 | CentOS 7.6 | x86_64 |
| CentOS 8.x | x86_64 | CentOS 8.0 | x86_64 |
| Ubuntu 14.04 | x86_64 | Ubuntu 14.04 | x86_64 |
| Ubuntu 16.04 | x86_64 | Ubuntu 16.04 | x86_64 |
| Ubuntu 18.04 | x86_64 | Ubuntu 18.04 | x86_64 | 

# 功能限制

- 目前仅支持迁移到UCloud公有云快杰云主机
- 系统盘数据量不能超过400GB，数据盘不能超过2TB
- USMC不迁移内存中的数据，所以不支持迁移Redis等内存数据库产品。
- USMC不迁移主机名，所以不支持迁移RabbitMQ等依赖hostname的产品。
- 如果源主机上部署有数据库(MySQL\PostgreSQL\MongoDB\TiDB等)， 建议使用UDTS先迁移数据库
