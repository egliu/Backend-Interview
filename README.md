This is Chinese version of [Back-End-Developer-Interview-Questions](https://github.com/arialdomartini/Back-End-Developer-Interview-Questions)


# 1 关于设计模式
- [x] 为什么全局或者静态对象是邪恶的？能够有代码的例子？
- [x] 介绍一下控制反转(IoC)，它是如何提高代码设计的？
- [x] 迪米特法则（Law of Demeter）表述每个单元最外部了解的越少越好，编写违反这个原则的代码，说明它是不好的设计模式，并且修复它。
- [x] 活动记录(Active-Record)是一种设计模式，它表述了代表数据库中表的对象应该拥有`Insert`,`Update`和`Delete`等相关操作。在你的观点和工作经验中，这中设计模式有什么限制和缺陷？
- [x] 数据映射(Data-Mapper)是另外一种设计模式，它鼓励使用`Mapper`层用来在内存对象和数据库之间移动数据，用来保证各自的独立。这个与活动记录`Active-Record`模式相反，你对这两种设计模式怎么看？在什么情况下使用其中一个，而不是另一个？
- [x] 为什么说引入`null`类型是一个`Billion dollar mistake`，你能说说有什么技术来避免它？比如在`GOF`书中提到的`Null Object Pattern`方法，`Option` 类型。
- [x] 许多观点是这样的：在面向对象编程(`OOP`)中，组合往往是比继承更好的选择，你观点是怎样的？
- [x] 什么叫反腐化(`Anti-corruption`)层？
- [x] 单例模式设计模式限制了每一个类只能创建唯一的对象，你能否写一个线程安全的单例模式？
- 改变实现方式而不影响客户端的能力叫做数据抽象`Data Abstraction`，那么编写一个违反这个属性的例子，并且修复它。
- 编写一个代码片段并且违法`DRY` (Don't Repeat Yourself)原则，并且修复它。
- [x] 如何处理依赖灾难（`Dependency Hell`)
- [x] `goto`语句是邪恶的吗？你或许听过一篇由`Edsger Dijkstra`写的著名论文 `Go To Statement Considered Harmful`，在这篇论文中他批评了`goto`语句，并且推崇结构化编程。 使用`goto`通常非常有争议，甚至`Dijkstra`这篇文章也被批评了，诸如`'GOTO Considered Harmful' Considered Harmful`，那么你的观点是怎样的？
- [x] 鲁棒性原则是软件开发中广泛的采用的原则，通常用 `对你的输出按照约定，对你的输入保持宽容`(`Be conservative in what you send, be liberal in what you accept`)，你能说说这个原则的合理性吗？
- 问题拆分（`Separation of Concerns`)是一种设计原则，它将编程问题划分到不同的领域，每一个领域关注自己的的问题。有许多不同的机制来完成这个目标，比如使用对象，函数，模块，或者MVC等等。 你能讨论一下这个话题吗？
  
# 2 代码设计
- [x] 在面向对象编程中，一个很重要的目标是高内聚（High Cohesion)和松耦合（Loose Coupling). 那么它意味着什么？为什么这个很重要？如何实现它呢？
- [x] 为什么在大部分语言中数组的下标从`0`开始？
- 测试和测试驱动开发(TDD)如何影响代码设计？
- 编写一个代码片段违反`DRY`原则，并且解释它为什么是坏的设计，然后修复它。
- [x] 内聚和耦合有什么区别？
- [x] 重构的作用是怎样的？
- [x] 代码中注释是有用吗？一些人说我们应该尽可能的避免注释，而且它们大部分是无用的，你同意吗？
- 设计和架构有什么区别？
- [x] 为什么测试驱动开发`TDD`中的测试时在开发之前？
- C++支持多继承，而JAVA允许一个类实现多个接口。在正交性上有什么影响？使用多继承和多接口有什么区别？使用委托和继承有什么区别？（问题来自`The Progmatic Programmer`一书中）
- 在存储过程中使用领域逻辑有什么好处和坏处？
- [x] 在你观点来看，使用面向对象编程为什么能够占据市场这么长时间？
- 你是如何知道一个代码是坏的设计？

