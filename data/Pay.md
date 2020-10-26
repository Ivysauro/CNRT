# 轨道交通支付方式/ Payment Methods for Rail Transit

地面公交支付方式点[这里](https://ivysauro.github.io/CNRT/data/Bus%20Pay)跳转/ For Buses, go to [HERE](https://ivysauro.github.io/CNRT/data/Bus%20Pay)

## 目录/ Content
- [过闸/ Passing Gate](#过闸-passing-gate)
- [购票/ Tickets](#购票-tickets)
- [充值/ Charging](#充值-charging)
- [开放性评分/ Open Score](#开放性评分-open-score)
- [感谢/ Thanks](#感谢-thanks)

## 过闸/ Passing Gate

### 图例/ Legend

| 标识/ Logo | 中文/ Chinese | 英文/ English |
| :-: | :- | :- |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/T-Union.png" width="40" hegiht="40" alt="T-Union"/> | [交通联合](https://zh.wikipedia.org/wiki/%E4%BA%A4%E9%80%9A%E8%81%94%E5%90%88) | [T-Union](https://en.wikipedia.org/wiki/China_T-union) |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/Unionpay NFC.png" width="40" hegiht="40" alt="Unionpay Quickpass"/> | [银联闪付](https://zh.wikipedia.org/wiki/%E9%97%AA%E4%BB%98#%E4%BA%91%E9%97%AA%E4%BB%98) | [Unionpay Quickpass](https://en.wikipedia.org/wiki/UnionPay#QuickPass) |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/Alipay.png" width="30" hegiht="30" alt="Alipay Transit QR Code"/> | [支付宝乘车码](https://zh.wikipedia.org/wiki/%E9%A8%B0%E8%A8%8A%E4%B9%98%E8%BB%8A%E7%A2%BC#%E7%9B%B8%E9%97%9C%E7%94%A2%E5%93%81) | Alipay Transit QR Code |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/WeChat Pay.png" width="25" hegiht="25" alt="WeChat Pay Transit QR Code"/> | [微信乘车码](https://zh.wikipedia.org/wiki/%E9%A8%B0%E8%A8%8A%E4%B9%98%E8%BB%8A%E7%A2%BC) | WeChat Pay Transit QR Code |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/Unionpay.png" width="25" hegiht="25" alt="Unionpay Transit QR Code"/> | [云闪付乘车码](https://zh.wikipedia.org/wiki/%E9%A8%B0%E8%A8%8A%E4%B9%98%E8%BB%8A%E7%A2%BC#%E7%9B%B8%E9%97%9C%E7%94%A2%E5%93%81) | Unionpay Transit QR Code |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/Rail Transit.png" width="25" hegiht="25" alt="Transit QR Code of Official Apps"/> | 官方应用乘车码 | Transit QR Code of Official Apps |

*[银联闪付]: 指银联云闪付（联机闪付），不包括电子现金（脱机闪付）
*[银联二维码]: 指符合银联标准的二维码，可在银联指定的应用内使用（如云闪付、各银行客户端、京东、美团等） 

| 图标/ Icon | 中文/ Chinese | 英文/ English |
| :-: | :- | :- |
| ✅ | 完全支持 | Full Support |
| ⭕ | 有条件的支持 | Conditional Support |
| 🕓 | 即将上线 | Coming Soon |
| 💥 | 新变动 | New Update |

### 主表/ Main Content

| 城市/ City | <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/T-Union.png" width="40" hegiht="40" alt="T-Union"/> | <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/Unionpay NFC.png" width="40" hegiht="40" alt="Unionpay Quickpass"/> | <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/Alipay.png" width="30" hegiht="30" alt="Alipay Transit QR Code"/> | <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/WeChat Pay.png" width="25" hegiht="25" alt="WeChat Pay Transit QR Code"/> | <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/Unionpay.png" width="25" hegiht="25" alt="Unionpay Transit QR Code"/> | <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/Rail Transit.png" width="25" hegiht="25" alt="Transit QR Code of Official Apps"/> | 其他/ Other |
| ---------  | :-----: | :------:  | :---------: | :-------: | :-------: | :-----------: | :- |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/bj.gif" width="20" hegiht="20"/>北京/ Beijing | ⭕[^bj] | 🕓 | | | ✅ | ✅ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/tj.gif" width="20" hegiht="20"/>天津/ Tianjin | ✅ | ✅ | | | | ✅ | |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/sh.gif" width="20" hegiht="20"/>上海/ Shanghai[^csh] | ✅[^sh1] | ⭕[^sh2] | | | | ✅ | |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/gz.gif" width="20" hegiht="20"/>广州/ Guangzhou[^cgz] | ✅ | ⭕[^gz] | ✅ | ✅ | | ✅ | |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/cc.gif" width="20" hegiht="20"/>长春/ Changchun | ✅ | ✅ | | | ✅ | ✅ | |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/dl.gif" width="20" hegiht="20"/>大连/ Dalian | ✅ | ✅ | | | | ✅ | |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/wh.gif" width="20" hegiht="20"/>武汉/ Wuhan | 🕓 | 🕓 | | | | ✅ | |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/cq.gif" width="20" hegiht="20"/>重庆/ Chongqing | 🕓 | 🕓 | ✅ | ✅ | ✅ | ✅ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/sz.gif" width="20" hegiht="20"/>深圳/ Shenzhen | ✅ | ✅ | | ✅ | ✅ | ✅ | |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/nj.gif" width="20" hegiht="20"/>南京/ Nanjing | ✅ | ✅ | ✅ | | ✅ | ✅ | 苏宁支付 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/sy.gif" width="20" hegiht="20"/>沈阳/ Shenyang | ✅ | | ✅ | ✅ | ✅ | ✅ | |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/cd.gif" width="20" hegiht="20"/>成都/ Chengdu | 🕓 | | ✅💥 | | ✅ | ✅ | |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/xa.gif" width="20" hegiht="20"/>西安/ Xi'an | ✅ | | ✅ | ✅ | ✅ | ✅ | |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/suz.gif" width="20" hegiht="20"/>苏州/ Suzhou | ✅ | | | | | ✅ | |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/km.gif" width="20" hegiht="20"/>昆明/ Kunming | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/hz.gif" width="20" hegiht="20"/>杭州/ Hangzhou | ✅ | ✅ | ✅ | | ✅ | ✅ | |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/hrb.gif" width="20" hegiht="20"/>哈尔滨/ Harbin | ⭕[^hrb1] | ⭕[^hrb2] | ✅ | ✅ | ✅ | ✅ | |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/zz.gif" width="20" hegiht="20"/>郑州/ Zhengzhou | ✅ | | ✅ | ✅ | ✅ | ✅ | |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/cs.gif" width="20" hegiht="20"/>长沙/ Changsha[^ccs] | ✅ | | | | | ✅ | 和包支付、闪客蜂 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/nb.gif" width="20" hegiht="20"/>宁波/ Ningbo | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/wx.gif" width="20" hegiht="20"/>无锡/ Wuxi | ✅ | | | | | ✅ | |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/qd.gif" width="20" hegiht="20"/>青岛/ Qingdao | ✅ | | | | | ✅ | |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/nc.gif" width="20" hegiht="20"/>南昌/ Nanchang | ✅ | ✅ | ✅ | | ✅ | ✅ | |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/fz.gif" width="20" hegiht="20"/>福州/ Fuzhou | ✅ | | | | | ✅ | |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/dg.gif" width="20" hegiht="20"/>东莞/ Dongguan | 🕓 | ⭕[^dg] | | | | ✅ | |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/nn.gif" width="20" hegiht="20"/>南宁/ Nanning | ✅ | ⭕[^nn] | | | | ✅ | |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/hf.gif" width="20" hegiht="20"/>合肥/ Hefei | ✅ | ✅ | | | | ✅ | |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/sjz.gif" width="20" hegiht="20"/>石家庄/ Shijiazhuang | ✅ | | | | | ✅ | |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/gy.gif" width="20" hegiht="20"/>贵阳/ Guiyang | ✅ | | | | | ✅ | |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/xm.gif" width="20" hegiht="20"/>厦门/ Xiamen | ✅ | ✅ | ✅ | | ✅ | ✅ | |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/wlmq.gif" width="20" hegiht="20"/>乌鲁木齐/ Urumqi | | | | | | ✅ | |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/wz.gif" width="20" hegiht="20"/>温州/ Wenzhou | | ✅ | | | | ✅ | |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/jn.gif" width="20" hegiht="20"/>济南/ Jinan | ✅ | ✅ | | | | ✅ | |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/lz.gif" width="20" hegiht="20"/>兰州/ Lanzhou | ✅ | ⭕[^lz] | ✅ | ✅ | | ✅ | 翼支付 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/cz.gif" width="20" hegiht="20"/>常州/ Changzhou | ✅ | ✅ | | | | ✅ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/xz.gif" width="20" hegiht="20"/>徐州/ Xuzhou | ✅ | ✅ | | | | ✅ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/hhht.gif" width="20" hegiht="20"/>呼和浩特/ Hohhot | 🕓 | | | | ✅💥 | ✅ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/hk.gif" width="20" hegiht="20"/>香港/ Hong Kong | | | ⭕[^hk] | | 🕓 | |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/mo.gif" width="20" hegiht="20"/>澳门/ Macao | | | | | | | |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/tp.gif" width="20" hegiht="20"/>台北/ Taipei[^ctp] | | 🕓 | | | | ⭕[^tp] | |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/kh.gif" width="20" hegiht="20"/>高雄/ Kaohsiung | | ⭕[^kh] | | | ✅ | ✅ | Mastercard |
| | <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/T-Union.png" width="40" hegiht="40" alt="T-Union"/> | <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/Unionpay NFC.png" width="40" hegiht="40" alt="Unionpay Quickpass"/> | <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/Alipay.png" width="30" hegiht="30" alt="Alipay Transit QR Code"/> | <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/WeChat Pay.png" width="25" hegiht="25" alt="WeChat Pay Transit QR Code"/> | <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/Unionpay.png" width="25" hegiht="25" alt="Unionpay Transit QR Code"/> | <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/Rail Transit.png" width="25" hegiht="25" alt="Transit QR Code of Official Apps"/> |

[^bj]: 北京：交通联合采用[专版白名单](https://mp.weixin.qq.com/s/JF4pULn90EA7S5lUWaxNyw)/ [Special whitelist](https://mp.weixin.qq.com/s/JF4pULn90EA7S5lUWaxNyw) in T-Union

[^sh1]: 上海：异地交通联合卡可享受虚拟换乘优惠；磁悬浮暂不支持交通联合/ Non-local T-Union card can enjoy virtual-transfer discount; Maglev doesn't accept T-Union

[^sh2]: 上海：仅磁悬浮支持银联信用卡闪付/ Only Shanghai Maglev accept credit card Quickpass

[^gz]: 广州：银联闪付仅支持[信用卡](http://cs.gzmtr.com/ckfw/pwzy/201811/t20181106_60161.htm)和招行借记卡（APM无此限制）/ Only [credit card](http://cs.gzmtr.com/ckfw/pwzy/201811/t20181106_60161.htm) and CMB debit card accepted in Quickpass (APM accept all cards)

[^hrb1]: 哈尔滨：交通联合采用[专版黑名单](https://www.zhihu.com/question/312911617)/ [Special Blacklist](https://www.zhihu.com/question/312911617) in T-Union

[^hrb2]: 哈尔滨：银联闪付仅支持工行、交行、广发、浦发、邮储借记卡信用卡和招商银行借记卡/ Only CMB debit card and ICBC, COM, CGB, SPDB, CPG debit or credit cards accepted in Qucikpass

[^dg]: 东莞：银联闪付仅支持东莞通合作银行/ Only banks that cooperates with DongguanTong accepted in Quickpass

[^nn]: 南宁：银联闪付仅支持除浦发、华夏以外的信用卡和交行、招行借记卡/ Only credit card(except SPDB, HXB) and COM, CMB debit card accepted in Quickpass

[^lz]: 兰州：银联闪付仅支持信用卡/ Only credit card accepted in Quickpass

[^hk]: 香港：支付宝乘车码仅支持AlipayHk（即支付宝香港版）

[^tp]: 台北：仅桃园机场捷运支持在线购票后扫码过闸/ Only Taoyuan Airport MRT support after buying ticket online

[^kh]: 高雄：银联闪付仅支持信用卡/ Only credit card accepted in Quickpass

## 购票/ Tickets

### 图例/ Legend

| 标识/ Logo | 中文/ Chinese | 英文/ English |
| :-: | :- | :- |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/Alipay.png" width="30" hegiht="30" alt="Alipay"/> | 支付宝 | Alipay |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/WeChat Pay.png" width="25" hegiht="25" alt="WeChat Pay"/> | 微信支付 | WeChat Pay |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/Unionpay QR.png" width="40" hegiht="40" alt="Unionpay QR Code"/> | 银联二维码 | Unionpay QR Code |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/Unionpay NFC.png" width="40" hegiht="40" alt="Unionpay Quickpass"/> | [银联闪付](https://zh.wikipedia.org/wiki/%E9%97%AA%E4%BB%98#%E4%BA%91%E9%97%AA%E4%BB%98) | [Unionpay Quickpass](https://en.wikipedia.org/wiki/UnionPay#QuickPass) |
| 💳 | 交通卡 | Transit Card |

| 图标/ Icon | 中文/ Chinese | 英文/ English |
| :-: | :- | :- |
| ✅ | 完全支持 | Full Supprot |
| ⭕ | 仅限部分车站 | Only in some stations |

### 线下购票/ Buying Tickets on machines 

包括自助购票和服务中心购票/ Be applicable to buying tickets on TVM and Service Center

各地轨道交通官方应用线下扫码购票数据暂缺/ No data for scanning QR code by local official apps so far

| 城市/ City | <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/Alipay.png" width="30" hegiht="30" alt="Alipay"/> | <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/WeChat Pay.png" width="25" hegiht="25" alt="WeChat Pay"/> | <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/Unionpay QR.png" width="40" hegiht="40" alt="Unionpay QR Code"/> | <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/Unionpay NFC.png" width="40" hegiht="40" alt="Unionpay Quickpass"/> | 💳 |
| --------- | :----------: | :-------------: | :----------------: | :-----------------: | :-: |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/bj.gif" width="20" hegiht="20"/>北京/ Beijing | ✅ | ✅ | ✅ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/tj.gif" width="20" hegiht="20"/>天津/ Tianjin | ✅ | ✅ | ✅ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/sh.gif" width="20" hegiht="20"/>上海/ Shanghai[^csh] | ✅ | ✅ | ✅ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/gz.gif" width="20" hegiht="20"/>广州/ Guangzhou[^cgz] | ✅ | ✅ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/cc.gif" width="20" hegiht="20"/>长春/ Changchun | ✅ | ✅ | ✅ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/dl.gif" width="20" hegiht="20"/>大连/ Dalian |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/wh.gif" width="20" hegiht="20"/>武汉/ Wuhan | ✅ | ✅ | ✅ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/cq.gif" width="20" hegiht="20"/>重庆/ Chongqing | ✅ | ✅ | ✅ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/sz.gif" width="20" hegiht="20"/>深圳/ Shenzhen | ✅ | ✅ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/nj.gif" width="20" hegiht="20"/>南京/ Nanjing | ⭕ | ⭕ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/sy.gif" width="20" hegiht="20"/>沈阳/ Shenyang |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/cd.gif" width="20" hegiht="20"/>成都/ Chengdu | ✅ | ✅ | | | ✅ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/xa.gif" width="20" hegiht="20"/>西安/ Xi'an | ✅ | ✅ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/suz.gif" width="20" hegiht="20"/>苏州/ Suzhou |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/km.gif" width="20" hegiht="20"/>昆明/ Kunming | | | ⭕ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/hz.gif" width="20" hegiht="20"/>杭州/ Hangzhou | | | | ✅ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/hrb.gif" width="20" hegiht="20"/>哈尔滨/ Harbin | ✅ | ✅ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/zz.gif" width="20" hegiht="20"/>郑州/ Zhengzhou | ⭕ | ⭕ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/cs.gif" width="20" hegiht="20"/>长沙/ Changsha[^ccs] | ✅ | ✅ | ✅ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/nb.gif" width="20" hegiht="20"/>宁波/ Ningbo | | | ✅ | ✅ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/wx.gif" width="20" hegiht="20"/>无锡/ Wuxi |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/qd.gif" width="20" hegiht="20"/>青岛/ Qingdao | ✅ | ✅ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/nc.gif" width="20" hegiht="20"/>南昌/ Nanchang | | ✅ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/fz.gif" width="20" hegiht="20"/>福州/ Fuzhou | ✅ | ✅ | ✅ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/dg.gif" width="20" hegiht="20"/>东莞/ Dongguan | ✅ | ✅ | ✅ | ✅ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/nn.gif" width="20" hegiht="20"/>南宁/ Nanning | ✅ | ✅ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/hf.gif" width="20" hegiht="20"/>合肥/ Hefei | ✅ | ✅ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/sjz.gif" width="20" hegiht="20"/>石家庄/ Shijiazhuang | ✅ | ✅ | ✅ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/gy.gif" width="20" hegiht="20"/>贵阳/ Guiyang | ✅ | ✅ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/xm.gif" width="20" hegiht="20"/>厦门/ Xiamen | ✅ | ✅ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/wlmq.gif" width="20" hegiht="20"/>乌鲁木齐/ Urumqi | ✅ | ✅ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/wz.gif" width="20" hegiht="20"/>温州/ Wenzhou | ✅ | ✅ | ✅ | ✅ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/jn.gif" width="20" hegiht="20"/>济南/ Jinan | ✅ | ✅ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/lz.gif" width="20" hegiht="20"/>兰州/ Lanzhou | ✅ | ✅ | ✅ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/cz.gif" width="20" hegiht="20"/>常州/ Changzhou | ✅ | ✅ | ✅ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/xz.gif" width="20" hegiht="20"/>徐州/ Xuzhou |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/hhht.gif" width="20" hegiht="20"/>呼和浩特/ Hohhot | ✅💥 | ✅💥 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/hk.gif" width="20" hegiht="20"/>香港/ Hong Kong | ⭕ | ⭕ | | | ✅ |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/mo.gif" width="20" hegiht="20"/>澳门/ Macao |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/tp.gif" width="20" hegiht="20"/>台北/ Taipei[^ctp] |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/kh.gif" width="20" hegiht="20"/>高雄/ Kaohsiung |
| | <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/Alipay.png" width="30" hegiht="30" alt="Alipay"/> | <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/WeChat Pay.png" width="25" hegiht="25" alt="WeChat Pay"/> | <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/Unionpay QR.png" width="40" hegiht="40" alt="Unionpay QR Code"/> | <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/Unionpay NFC.png" width="40" hegiht="40" alt="Unionpay Quickpass"/> | 💳 |

[^csh]: 上海：包括磁浮线/ Maglev is included in Shanghai
[^ccs]: 长沙：包括磁浮快线/ Maglev is included in Changsha
[^cgz]: 广州：包括APM线和广佛线/ APM Line and Guang-Fo Metro are included in Guangzhou
[^ctp]: 台北：包括桃园机场捷运/ Taoyuan Metro is included in Taipei

### 网上购票（线下取票）/ Buying Tickets Online

请参见[运营方式-服务-App](https://ivysauro.github.io/CNRT/data/General%20Operations#app)/ Please see [General Operation_Service_App](https://ivysauro.github.io/CNRT/data/General%20Operations#app)

## 充值/ Charging

包括自助充值和服务中心充值/ Be applicable to charging Transit Card on TVM and Service Center

*待完善*

## 开放性评分/ Open Score

本地虚拟交通卡超过4个厂商支持才能得满分，否则得一半分/ Only above 4 brand support Vitual NFC Local Card can Score full marks

### 图例/ Legend

| 标识/ Logo | 中文/ Chinese | 英文/ English |
| :-: | :- | :- |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/Alipay.png" width="30" hegiht="30" alt="Alipay"/> | 支付宝 | Alipay |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/WeChat Pay.png" width="25" hegiht="25" alt="WeChat Pay"/> | 微信支付 | WeChat Pay |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/China Unionpay.png" width="30" hegiht="30" alt="Unionpay"/> | 银联 | Unionpay |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/T-Union.png" width="40" hegiht="40" alt="T-Union"/> | 交通联合 | T-Union |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/NFC.png" width="25" hegiht="25" alt="NFC Local Card"/> | 本地虚拟交通卡 | Virtual NFC Local Card |

| 图标/ Icon | 中文/ Chinese | 英文/ English | 计分/ Mark |
| :-: | :- | :- | :-: |
| ✅ | 支持 | Support | 20 |
| ⭕ | 部分支持 | Partly Support | 10 |
| ❌ | 不支持 | Not Support | 0 |

### 主表/ Main Content

| 城市/ City | <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/Alipay.png" width="30" hegiht="30" alt="Alipay"/> | <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/WeChat Pay.png" width="25" hegiht="25" alt="WeChat Pay"/> | <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/China Unionpay.png" width="30" hegiht="30" alt="Unionpay"/> | <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/T-Union.png" width="40" hegiht="40" alt="T-Union"/> | <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/NFC.png" width="25" hegiht="25" alt="NFC Local Card"/> | 得分/ Score |
| --------- | :------------: | :--------------: | :-----------: | :------------: | :-----------: | :--------: |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/bj.gif" width="20" hegiht="20"/>北京/ Beijing | ⭕ | ⭕ | ✅ | ⭕ | ✅ | 70 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/tj.gif" width="20" hegiht="20"/>天津/ Tianjin | ⭕ | ⭕ | ✅ | ✅ | ✅ | 80 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/sh.gif" width="20" hegiht="20"/>上海/ Shanghai | ⭕ | ⭕ | ⭕ | ✅ | ✅ | 70 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/gz.gif" width="20" hegiht="20"/><img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/fs.gif" width="20" hegiht="20"/>广州&佛山/ Guangzhou & Foshan | ✅ | ✅ | ⭕ | ✅ | ✅ | 90 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/cc.gif" width="20" hegiht="20"/>长春/ Changchun | ⭕ | ⭕ | ✅ | ✅ | ✅ | 80 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/dl.gif" width="20" hegiht="20"/>大连/ Dalian | ❌ | ❌ | ✅ | ✅ | ✅ | 60 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/wh.gif" width="20" hegiht="20"/>武汉/ Wuhan | ⭕ | ⭕ | ⭕ | ❌ | ✅ | 50 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/cq.gif" width="20" hegiht="20"/>重庆/ Chongqing | ✅ | ✅ | ✅ | ❌ | ✅ | 80 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/sz.gif" width="20" hegiht="20"/>深圳/ Shenzhen | ⭕ | ✅ | ✅ | ✅ | ✅ | 90 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/nj.gif" width="20" hegiht="20"/>南京/ Nanjing | ✅ | ⭕ | ✅ | ✅ | ✅ | 90 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/sy.gif" width="20" hegiht="20"/>沈阳/ Shenyang | ✅ | ✅ | ✅ | ✅ | ✅ | **100** |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/cd.gif" width="20" hegiht="20"/>成都/ Chengdu | ✅ | ⭕ | ✅ | ❌ | ⭕ | 60 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/xa.gif" width="20" hegiht="20"/>西安/ Xi'an | ✅ | ✅ | ✅ | ✅ | ✅ | **100** |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/suz.gif" width="20" hegiht="20"/>苏州/ Suzhou | ❌ | ❌ | ❌ | ✅ | ✅ | 40 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/km.gif" width="20" hegiht="20"/>昆明/ Kunming | ✅ | ✅ | ✅ | ✅ | ❌ | 80 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/hz.gif" width="20" hegiht="20"/>杭州/ Hangzhou | ✅ | ❌ | ✅ | ✅ | ⭕ | 70 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/hrb.gif" width="20" hegiht="20"/>哈尔滨/ Harbin | ✅ | ✅ | ✅ | ⭕ | ✅ | 90 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/zz.gif" width="20" hegiht="20"/>郑州/ Zhengzhou | ✅ | ✅ | ✅ | ✅ | ✅ | **100** |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/cs.gif" width="20" hegiht="20"/>长沙/ Changsha | ⭕ | ⭕ | ⭕ | ✅ | ✅ | 70 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/nb.gif" width="20" hegiht="20"/>宁波/ Ningbo | ✅ | ✅ | ✅ | ✅ | ✅ | **100** |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/wx.gif" width="20" hegiht="20"/>无锡/ Wuxi | ❌ | ❌ | ❌ | ✅ | ✅ | 40 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/qd.gif" width="20" hegiht="20"/>青岛/ Qingdao | ⭕ | ⭕ | ❌ | ✅ | ✅ | 60 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/nc.gif" width="20" hegiht="20"/>南昌/ Nanchang | ✅ | ⭕ | ✅ | ✅ | ⭕ | 80 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/fz.gif" width="20" hegiht="20"/>福州/ Fuzhou | ⭕ | ⭕ | ⭕ | ✅ | ❌ | 50 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/dg.gif" width="20" hegiht="20"/>东莞/ Dongguan | ⭕ | ⭕ | ✅ | ❌ | ❌ | 40 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/nn.gif" width="20" hegiht="20"/>南宁/ Nanning | ✅ | ⭕ | ⭕ | ✅ | ✅ | 80 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/hf.gif" width="20" hegiht="20"/>合肥/ Hefei | ⭕ | ⭕ | ✅ | ✅ | ✅ | 80 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/sjz.gif" width="20" hegiht="20"/>石家庄/ Shijiazhuang | ⭕ | ⭕ | ⭕ | ✅ | ✅ | 70 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/gy.gif" width="20" hegiht="20"/>贵阳/ Guiyang | ⭕ | ⭕ | ❌ | ✅ | ⭕ | 50 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/xm.gif" width="20" hegiht="20"/>厦门/ Xiamen | ✅ | ⭕ | ✅ | ✅ | ✅ | 90 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/wlmq.gif" width="20" hegiht="20"/>乌鲁木齐/ Urumqi | ⭕ | ⭕ | ❌ | ❌ | ❌ | 20 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/wz.gif" width="20" hegiht="20"/>温州/ Wenzhou | ⭕ | ⭕ | ✅ | ❌ | ❌ | 40 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/jn.gif" width="20" hegiht="20"/>济南/ Jinan | ⭕ | ⭕ | ✅ | ✅ | ❌ | 60 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/lz.gif" width="20" hegiht="20"/>兰州/ Lanzhou | ✅ | ✅ | ⭕ | ✅ | ⭕ | 80 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/cz.gif" width="20" hegiht="20"/>常州/ Changzhou | ⭕ | ⭕ | ✅ | ✅ | ✅ | 80 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/xz.gif" width="20" hegiht="20"/>徐州/ Xuzhou | ❌ | ❌ | ✅ | ✅ | ⭕ | 50 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/hhht.gif" width="20" hegiht="20"/>呼和浩特/ Hohhot | ⭕ | ⭕ | ✅ | ❌ | ❌ | 40 |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/hk.gif" width="20" hegiht="20"/>香港/ Hong Kong | ⭕ | ⭕ | ✅ | | ⭕ | - |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/mo.gif" width="20" hegiht="20"/>澳门/ Macao | | | | | | - |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/tp.gif" width="20" hegiht="20"/><img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/ty.gif" width="20" hegiht="20"/>台北&桃园/ Taipei & Taoyuan | | | | | ⭕ | - |
| <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/city/kh.gif" width="20" hegiht="20"/>高雄/ Kaohsiung | | | ✅ | | ⭕ | - |
| | <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/Alipay.png" width="30" hegiht="30" alt="Alipay"/> | <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/WeChat Pay.png" width="25" hegiht="25" alt="WeChat Pay"/> | <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/China Unionpay.png" width="30" hegiht="30" alt="Unionpay"/> | <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/T-Union.png" width="40" hegiht="40" alt="T-Union"/> | <img src="https://raw.githubusercontent.com/Ivysauro/CNRT/master/images/NFC.png" width="25" hegiht="25" alt="NFC Local Card"/> | |

## 感谢/ Thanks

部分内容参考自[地铁族](http://www.ditiezu.com/)用户@[清风雨鸽](http://www.ditiezu.com/space-uid-215526.html)的[帖子](http://www.ditiezu.com/thread-607166-1-1.html)

---
