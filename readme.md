![](/logo.png)

# HSPMiner

GPU Miner for `Ethereum(以太坊)` mining.

## Download

[Download here](https://github.com/hspminer/HSPMinerETH/releases)

## Community support

QQ： 870349675

## Performance (stock frequency)

| Algorithm        |  Coin   | P106-100  |  P104-8G   |  1070ti  |  1080ti  |   2080   |
| :--------------- | :-----: | :-------: | :--------: | :------: | :------: | :------: |
| ethash           |   ETH   |   21.2M   |   34.5M    |  26.9M   |   46M    |   35M    |


## 功能特点

* Support Windows & Linux.
* Support backup mining pool configuration.
* Support SSL connection to mining pools.
* Dev Fee:
  - tensority_ethash 


## Requirements

- **NVIDIA Driver version: >= 377**.
- GPU Specific Requirements:

|    Algorithm     |  Coin   | Compute Capability | Memory (Win7 & Linux) | Memory (Win10) |
| :--------------: | :-----: | :----------------: | :-------------------: | :------------: |
|      ethash      |   ETH   | 6.0, 6.1, 7.0, 7.5 |          4GB          |      4GB       |



## Sample Usages

#### Ethereum

- **f2pool:** HSPMiner.exe -epool eth.f2pool.com:8008 -ewal {your_self_wallet_address} -eworker {your_self_worker_name} -epsw {your_self_worker_password} -logfile -api 0.0.0.0:16666
- **beepool:** HSPMinerETH.exe -epool eth-pool.beepool.org:9530 -ewal 0x6881a96B728097bbe78Af30459987Db2D1C996ca -eworker x -epsw passd -logfile -api 0.0.0.0:16666
- **sparkpool:** HSPMinerETH.exe -epool cn.sparkpool.com:3333 -ewal 0x6881a96B728097bbe78Af30459987Db2D1C996ca -eworker x -epsw passd -logfile -api 0.0.0.0:16666
- **sparkpool:** HSPMinerETH.exe -epool eth.uupool.cn:8008 -ewal 0x6881a96B728097bbe78Af30459987Db2D1C996ca -eworker x -epsw passd -logfile -api 0.0.0.0:16666


## CMD options：
  * -epool      pool address and port.
  * -ewal       your self wallet address.
  * -eworker    worker name.
  * -ewal       worker password.
  * -logfile    create log file.
  * -api        \<host:port>    The endpoint for serving REST API.
  



### Web Monitor

Open http://api_host:port/ in your browser to use web monitor.


## FAQ


#### 为什么我的矿池算力比本地算力低?

- `矿池的显示算力`


## Change Log

#### 2.0.9 2019/06/01
- fix:Remove usage time limit.

#### 2.0.8 2018/12/29
- fix:Extend the life cycle to June 1, 2019.

#### 2.0.7 2018/12/01
- fix:Fixed some problems with delayed display of mine pool.

#### 2.0.6 2018/11/25
- fix:Fix lost job problem.

#### 2.0.4 2018/11/23
- fix:Fixed sparkpool Mine Pool Protocol Error

#### 2.0.3 2018/11/22
- fix:Correct the problem that the delay rate is too high
- fix:Fixed some inpot pool protocol (user name mining) incompatibility issues.

#### 2.0.2 2018/11/18
- add:Adjust the job sent to the gpu process, and slightly improve the power.
- fix:Correct the problem of inaccurate calculation of local computing power.
- fix:Fixed the problem of high rejection rate in ponds such as f2pool.

#### 2.0.1 2018/11/16
- add:Add the display of the local calculation of the mining pool
- add:Adjust the nonce generation algorithm, and the job is faster and more stable under multiple GPUs.
- fix:Fixed a problem with some mine pool workers being wrong.
- fix:Adjust the interval and font color of some statistics display.

#### 2.0.0 2018/11/15
- add:The ETH algorithm is released, and the computing power remains the same as other mining software, while reducing power consumption by 8%-15%.