# 3 语言
- 说一下你最喜欢语言的三个缺陷;
- [x] 为什么现在对函数式编程语言越来越受到欢迎？
- [x] 什么是闭包，闭包有什么作用？它和类有什么区别？
- 泛型是用来做什么的？
- [x] 什么是高阶函数？它是用来做什么的？用你最喜欢的语言写一个高阶函数;
- [x] 编写一个循环，然后将它转换成递归的形式，并且只能使用不可变结构（比如避免使用变量）
- 语言将函数当做一等公民意味什么？
- 展示一个例子来说明匿名函数是有用的；
- 有许多不同的类型系统：静态类型和动态类型，强类型和弱类型等等。你能分享和讨论一下在开发一个企业级软件的时候，如何去选择特定的类型系统？
- 命名空间（namespace)是做什么的？能够发明一个可替代性的东西？
- 讨论一下JAVA和C#之间的互通性？
- 为什么许多开发人员不喜欢JAVA？
- 好语言的好和坏语言的坏各自在什么地方？
- 编写两个函数，一个是引用透明（`Referentially Transparent`)，另一个是引用不透明（`Referentially Opaque`）;
- [x] 什么是栈和堆？什么叫栈溢出？
- 为什么在一个语言中，函数是一等公民是非常重要的？
- 在一些语言中，尤其是函数化倾向的语言中，有一种叫模式匹配（Pattern Matching)的技术，那么在模式匹配和`Switch`语言有什么区别？
- 为什么在有些语言设计中没有异常机制？那么它们有什么优势和弊端？
- 如果`Cat`是`Animal`，那么设计的时候是`TakeCare<Cat>`还是`TakeCare<Animal>`?
- 为什么在JAVA，或者C#中，构造函数不是接口的一部分？
- 最近几年，有很多关于`Node`的不实的宣传，那么你对这些原本运行在浏览器中的语言用作后端开发语言的看法是什么？
- 假设你有一台时光机，能够穿梭到Java语言创建的时间点，并且能够和JDK的架构者交流，那么你将会说服他什么？比如移除检查异常（checked  exception)机制?增加非符号的的基础类型？增加多继承？
  
# 4 Web开发
- 为什么`第一方`缓存和`第三方`缓存不同对待？
- 如何管理你的`Web`符合的API版本？
- 从后端的角度来看，采取单页面应用程序(`Single Page Application`)有什么弊端和缺陷？
- 为什么我们通常在无状态服务做出巨大的付出，那么在无状态代码中有哪些好处以及有状态有什么坏处？
- `REST`和`SOAP`两种方式，什么时候选择其中一个，而不用另外一个？
- 在Web开发中，MVC和MVVM两种模式非常常见，在前端和后端中都是常见的，那么它们各自是什么？为什么它们是值得使用的？

# 5 数据库
- 如果你将你的应用程序迁移数据库，比如从MySQL迁移到PostgreSQL，你会怎么做？如果你来管理这个项目，那些问题需要考虑？
- 为什么数据库需要特别对待`null`，比如在SQL语言中: `SELECT * FROM table WHERE field=null`并不能匹配为空的记录？
- ACID通常是`Atomicity`, `Consistency`，`Isolation`和`Durabiltiy`。这四个属性通常有数据库引擎的事务来保证，你能谈谈这个话题吗？
- 你是如何做到数据库模式的迁移，你是如何版本更改中，如何自动更改数据库模式修改的影响？
- 懒加载（lazy loading)是如何做到？它有什么作用？也有哪些缺陷？
- 什么是`N+1`问题？
- 如何在你的应用中查出代价最大的查询？
- 在你的观点中，数据库范式化是否永远必须的？什么时候数据库可以不需要范式化？
- 什么叫持续集成？也叫做`Blue-Green Deloyment`

# 6 NoSQL
- 什么叫最终一致性（Eventual  Consisitency)?
- `Brewer`理论，也叫做`CAP`理论，说明在网络分区（network Partition)中，一个系统设计者需要在以一致性`Consistency`和可用性`Availiablity`中做出选择，你能举出`CP`， `AP`和`CA`系统的例子吗？
- 你能解释一下最近对`NoSQL`热度越来越高的原因吗？
- 为什么`NoSQL`解决了可扩展性的挑战？
- 在那种情况下你会选择文档型数据库比如`MongoDB`而不是关系型数据库比如`MySQL`?
  
