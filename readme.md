![](/logo.png)

# HSPMiner

用于显卡GPU的`Ethereum(以太坊)`挖矿软件。

## 下载地址

[从这里下载](https://github.com/hspminer/HSPMinerETH/releases)

## 社区支持

官方QQ群： 870349675

## 参考算力（默认频率）

| 算法             |  币种   | P106-100  |  P104-8G   |  1070ti  |  1080ti  |   2080   |
| :--------------- | :-----: | :-------: | :--------: | :------: | :------: | :------: |
| ...           |   ...   |   ...   |   ...    |  ...   |   ...   |   ...    |


## 功能特点

- 支持Windows和Linux
- 支持备用矿池的设置
- 支持SSL方式连接矿池
- 开发手续费:
  - 


## 配置需求

- **NVIDIA显卡驱动版本，大于等于377**
- 显卡参数需求:

|       算法       |  币种   | Compute Capability | 显存 (Win7 & Linux) | 显存 (Win10) |
| :--------------: | :-----: | :----------------: | :-----------------: | :----------: |



## 使用样例

#### Ethereum

- **f2pool:** HSPMiner.exe -epool eth.f2pool.com:8008 -ewal {替换钱包地址} -eworker {替换旷工名称} -epsw {替换密码} -logfile -api 0.0.0.0:16666

## 命令行参数

## API查询接口

### 网页监控

在浏览器中打开 http://api_host:port/ 启动网页监控.


## FAQ


#### 为什么我的矿池算力比本地算力低?

- `矿池的显示算力`


## 修改记录

#### HSPMinerEth 2.0.1 2019/1/16

- Add:相同算了的情况下，更加省电


