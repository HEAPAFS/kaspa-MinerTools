# kaspa—MinerTools
Kaspa一键挖矿
随手写的启动器，图形界面，方便配置参数，一键配置参数以及开始

在Release下载文件，或者

##  使用方式 

第一步配置节点，对空间以及网络要求较高，可以等一等其他人创立的公共节点。直接将节点的地址以及端口填入启动器即可。

第二步建立钱包，需要注意中文教程有些过时，如果没有show-address是空的话，先运行 new-address命令。

第三步一键启动，如果前两步已经配置好，直接运行release里的文件即可

端口默认端口空着就可以
![图片alt](/readme/usage.jpg "图片title")


具体可以参考官方文档。
https://github.com/kaspanet/docs/blob/main/Getting%20Started/Full%20Node%20Installation.md

中文教程：
https://mp.weixin.qq.com/s/KFwyfnRv5glxXuhaDHlJMQ



## 注意事项 ！
请使用官方提供的内核！官方内核是开源的，最安全，release里面提供的即是官方内核（不同版本，按需求选择，最新版本似乎不是很稳定），如果不放心，自行下载即可。

有些版本似乎兼容有问题，可以尝试一下不同版本，以及升级驱动
    N卡要求 驱动版本490一上

CPU版本 https://github.com/elichai/kaspa-miner/releases/tag/v0.2.1

GPU版本 https://github.com/tmrlvi/kaspa-miner/releases

## 打赏 抽水
启动器是开源的，不会有任何暗抽，强制抽水。
默认写了个0.5恰烂钱打赏 （0.5%，一天只有10分钟，真的有用吗。。。
舍不得的话改成0即可。

    注意 如果什么都不设置的话，GPU版本的核心，官方默认开启了1%的打赏（这不是强制的，使用启动器的话就默认就只有上面说的0.5%，
    CPU核心默认不开启。
    
    目前这些都不是强制的，算是对开发者的支持。

官方的核心运行时会显示抽水比例以及抽水账户，不用担心暗抽。
![图片alt](/readme/1.png "图片title")


如果你觉得有帮助 欢迎直接支持一下

kaspa:qpjrxsq6e06l09agkj7qyzqz59ydxvvlqlf7gmu6q5mm4au0j0de2rr9dk3qv

## 下一阶段目标
加入钱包功能