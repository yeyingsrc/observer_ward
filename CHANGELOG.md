# Change Log

<!-- next-header -->
## [2025.6.5] - 2025.6.5

### Fixes

- 修复nuclei单个参数解析缺失

## [2025.5.15] - 2025.5.15

### Fixes

- 添加tls握手超时

## [2025.5.14] - 2025.5.14

### Fixes

- 限制js跳转和30x跳转最大次数为10次

## [2025.4.6] - 2025.4.6

### Fixes

- fix socks5 proxy tls

## [2025.3.31] - 2025.3.31

### Fixes

- fix api-server async runtime

## [2025.3.23] - 2025.3.23

### Fixes

- 更新[slinger](https://github.com/emo-crab/slinger)，把之前的线程池修改为异步
- 添加`length`和`extractor`到csv表格
- 修改`body`调试为十六进制字符串
- 删除openssl依赖

## [2025.3.3] - 2025.3.3

### Fixes

- 修复/path拼接
- 优化slinger的原始字符串显示和比较

## [2025.2.20] - 2025.2.20

### Fixes

- 修复命令行未序列化参数被api配置覆盖掉的bug

## [2025.2.10] - 2025.2.10

### Fixes

- 添加mode参数，当目标没有协议的时候根据模式添加协议再尝试

## [2024.11.5] - 2024.11.5

### Fixes

- fix keepalive
- fix http version line read

## [2024.10.9] - 2024.10.9

### Fixes

- 将nuclei标签过滤表达式改为or

## [2024.8.16] - 2024.8.16

### Fixes

- 修复nuclei字段`cve-id`为`null`时解析错误
- 修复`aarch64`和`arm`架构自更新下载目标文件错误

## [2024.8.15] - 2024.8.15

### Fixes

- 修复tls握手阻塞

## [2024.8.7] - 2024.8.7

### Fixes

- 修复了favicon无法获取svg的hash

## [2024.8.6] - 2024.8.6

### Fixes

- 修复了favicon的url拼接的baseURL为当前响应URL
- 避免打印重复的目标和指纹

## [2024.7.31] - 2024.7.31

### Fixes

- 添加空间搜索引擎数据
- 添加unix-socket接口 socket over http
- 根据空间搜索引擎语法自动生成指纹规则

## [2024.7.25] - 2024.7.25

### Fixes

- 添加openssl配置到配置文件夹，在启动前设置`OPENSSL_CONF`配置文件路径
- 添加http请求缓存

## [2024.7.23] - 2024.7.23

### Fixes

- 修复http请求头多个set-cookie被覆盖问题
- 当本地没有指纹库时尝试更新指纹
- waf拦截挂起后最大超时设置

## [2024.7.22] - 2024.7.22

### Fixes

- 如果没有协议默认尝试https和http

## [2024.7.20] - 2024.7.20

### Fixes

- 修复部分没有端口的探针
- tcp添加超时计时器
- 更新依赖
- 替换输出换行符

## [Unreleased] - ReleaseDate

## [2024.7.19] - 2024.7.19

### Fixes

- 添加端口和rarity信息，用于根据端口排序选择优先探针
- 添加`name`字段到结果
- 默认不保存请求响应和证书
- 使用更小的数据类型减少内存

## [2024.7.18] - 2024.7.18

### Fixes

- 使用Arc减少克隆，优化内存
- 修复只有图标哈希规则时没有请求首页
- 只返回存活的结果

## [2024.7.1] - 2024.7.1

### Fixes

- 版本重构