# 7 代码版本管理
- 为什么在`Mercuial`或者`git`中，创建分支比`SVN`分支容易；
- 分布式版本控制系统和集中式版本管理系统有什么各自的缺点和优点？
- [x] 你能描述`github flow`和`gitflow`各自的工作流？
- [x] 什么是`rebase`?
- 在`Mercurial`或者`git`中合并比`SVN`中容易；

# 8 并发
- [x] 为什么我们需要并发？
- 为什么测试多线程或者并发比较困难？
- [x] 什么是竞争条件？举一个例子来描述？
- [x] 什么是死锁？编写一些代码是由死锁导致的；
- [x] 什么是进程饥饿？如果需要，重新回顾一下定义
- [x] 什么是`Wait Free`算法？

# 9 分布式系统
- 如何测试分布式系统？
- 在哪种方式下在两个系统之间通信使用异步方式？
- RPC调用有什么缺陷？
- 如果你在构建一个分布式系统以便可扩展性和鲁棒性，那么在网络环境安全和地理分布上的考虑和其他系统有什么区别？
- 如何管理一个web应用程序的错误容忍性？
- 在分布式系统中如何处理故障？
- 如何在分布式网络中保证一致性？
- 分布式系统中有哪些谬论？
- 什么时候用`Request/Reply`模式或者`Publish/Subscribe`模式？
- 假设你的系统不支持事务，那么你该如何从头实现一个？
  
# 10 软件生命周期和团队管理
- 什么是敏捷？
- 你是如何处理历史遗留代码？
- 假设我是项目经理，并且没有编程经验，那么你能跟我解释历史代码并且告诉我为什么关注代码质量？
- 如果我是公司的CEO，那么像我解释`Kanban`，并且说服我在上面投资；
- 敏捷和瀑布流最大的区别是什么？
- 作为一个团队管理者，你是如何处理有太多的会需要参加的问题？
- 你是如何处理延期的项目？
- "个体与交互重于过程和工具"和"客户协作重于合同谈判"占了敏捷宣言（Agile Manifesto）的一半，谈论一下这两个观念；
- 如果你是公司的CTO，那么你会采取什么措施？
- 项目经理有用吗？
- 如果要你组织一个弹性工作制的开发团队（即没有强制工作时间的要求），并且假期制度是"按需休假"，你会如何做？
- 你会如何管理一个人员流动非常高的团队？如何在不加薪的条件下说服团队成员不要离开？
- 除了代码之外，你认为你要找的同事最重要的三个特质是什么？
- 对于非技术背景的人，你认为三个最重要的事情是什么？
- 如果公司给你一个月时间和一些预算来提高你同事的日常生活，你会怎么做？

# 11 逻辑和算法
- [x] 仅仅使用`LIFO`栈来实现`FIFO`的队列，然后使用`FIFO`的队列来实现`FIFO`的栈；
- 使用代码片段来实现栈溢出；
- 使用尾递归版本的`Fraction`方法；
- 使用你最熟悉的语言，来实现一个REPL，它将输出任何输出；执行RPN表达式；
- 如何设计一个磁盘整理碎片工具？
- 编写一个随机生成迷宫的程序；
- 编写一个实例代码能够导致内存泄漏；
- 生成一系列不同的随机数；
- 编写简单的垃圾回收系统；
- 编写基础的消息发送broker;
- 编写基础的web服务器，并且绘制出将来的要完成的功能；
- 如何对10GB的文件排序，那么10TB文件如何呢？
- 如何自动检测冗余的文件？

# 12 软件架构
- 什么时候缓存是无用的，甚至是危险的？
- 为什么事件驱动架构提高可靠性？
- 如何让代码可读？
- 紧急设计(Emergent Design)和演化架构(Evolutionary Architecture)之间的区别是什么？
- 横向扩展和纵向扩展有什么区别？什么时候使用其中一个，而不是另外一个？
- 如何处理"故障切换(failover)"和"用户会话(user session)"？
- 什么是CQRS（Command Query Responsibility Segregation)? 它和最初的有什么区别？
- ...

# 13 SOA 和 Microservices
- 为什么在SOA中，长时间事务是不推荐的，而是使用`Sagas`?
- Soa和微服务（microservice)有什么区别？
- web服务如何进行版本管理，版本兼容和打破改变？
- 事务和`saga`在SOA中有什么区别？
- 什么使用微服务显得太微（`too micro`)了?
- 微服务架构的优缺点是什么？

