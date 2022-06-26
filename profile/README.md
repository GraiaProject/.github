# Welcome to Graia Project!

Graia Project 是一系列的项目的集合, 并最终致力于建立开放包容, 具有丰富创造力的活跃 Bot 社区.

Graia Project 目前的主要工作是为 Bot Development 提供一系列高效, 现代化, 充分可扩展的工具链,
以及提供优秀的基础设施实现.

官方文档: https://graia.readthedocs.org/
社区文档: https://graiax.cn/

目前我们以不同的形式开源了许多的项目, 接下来将会一一列举出来.

部分项目存于由社区成员建立, 有官方人员提供支持的 [GraiaCommunity](https://github.com/GraiaCommunity) 处,
其中由官方人员维护的项目也会出现.

部分存于官方人员的个人 GitHub 账号下的项目, 若有一定关联亦会出现.

* Framework
  * [Ariadne](https://github.com/GraiaProject/Ariadne) - [Docs](https://graia.readthedocs.io/ariadne)  
    一个优雅且完备的 Python QQ 自动化框架, 基于 Mirai API HTTP v2.
* Framework Tools
  * [Broadcast Control](https://github.com/GraiaProject/BroadcastControl) - [Docs](https://graia.readthedocs.io/broadcast/)  
    极具扩展性的, 并不止于事件系统的事件系统实现.
  * [Saya](https://github.com/GraiaProject/Saya) - [Docs](https://graia.readthedocs.io/saya/)  
    社区中通用的插件/模块管理器.
  * [Scheduler](https://github.com/GraiaProject/Scheduler)  
    一个简单的定时任务实现, 与 Broadcast Control 深度结合.
* Infrastructure
  * [Amnesia](https://github.com/GraiaProject/Amnesia)  
    一系列共用组件的集合.
  * [creart](https://github.com/GraiaProject/creart) & [creart-graia](https://github.com/GraiaProject/creart-graia) - [Docs](https://graia.readthedocs.io/other/creart/intro/)  
    通用, 易于扩展, 实现简洁的类实例化器, 致力于简化 Graia Project 中各个部件在单一应用实例中的创建及引用.
  * [launart](https://github.com/GraiaProject/launart)  
    统一的应用实例启动时部件管理.
  * [statv](https://github.com/GraiaProject/statv) - [Docs](https://graia.readthedocs.io/other/statv/)  
    `Status API` 的实际实现.
  * [richuru](https://github.com/GreyElaina/richuru)  
    一个轻量级的依赖, 为 [`loguru`](https://github.com/Delgan/loguru) 提供 [`rich`](https://github.com/willmcgugan/rich) 强大的终端渲染支持.
  * [Mina](https://github.com/GreyElaina/Mina)  
    基于 `pdm-pep517` 实现的 Monorepo for Python 实现.
  * **WIP** [kayaku](https://github.com/GraiaCommunity/kayaku)  
    强大的配置管理解决方案.
  * **Planned** [Luma](https://github.com/GraiaProject/Luma)  
    基于 `kayaku` 与 `creart` 等组件, 实现无入口文件的应用实例启动, 为之诞生的 CLI 工具.  
    亦提供基于现有设施的 Saya 模块的管理, 目前 `pdm` 与 `poetry` 的支持已列入 Roadmap. 
