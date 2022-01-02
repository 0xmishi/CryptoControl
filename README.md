# CryptoControl
PC版，监控链上使用uniswapV2，uniswapV3协议的任意swap兑换记录
支持ETH,BSC,Polygon,HECO,OEC..
![Image text](https://raw.githubusercontent.com/0xmishi/CryptoControl/main/screen.png)
## 下载最新版本
 > [**Releases**](https://github.com/0xmishi/CryptoControl/releases)中下载打包好的压缩包
## 使用帮助
### 监控指定token
***
- pairAddress输入框填写pairAddress地址(池子地址)，非token合约地址.
- ETH主网直接填写pairAddress即可,**Polygon链地址前面添加MATIC,BSC链地址前面添加BNB,OEC链地址前面添加OKT,Heco链地址前面添加HT**
- pair地址获取:以下地址或软件右击复制pair地址等其他方法
https://info.uniswap.org/#/pools
https://analytics.sushi.com/
https://pancakeswap.finance/info/pools
...
### 监控主网
***
>暂时只支持ETH链上的监控，实时监控链上所有V2,V3协议的兑换记录，过滤稳定币(ETH,USDT,USDC,DAI==)。
### 小技巧
***
1. **双击选中的兑换记录**:会自动跳转区块链浏览器，查看详细信息.
2. **右击菜单高亮大额**:填写设置的金额，同时勾选声音提醒，大额时候会声音提醒.
3. **成交量统计**:统计当前交易频率最高的30个token信息
4. **过滤小额**:监控全网的情况下，过滤掉低于1 ETH/3000 USD的交易
5. **Mark**:标记指定的信息
6. **热门币种提醒**:监控全网的情况下，状态栏显示前1个小时和前2个小时热门币种
7. 其他。。

## 使用异常
+ 如出现启动出错,请安装`.net framework 4.5`
+ 其他bug，twitter私信@**crypto_mishi**，不定时回复.
***
> **Note:** 玩土狗的时候瞎写的，本软件完全免费，谨防受骗！
> 希望对你有一点点帮助！