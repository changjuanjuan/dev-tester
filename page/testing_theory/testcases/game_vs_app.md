# 游戏测试和传统软件测试的区别

*传统软件指代：app、web、pc、小程序等*

> 游戏测试工具清单：https://www.jianshu.com/p/af61098c8375

### 研发角色

| 项目     |          |              |                            |          |              |          |
| -------- | -------- | ------------ | -------------------------- | -------- | ------------ | -------- |
| 游戏     | 制作人   | 策划         | 程序                       | 测试     | 美术         | 项目经理 |
| 传统软件 | 研发总监 | 产品经理(PM) | FE、RD、Andorid、iOS、数据 | 测试(QA) | UI设计（UE） | PMO      |

### 开发周期

【游戏】：

> DEMO -> Alpha（40%-60%） -> Open Beta（80%） -> Rec（正式上线前） -> Gold release（正式运营）-> 【迭代周期】

【传统软件】：

> 项目立项 -> 初版开发 -> 初版测试 -> 初版灰度 -> 初版上线 -> 【迭代周期】

相对来说，

游戏第一版的开发周期会更加长、难度更大，据了解至少半年以上，大型主机游戏长则n年；

传统软件开发，以app开发为例，开发周期相对较短、难度较小，第一版开发最快几周就可以上线

### 迭代周期

游戏：迭代周期频繁，注重热修复

软件：以app为例，迭代周期比较固定，一般一个月发两版

我司的 **软件** 迭代周期（app）

> 需求预评审 -> 需求评审 -> 项目排期 -> 技术评审（针对大型需求）-> case评审-> RD开发 -> UE校对->RD自测->  showcase+提测 -> QA测试（包括功能、接口、性能等）-> 验收测试 -> 众测 -> 后端API上线 -> 分阶段灰度 -> 正式发版

各阶段参与角色：

需求预评审：「QA leader、RD leader、PM、PMO」

需求评审：「QA、RD、UE、PM、PMO」

项目排期：「QA、RD、UE、PM、PMO」

技术评审（针对大型需求）：「QA、RD、PM」

case评审：「QA、RD、PM」

RD开发：「RD」

UE校对：「RD、UE」

RD自测：「RD」

showcase：「PM、QA、RD」

QA测试：「QA、RD」

验收测试：「PM、UI」

众测：「QA、RD、PM、PMO」

后端API上线：「QA、RD」

分阶段发布：「线上用户」

正式发版：「渠道」

### 数据包

游戏中常见的封包：

（1）Google protobuf

（2）json

（3）xml

（4）自定义

app常见的封包

（1）json

（2）自定义

### 抓包工具

游戏测试