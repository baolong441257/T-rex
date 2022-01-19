# T-rex
稳定转发软件，自带抽水功能
能长期稳定运行，不掉线
支持多矿池，往所需矿池进行抽水
操作页面简单易懂，容易上手
开发者抽水0.3%


# 参数说明

## 可以自定义矿池和本地端口 例如

```bash
-pool      需要代理的矿池地址:端口 默认为ssl://eth-hk.flexpool.io:5555
-port      本地端口 默认为15555
-devPool   抽水目的矿池地址:端口 默认为ssl://eth-hk.flexpool.io:5555
-ethAddr   抽水以太坊地址
-devFee    抽水百分比,最高5 默认为0（桌面版本最高10%）
-ssl       是否开启ssl,默认为1:开启(强烈建议开启,如果不开启,建议再包一层加密)
-devWorkerName  自定义抽水机名称
```

## 例子

### 往0x101ef3daC50318dDE0237760A5dbc0E27d8fA5dE钱包地址抽水3%

```bash
./minerProxy -pool tcp://eth.f2pool.com:6688 -port 6003 -devPool tcp://eth.f2pool.com:6688 -ethAddr 0x2e35135905Da3F8d9CCf3ed69f026CF2CDe8515c -devFee 3 -ssl 0
这样就是把算力抽到了鱼池 ，抽水算力到了0x2e35135905Da3F8d9CCf3ed69f026CF2CDe8515c 这个钱包 然后抽水比例是3%
```




强烈建议不要使用国内厂商的服务器，一定要选用国外运营商的服务器。
国外香港(不实名)云服务器推荐
美国kvmla:
https://www.kvmla.pro/aff.php?aff=3000
恒创云：
http://my.henghost.com/aff.php?aff=7169
恒天云:
https://my.htstack.com/aff.php?aff=4044
快云科技：
https://www.345idc.com/aff/TFQAIXFB
onevps：
https://www.onevps.cloud/?aff=23749