# 14 安全
- 什么是代码安全？在你的观点中，这个是开发者的责任，还是公司需要专门的角色？
- 为什么密码学是一些你自己不需要重新发明和设计的事情？
- 什么是双因素认证(Two Factor Authentication)？在一个已有的Web应用中，你如何实现这种机制？
- 如果不是仔细处理，存在日志中包含敏感信息的风险，比如密码？如何处理这些事情呢？
- 编写代码能够被SQL注入影响，并修改它；
- 能够通过代码静态检查分析来检测SQL注入，能够给出大致的思路；
- 什么是` Cross-Site Scripting`?
- 什么是`Cross-Site Forgery Attack`?
- HTTPS是如何工作的？
- 什么是中间人攻击（`Man-in-the-middle Attack`)? `HTTPS`如何保护的？
- 怎样防止用户的会话（session）被偷？

# 15 通用问题
- 函数式语言是做什么的？什么时候我们需要使用函数语言？
- Microsoft，Google，Opera和Mozilla公司从他们的浏览器中如何获利的？
- 为什么打开TCP套接字有很大的开销？
- 封装对于那些有重要的作用？
- 什么是实时系统？它和普通的系统有什么区别？
- 实时语言(real-time language)和堆内存分配(heap memory allocation)之间的关系是什么？
- 不可变性是怎么帮助我们提高编写更安全的代码？
- 可变性变量和不可变量有什么优势和弊端？
- 什么是O/R阻抗失衡(Object-Relational impedence mismatch)？
- 缓存大小在设计的时候需要考虑哪些原则？
- 客户端渲染和服务端渲染有什么各自弊端，如何取舍？
- 如何在不可靠的协议上开发出可靠通讯协议？
- 想象一下如果在你最喜欢的语言移除空引用的问题，你该如何做？会导致什么样的后果？

# 16 开放问题
- 为什么人们讨厌改变？
- 向你的奶奶解释线程
- 作为一个软件工程师，你想要既要有创新力，又要产出具有可预测性。采用什么策略才能使这两个目标可以共存呢？
- 什么让好代码变得更好？
- 解析什么是流，并且实现它；
- 你在这一周学到了什么？
- 所有的设计中都会有美学元素(aesthetic element)的存在。问题是，你认为美学元素是你的朋友还是敌人？
- 列出你最近读的五本书
- 如何让大公司从瀑布式开发模式到持续交付的模式改变？
- 什么时候你觉得重复发明轮子是有意义的？
- 我们来谈谈"重复造轮子","非我发明症", "吃自己做出来的狗粮"的这些做法吧。
- 在你当前的工作流中，什么事情是你计划下一步需要自动化的？
- 为什么编写软件是复杂的？什么让维护软件也变得非常困难？
- 你更喜欢在全新项目（Green Field Project）上工作还是在已有项目(Brown Field Project)基础上工作？为什么？
- 当你在浏览器中输入`google.com`并且按回车后，发生了什么？
- 当你没有自己的代码在运行，你的操作系统会做一些什么，尽管它看上去的空闲的？
- 如何向一个5岁的孩子解释什么是Unicode/数据库事务？
- 如何维护单体架构(monolithic architecture)？
- 成为一个专业的开发者意味着什么？
- 在你的观点中，软件开发是否是一门艺术，一个手工艺亦或者是工程？
- "喜欢这个的人也喜欢..."，如何在一个电子商务商店里实现这种功能？
- 为什么大公司在创新上不如初创公司？
- 最近有哪些东西你是值得骄傲的？

# 17 Bill Gates 问题
- 如果你把一面镜子放在扫描仪上，会发生什么？
- 假设有一个和你完全一样的克隆人，而他是你的上司，你愿意和他工作吗？
- 现在请你面试一下我。
- 为什么Quora上的回答会比Yahoo Answer上的回答好？
- 对手是现代语言，你的任务是要为Cobol辩护，你会如何进行？
- 10年后的你是什么样子？
- 假设你是我老板，我被解雇了，你会如何通知我？
- 我想要重构一个系统，而你想要从头重写。我们来争论一下该怎么弄吧。然后我们反转角色，再争论一下。
- 老板要你对公司撒谎，你的反应是什么？
- 如果你可以穿越到以前，你会给年轻时候的你什么建议？