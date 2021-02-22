![LICENSE](https://img.shields.io/github/license/WeBankBlockchain/Truora-Service)
![image](./images/logo.png)
# 什么是Truora

**Truora** 取Trust（可信）、Oracle（预言机）的涵义命名，可读为[tru ɔ:rə]。是一整套联盟链可信预言机解决方案，Truora作为连接联盟链和互联网的桥梁，Truora致力于让互联网数据安全可信地上链。

**Truora** 是 FISCO-BCOS 区块链平台的预言机服务解决方案，是在广泛调研的基础上针对**联盟链**场景设计的可信预言机服务。 详细介绍请查看[Truora在线文档](https://truora.readthedocs.io/)
                                                                                 
                                                                                    
## 各子系统简介
**Truora** 服务主要由后端 Java 组件 Truora-Service 和前端 Vue 组件 Truora-Web 组成。

* **预言机后端服务 [Truora-Service](https://github.com/WeBankBlockchain/Truora-Service)** 
 主要分为链上部分和链下部分。链上部分主要是 oracle 相关合约，链下部分主要是 Java 服务，负责连接节点，监听合约的事件，采集结果并回写到 oracle 合约。
 Truora-Service 目前主要支持获取链下API,后续会陆续开源VRF随机数，去中心化预言机功能。
* **预言机前端服务 [Truora-Web](https://github.com/WeBankBlockchain/Truora-Web)**
 主要支持预言机配置信息、请求详情、请求历史的查询。方便应用查询自己预言机请求的结果，如果请求失败，可以看到请求失败的原因。

## License

开源协议为[Apache License 2.0](http://www.apache.org/licenses/). 详情参考[LICENSE](../LICENSE)。
    
## 贡献说明
请阅读我们的[贡献文档](https://truora.readthedocs.io/zh_CN/latest/docs/CONTRIBUTING.html)

## 愿景
   区块链愈发展，对链下数据的需求就会愈强烈，预言机的重要性也会愈发凸显。
   预言机作为区块链的重要一环，保证链下数据的安全可信上链是一个有趣也是富有挑战性的课题。
   独行快，众行远。Truora目前还在迭代开发中，希望社区更多参与进来共建联盟链可信预言机服务。

## 社区
  - 交流群：如在实操方面遇到阻碍或想和开发者们随时随地交流，那么加群、加群、加群，群里的“老司机”很乐意为你提供解答和支持。
  ![小助手](./images/assistant.png)
  - 公众号：及时掌握项目动态、了解版本更新信息、阅读来自社区的精彩文章，以及查阅近期活动安排。
  ![公众号](./images/account.png)