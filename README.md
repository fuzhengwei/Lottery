# :gift: Lottery 抽奖系统 - 基于领域驱动设计的四层架构实践

<div align="center">
    <a href="https://bugstack.cn" style="text-decoration:none"><img src="https://codechina.csdn.net/KnowledgePlanet/Lottery/-/raw/master/doc/_media/lottery.png" width="128px"></a>
</div>

<div align="center">
<a href="#">互联网</a> •    
<a href="#">C端项目</a> •    
<a href="#">DDD架构</a> •    
<a href="#">分布式</a> •    
<a href="#">规则引擎</a>
</div>

>` Lottery 抽奖系统` 项目是一款互联网面向C端人群营销活动类的抽奖系统，可以提供抽奖活动玩法策略的创建、参与、记账、发奖等逻辑功能。在使用的过程中运营人员通过创建概率类奖品的抽奖玩法，对用户进行拉新、促活、留存，通常这样的系统会用在电商、外卖、出行、公众号运营等各类场景中。By 小傅哥，[《重学Java设计模式》](https://item.jd.com/13218336.html)图书作者，沉淀、分享、成长，让自和他人都能有所收获！

⛳ **目录**

- [学习说明](https://codechina.csdn.net/KnowledgePlanet/Lottery#-%E5%AD%A6%E4%B9%A0%E8%AF%B4%E6%98%8E)
- [系统架构](https://codechina.csdn.net/KnowledgePlanet/Lottery#-%E7%B3%BB%E7%BB%9F%E6%9E%B6%E6%9E%84)
- [开发日志](https://codechina.csdn.net/KnowledgePlanet/Lottery#-%E5%BC%80%E5%8F%91%E6%97%A5%E8%AE%B0)
- [开发规范(分支、提交)](https://codechina.csdn.net/KnowledgePlanet/Lottery#-%E5%BC%80%E5%8F%91%E8%A7%84%E8%8C%83)
- [问题交流](https://codechina.csdn.net/KnowledgePlanet/Lottery#-%E9%97%AE%E9%A2%98%E4%BA%A4%E6%B5%81)
- [感谢支持](https://codechina.csdn.net/KnowledgePlanet/Lottery#-%E6%84%9F%E8%B0%A2%E6%94%AF%E6%8C%81)

## 📝 学习说明

在此项目中你会学习到互联网公司关于C端项目开发时候用到的一些，技术、架构、规范等内容。由于项目为实战类编程项目，在学习的过程中需要上手操作，小傅哥会把系统的搭建拉不同的分支列为每一个章节进行设计和实现并记录到开发日记中，读者在学习的过程中可以结合这部分内容边看文章边写代码实践。

- 技术：SpringBoot、Mybatis、Dubbo、MQ、Redis、Mysql、ELK、分库分表、Otter
- 架构：DDD 领域驱动设计、充血模型、设计模式
- 规范：分支提交规范、代码编写规范

## 🎨 系统架构

- 待编写，当设计和输出完第一章节后，陆续补全系统架构

## 📘 开发日志

- [x] [`第 01 节：开篇介绍 - 怎么上手、学到哪些`](https://codechina.csdn.net/KnowledgePlanet/Lottery/-/blob/master/doc/notes/%E7%AC%AC%2001%20%E8%8A%82%EF%BC%9A%E5%BC%80%E7%AF%87%E4%BB%8B%E7%BB%8D%20-%20%E6%80%8E%E4%B9%88%E4%B8%8A%E6%89%8B%E3%80%81%E5%AD%A6%E5%88%B0%E5%93%AA%E4%BA%9B.md)
- [x] [`第 02 节：搭建(DDD + RPC)分布式架构`](https://codechina.csdn.net/KnowledgePlanet/Lottery/-/blob/master/doc/notes/%E7%AC%AC%2002%20%E8%8A%82%EF%BC%9A%E6%90%AD%E5%BB%BA(DDD%20+%20RPC)%E5%88%86%E5%B8%83%E5%BC%8F%E6%9E%B6%E6%9E%84.md)
- [x] [`第 03 节：跑通广播模式RPC过程调用`](https://codechina.csdn.net/KnowledgePlanet/Lottery/-/blob/master/doc/notes/%E7%AC%AC%2003%20%E8%8A%82%EF%BC%9A%E8%B7%91%E9%80%9A%E5%B9%BF%E6%92%AD%E6%A8%A1%E5%BC%8FRPC%E8%BF%87%E7%A8%8B%E8%B0%83%E7%94%A8.md)
- [x] [`第 04 节：抽奖活动策略玩法库表设计和创建`](https://codechina.csdn.net/KnowledgePlanet/Lottery/-/blob/master/doc/notes/%E7%AC%AC%2004%20%E8%8A%82%EF%BC%9A%E6%8A%BD%E5%A5%96%E6%B4%BB%E5%8A%A8%E7%AD%96%E7%95%A5%E7%8E%A9%E6%B3%95%E5%BA%93%E8%A1%A8%E8%AE%BE%E8%AE%A1%E5%92%8C%E5%88%9B%E5%BB%BA.md)
- [ ] [`第 05 节：抽奖策略领域模块设计和开发`](#)
- [ ] [`第 06 节：待归档`](#)

## 📐 开发规范

**分支命名**：日期_姓名首字母缩写_功能单词，如：`210804_xfg_buildFramework`

**提交规范**：`作者，type: desc` 如：`小傅哥，fix：修复查询用户信息逻辑问题` *参考Commit message 规范*

```java
# 主要type
feat:     增加新功能
fix:      修复bug

# 特殊type
docs:     只改动了文档相关的内容
style:    不影响代码含义的改动，例如去掉空格、改变缩进、增删分号
build:    构造工具的或者外部依赖的改动，例如webpack，npm
refactor: 代码重构时使用
revert:   执行git revert打印的message

# 暂不使用type
test:     添加测试或者修改现有测试
perf:     提高性能的改动
ci:       与CI（持续集成服务）有关的改动
chore:    不修改src或者test的其余修改，例如构建过程或辅助工具的变动
```

## 🐾 问题交流

- **加群交流**

    本群的宗旨是给大家提供一个良好的技术学习交流平台，所以杜绝一切广告！由于微信群人满 100 之后无法加入，请扫描下方二维码先添加作者 “小傅哥” 微信(fustack)，备注：`Spring学习加群`。
    
    <img src="https://codechina.csdn.net/KnowledgePlanet/Lottery/-/raw/master/doc/_media/fustack.png" width="180" height="180"/>

- **公众号(bugstack虫洞栈)**

    沉淀、分享、成长，专注于原创专题案例，以最易学习编程的方式分享知识，让自己和他人都能有所收获。目前已完成的专题有；Netty4.x实战专题案例、用Java实现JVM、基于JavaAgent的全链路监控、手写RPC框架、DDD专题案例、源码分析等。
    
    <img src="https://codechina.csdn.net/KnowledgePlanet/Lottery/-/raw/master/doc/_media/bugstack.png" width="180" height="180"/>
    
## 🎉 感谢支持

![](https://codechina.csdn.net/KnowledgePlanet/Lottery/-/raw/master/doc/_media/background.png)

参与到项目开发学习过程中的小伙伴，可以通过PR提交个人对项目中学习过程中一些关于，代码优化、逻辑完善、问题修复等各项内容。当你的代码完整的提交以后，我会进行 `review` 通过以后进行合并以及记录你的提交信息。

<a href="#小傅哥">
    <img src="https://codechina.csdn.net/KnowledgePlanet/Lottery/-/raw/master/doc/_media/xiaofuge.jpeg" style="border-radius:5px" width="50px">
</a>
<a href="#倩倩">
    <img src="https://codechina.csdn.net/KnowledgePlanet/Lottery/-/raw/master/doc/_media/h_1.jpeg" style="border-radius:5px" width="50px">
</a>
<a href="#钢球">
    <img src="https://codechina.csdn.net/KnowledgePlanet/Lottery/-/raw/master/doc/_media/h_2.jpeg" style="border-radius:5px" width="50px">
</a>
<a href="#豆豆">
    <img src="https://codechina.csdn.net/KnowledgePlanet/Lottery/-/raw/master/doc/_media/h_3.jpeg" style="border-radius:5px" width="50px">
</a>

