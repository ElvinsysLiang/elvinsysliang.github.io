---
layout: post
title:  "《Head First敏捷开发》读书笔记"
tags:   [读书笔记]
date:   2021-04-19 10:03:05
categories: [笔记]
---

# 第一章————什么是敏捷？原则与实践

1. 敏捷开发流行的原因  
- 容易满足最后期限的需求。
- 减少软件的bug。
- 代码容易维护——增加、扩展和修改。
- 提高用户满意度。
- 提高团队效率，减少加班。

2. 什么是敏捷  
- 帮助解决软件团队遇到的特定问题而提供的一组方法论。
- 这些方法论适用于所有软件工程领域，包括项目管理、软件设计和架构以及流程改进。
- 敏捷除了是一组方法论，也是一种思维模式，因此每个方法论都包含一组价值观。
- 常用的方法论有：Scrum、XP极限编程、Lean精益和看板。

---

# 第二章————敏捷价值观和原则：思维模式与方法

1. 《敏捷宣言》  
- 个体与交互    胜于    流程和工具
- 可用的软件    胜于    完备的文档
- 客户协作      胜于    合同谈判
- 响应变化      胜于    遵循计划

2. 《敏捷宣言》背后的12个原则  
- 最高目标是，通过尽早和持续地交付有价值的软件来满足客户。
- 欢迎对需求提出变更，善于利用需求变更来获得竞争优势。
- 要不断交付可用软件，周期从几周到几个月不等，越短越好。
- 项目过程中，业务人员与开发人员必须在一起工作。
- 要善于激励项目人员，给予他们所需的环境和支持，并信任他们能完成任务。
- 无论是开发团队还是团队间，最有效的沟通方法是面对面的交谈。
- 可用的软件是衡量进度的主要指标。
- 提倡持续的开发，赞助商、开发人员和用户应该能够保持恒久稳定的进展速度。
- 对技术的精益求精以及对设计的不断完善，能提升敏捷性。
- 要做到简洁，尽最大可能减少不必要的工作。
- 最佳的架构、需求和设计出自于自组织的团队。
- 团队要定期反省如何能够做到更有效，并相应地调整团队的行为。

---

# 第三章————用Scrum管理项目：Scrum规则

1. Scrum指南：https://www.scrum.org  

2. 3个主要角色（至少3人，最多9人）  
1）产品负责人（Product Owner），与团队一同维护产品待办列表（Product Backlog）。  
2）敏捷教练（Scrum Master），指导团队克服障碍。  
3）开发团队（Development Team）。  

3. 时间盒事件（Time Boxed）  
1）项目划分为sprint。  
一个sprint为2周到30天，sprint长度固定进行迭代。  
长度为30天时，sprint计划会议为8小时，长度为2周时，sprint计划会议为4小时。  
2）sprint计划会议（Planning）  
团队在一个sprint开始时召开sprint计划会议（Planning）。  
构建sprint待办列表（Sprint Backlog）。  
对于产品待办列表中的每一项，写出足够的信息，足以召开sprint计划会议即可。  
在会议中，对sprint待办列表完成适量的分解，足以让每个人开始工作即可。  
对sprint待办列表中的每一个项的“完成”进行定义，并在团队中达成共识。  
3）每日Scrum站会（Daily Scrum）  
每天召开每日Scrum站会（Daily Scrum），时间为15分钟。  
谈论内容：做了什么，接着做什么，遇到什么障碍。  
检查所开发的每一项，每一个任务。  
发现新的任务和变更时，在每日Scrum站会上提出，再指定之后的24小时计划。  
4）sprint评审会议（Sprint Review）  
sprint结束时召开sprint评审会议（Sprint Review）。  
产品负责人查看Sprint中“完成了”的待办项。  
团队向产品负责人和利益相关者演示可用软件。  
团队讨论哪些工作做得好，哪些可以改进，并回答客户和利益相关者的问题。  
产品负责人引导所有人查看产品待办列表，大家一起讨论应该把哪些项放到下一个sprint待办列表。  
讨论市场出现的变化，这将会影响接下来的最有价值的工作。  
5）回顾会议(Retrospective)  
召开回顾会议(Retrospective)。  
总结学到的经验教训，改进特定问题。  
30 days->Backlog:21 features->Planning->Daily Scrum->...->Daily Scrum->Sprint Review->Retrospective  
30 days->Backlog:17 features->Planning->Daily Scrum->...->Daily Scrum->Sprint Review->Retrospective  
30 days->Backlog:14 features->Planning->Daily Scrum->...->Daily Scrum->Sprint Review->Retrospective  
30 days->Backlog:12 features->Planning->Daily Scrum->...->Daily Scrum->Sprint Review->Retrospective  

4. 用于了解“Sprint构建的什么，如何构建”的三个工件  
1）产品待办列表（Product Backlog）  

例子：狂野奶牛5的产品待办列表  
第一项：设计和测试“羊圈秘密行动”关卡。  
估计工作量：27人日。  
价值：在CGW4最受欢迎的关卡的基础上构建，提高玩家满意度。  

第二项：更新牛奶枪功能，包含喷射动作。  
估计工作量：4人日。  
价值：改进游戏过程的体验。   

第三项：完成狂野奶牛僵尸生存关卡的设计，包括僵尸AI和大群僵尸的攻击。  
估计工作量：16人日。  
价值：僵尸题材能提高玩家满意度。  

第四项：增加战场的俯视图，让玩家能掌握炮塔、部队和狙击手的位置。  
估计工作量：19人日。  
价值：通过代码重用，增加游戏关卡。  
......

2）Sprint待办列表（Sprint Backlog）

例子：狂野奶牛5的Sprint待办列表    

Sprint目标：至少创建一个可以从头玩到尾的关卡。  

Sprint代办项：  
1.羊圈秘密行动关卡  
2.牛奶枪功能  
3.生存关卡  

Sprint计划：  
1.羊圈秘密行动关卡
1）编写两类新的奶牛敌人  
2）创建纹理图  
3）在关卡编辑器中为这个关卡设计3D空间  
4）构建秘密行动模式AI  

2.牛奶枪功能  
1）设计喷射算法  
2）实现牛奶枪类  
3）更新碰撞检测代码  
......

3）增量：增量是sprint结束时实际完成和交付的所有产品待办列表项的总和。

5. Scrum的5个价值观  
1）开放  
每个团队成员都愿意分享自己在做什么、遇到的问题和障碍，互相能相互讨教。  

2）尊重  
每个团队成员都能相互尊重，信任彼此能完成任务。  

3）勇气  
利用工具确定计划的可行性，遇到不可能完成的任务时，勇敢说出。  

4）专注  
每个团队成员都能专注于sprint目标，一次只完成一个任务，知道sprint结束。  

5）承诺  
每个团队成员都承诺会尽其所能交付最有价值的产品。  

6. Scrum团队在整个sprint中适应变更的手段（经验过程控制理论）  
1）三大支柱的一个循环，：透明、检查、适应。  
2）透明：团队共同决定一个sprint要包含的项，对每一项的完成标准的准确定义。
3）检查：每天站会检查每一项。  
4）适应：如果发现变更，则马上做出适应性调整，可以PO对sprint待办列表进行增删操作）  
5）第二天继续上面的循环，知道时间盒到期，sprint结束。  
6）也可通过会议评审修改sprint目标、待办项、任务以及工作方式，来检查适应其他Scrum事件。  
（包括sprint计划会议、sprint评审会议和sprint回顾会议）

7. 最后责任时刻   
1）在sprint开始时不会做出所有任务的计划。  
2）只需要做出绝对必要的计划，就可以启动一个sprint。
3）如果需要更多计划，即使在sprint的后期也可以再做那些计划。
4）在最后责任时刻才做出决定。

8. 敏捷宣言对于Scrum团队非常有用的3个原则  
1）最高目标是，通过尽早和持续地交付有价值的软件来满足客户。  
产品负责人要确保团队交付的价值。他有权拒绝验收Sprint待办列表中的“没有完成的项”。  
在sprint评审会议中，产品负责人发挥的作用就是将价值最大化。  

2）最佳的架构、需求和设计出自于自组织的团队。  
这说明整个Scrum团队一起合作来确定项目的计划，而不是由老板指派某人完成某个任务。  
无论是在sprint计划会议中，还是每日Scrum站会，团队成员都会不断调整他们的计划。  

3）欢迎对需求提出变更，善于利用需求变更来获得竞争优势。  
在sprint计划会议、每日Scrum站会中，都要持续进行检查和适应性调整。  

---

# 第四章————敏捷规划和估计：Scrum实践

1. 用户故事（User Stories）和故事点（Story Points）  

1）用户故事（User Stories）  
帮助团队了解用户需求。    
一般写在笔记卡上。  

例子：  

标题：跑动过程中换装备  
故事点：2点  
角色：作为**一个玩家**，  
实现效果：我希望**能够在跑动过程中更换装备**，  
特性价值：这样我就**不需要停下来查看装备库，以免被打死**。  

例子:  
跑动过程中更换装备  
2点     
作为一个玩家          
我希望能够在跑动过程中更换装备,  
这样我就不需要停下来查看装备库，  
以免被打死。  

2）故事点（Story Points）  
用来预测每个故事的规模，强调特性的相对规模。  
每个故事的工作量预测，不一定是具体花费时间。  
团队通过故事点，对故事的规模达成一致。  

2. 规划扑克（Planning Poker）  

1）准备  
每个成员一副扑克，Scrum教练主持会议，成员用扑克对用户故事规模估值。  
2）理解每个故事  
团队与产品负责人一起按优先顺序查看sprint待办列表中的故事。  
3）指定一个故事点值  
对于某一特性，每个人给出一个故事点值。  
4）解释最大值和最小值  
让给出最大值和最小值的成员做出解释。  
5）调整估计  
每个成员对同一故事进行再取值。  
6）汇聚估计  
经过2到3次的讨论迭代后，团队就一致确定一个故事点值。  

3. 任务版（Task Boards）  
帮助团队了解信息，分为：待办（To Do），进行中（In Progress），完成（Done）  

4. 燃尽图（Burndown Charts）  
帮助团队了解还剩下多少工作。  

5. 故事地图  
1）产品负责人和开发团队协作，为了确保下一个sprint待办列表中的项目，而进行产品待办列表细化会议（Product Backlog Refinement Meeting），花费的时间不会超过总时间的10%。  
2）利用故事地图，确定待办列表的优先顺序。  
3）主干（backbone）：产品最核心的特性。  
4）行走骨骼（walking skeleton）：从某一个主干中分解出来的用户故事。  
5）再从主干中分解出不同的用户故事，然后按照地图上的优先顺序加入特性。  

6. 用户画像（Persona）  
1）假想一个虚拟用户，包括个人信息，一张照片，用来帮助Scrum团队了解用户和利益相关者的需求。  
2）例子：  
一张照片（~~~）  
姓名：老黄  
年龄：28岁  
位置：纽约  
角色：高级玩家  
人物资料：尽可能参加游戏大会。拥有多个游戏平台机器，专门为玩游戏组装PC。  
目标：游戏剧情，多种玩法，战斗游戏，挑战性高，合作游戏。  
担心：游戏质量，bug，卡住，崩溃，剧情漏洞，服务器性能差。  

7. 回顾  
1）帮助团队改进他们的工作方式。  
2）做准备，让每个人在会议开始的时候都有机会抒发一下心情，之后会更乐意分享他们的观点。  
3）手机数据，查看看板，燃尽图，让成员对事件和决策进行投票，确认事件和决策的好坏。  
4）产生简介，收集数据后，用鱼骨图来找出组织问题的根本原因，考虑将来的改善方法。  
5）决定做什么，在接下来的sprint中要实现那些改进。  

---

# 第五章————XP极限编程（ExtremeProgramming）：拥抱变化

1. 概念  
XP是一种敏捷开发的方法论，专注于构建能良好沟通、有凝聚力的团队，并创建一种让人**放松而且精力充沛**的环境，旨在让团队构建简单而不是复杂的代码，从而变得**拥抱变化**，而不是惧怕变化。  

2. XP的迭代  
1）符合敏捷宣言的第二个原则：欢迎对需求提出变更，善于利用需求变更来获得竞争优势。  
2）用户故事：与Scrum相同，“作为一个...我希望...这样就能...”。  
3）故事点：变为以小时为单位。  
4）时间盒：以季度为周期，开会反思上一季度，明确这个季度的长期目标，挑选用户故事放入待办列表。  
5）时间盒：以一周为迭代，每个循环开始前，先召开会议审查当前进展，演示可用软件，与客户一起从待办列表仲挑选用户故事，并将用户故事分解为任务。周循环在每周同一天开始，但通常是周二或周三。  
6）松弛项：加入少量可选或不太重要的项，占用时间不超过周循环的20%。  

3. XP与Scrum的区别  
1）Scrum关注项目管理，每个sprint都以时间盒会议开始和结束，每天召开例行站会。需要一个全职产品负责人进行管理和细化产品待办列表。  
2）XP强调团队协作的重要性，以及构建代码的方式，并不太关注项目管理。  
3）Scrum独有的价值观：产品待办列表，经验主义，回顾会议，专注，承诺，开放。  
4）XP独有的价值观：季度循环，周循环，主题，松弛。  
5）Scrum和XP共有的价值观：用户故事，时间盒迭代，尊重，勇气。  

4. 构建XP团队  
1）建立在成员互相信任之上，允许成员犯错误，并协力克服困难。  
2）没有固定角色，无论是与用户交流、编写用户故事、设计用户界面、建立体系结构、构建代码，乃至项目管理等等，每个成员对与所有工作都会做一点。  
3）重视沟通，采用人小隔间+公共区域的构建信息化工作场所，在公共区域增加“信息辐射器”，利用“渗透式沟通”能吸收相关项目信息。  
4）保持轻松的心态，预留足够时间完成工作，消除干扰，犯错的自由，可持续的步调工作。  

5. **保持轻松的心态**  
1）预留足够时间完成工作：不现实的最后期限会打击士气，对于无法完成的工作，应该放到下一个迭代。  
2）消除干扰：2小时内关掉邮件或电话提醒，让自己进入心流状态。  
3）犯错的自由：在设计新特性、提出新想法、构建代码等过程中，承认失败在构建软件过程中无可避免。  
4）按可持续的步调工作：晚上周末不加班，平均每周40小时是团队获得最大生产力的最佳方法，即使有连续工作好几天的“紧张时期”，之后也应该进行适当休息，以保证稳定的发展速度和可持续的开发。  

6. XP为了拥抱变化，必须通过经常获得**反馈**来保证小的变更，而提出4种XP价值观  
1）迭代：不是先计划好6个月的工作，而是持续进行小更新来得到用户的反馈，再不断调整计划。  
2）集成代码：经常把新代码与其他团队成员的代码继承，尽早发现和解决冲突。  
3）单元测试：构建自动化单元测试，保证代码能正常工作。
4）队友审查：从队友得到反馈，帮助发现代码中存在的问题。  

7. 为了得到更多的**反馈**形成“**反馈回路**”，而提出的4种XP实践  
1）自动化构建：引入“10分钟构建”，利用自动化构建的脚本语言或工具构建服务器，定期从版本控制系统中获取最新代码运行自动构建，来更快速频繁地发现构建问题。  
2）持续集成：每个团队成员每隔几小时就进行一次集成和测试他们的变更，利用版本管理工具，可解决不同成员对同一文件进行变更而造成的代码冲突问题。  
3）测试驱动开发：在增加新代码之前，首先写一个失败的单元测试，再编写修改代码使他通过测试。  
4）结对编程：两人一起在同一台电脑上写代码，好处是：保持专注、互相讨论、思路清晰、捕捉错误、参与整个项目的各个环节、以及不太容易投机取巧。  

8. 其他能够得到更多**反馈**的设计和测试工具  
1）线框图（Wireframes）：用于在构建用户界面前花出草图，以此尽早且经常得到对用户界面的反馈。  
2）Spike解决方案：架构Spike用于证明一个特定技术方案的可行性，基于风险的Spike用于去除项目中的风险。  

9. 让代码更简单  
1）简单符合敏捷原则第十二项“要做到简洁，尽最大可能减少不必要的工作。”。  
2）将一个做太多事情的单元分解为更小的单元，每个单元只做一件事。  
3）尽可能地重构代码，在功能不变的基础上改变其结构，使之更简单。  
4）养成习惯，每次看到可以重构的代码就进行重构。  
5）不要为了可重用性，就牺牲简单性。  
6）及时偿还技术负债，“未修复”的设计和代码问题存在的时间越长，衍生的问题就越多。  
7）在简化每个单元的设计同时，建立增量式设计的习惯来处理系统。  

---

# 第六章————精益/看板：消除浪费和管理流动

1. 精益思想（Lean Thinking）概念  
只是一种思维模式，而不是一个方法论，不包含实践。其基本原则是，确保团队采用的流程有助于构建对客户有价值的产品。其主要作用是，利用提供的工具来检查流程上出现的阻碍达成目标的问题，从而修正这些问题。  

2. 7大原则  
1）消除浪费：实际做的工作多于真正需要做的工作。  
2）增强学习：利用反馈，观察改变后的结果，再决定下一步，进行不断迭代的改进。  
3）尽晚决定：在得到尽量多的信息后的最后责任时刻，才做出重要的项目决策。不要强制提前做出决定。  
4）尽快交付：跟踪流程，利用拉动系统、队列和缓冲区来均衡工作，减低延迟对团队的影响。  
5）授权团队：允许团队决定工作的最有效方法。
6）建构完整性：用户了解构建的软件来评价团队的工作质量。  
7）综观全局：采取适当的度量方式，让团队每个人得到需要的信息来做出正确的决定。  

3. 更多的精益思维工具  
1）查找浪费：找出对构建有价值商品没有帮助部分，例如编写没人读的文档。  
2）价值流程图：以完成一个特性为最小块，从开始讨论，到最后交付，算出各步骤间的等待时间，就是浪费。  
3）排队论：用于确保团队工作负荷过重，使他们有足够的时间来采取正确的工作方式。  
4）拉动系统：不是由客户或产品负责人向团队推送任务，而是开发团队主动从待办列表中拉取需求。  
5）选项思维：在团队拉去需求时，并不说明是给用户的承诺，只确保团队尽其所能完成产品工作。  
6）**延迟成本**：风险较高的任务与风险较低的任务相比，延迟高风险工作所付出的成本更高。  
7）感知完整性/概念完整性：一个特性是否能满足客户需求/多个特性间能否充分合作形成一个统一的产品。  

4. 查找7种浪费  
1）部分完成的工作（Partially Done Work）  
在一个任务过程中要等待某个信息或批准的时候，又开始了一个新的任务，最后导致前一个任务只是完成了部分工作。  
2）多余的流程（Extra Processes）  
对于交付软件没有帮助的流程，反而增加团队的工作。例如，编写不会交付的文档，召开不会结束的会议等。  
3）多余的特性（Extra Features）  
以为尝试的新技术新特性对项目有革新的好处，结果却是不仅占用团队时间，而且对用户来说没有价值。  
4）任务切换（Task Switching）  
通常是由于开发人员的过度承诺引起，为的是面子而同时在3~5个任务间切换。只要存在2个优先级相当的任务间切换，就说明在浪费时间。  
5）等待（Waiting）  
包括等待物理硬件的配置，或是DBA把数据库准备好等等的情况，只能尽可能减少这种等待时间。  
6）动作（Motion）  
团队成员需要沟通时，进行的位置移动，无论是办公室内，还是市内或城际间远距离移动，所产生的时间成本浪费。  
7）缺陷（Defects）  
构建软件过程中所产生的缺陷发现得越晚，找出和修正缺陷所需要得时间就越多，必须尽早发现处理解决。  

5. 价值流程图  
1）作用：显示造成浪费而导致工作减慢的步骤在流程中的具体位置。  
2）公式：（100 ✖ 工作时间 ➗ 交付时间）%  
3）可能性：开发人员在完成开发和单元测试后就开始开发一个新特性，导致需要同时处理开发和测试管线上的4到5个不同位置的特性。由于设计的高度耦合，特性必须成批发布，导致测试和部署的整体延后。  

6. 丰田制造系统（Toyota Production System，TPS）  
1）3大浪费来源（3M）：Muda（浪费），Mura（不均衡），Muri（高负荷）。  
2）7种制造浪费：库存、运输、过量生产、过度加工、等待、动作、缺陷。  
3）改善质量：自动化（Jidoka）、看板（Kanban）、拉动系统（Pull System）、基本原因分析（Root Cause Analysis）、改善（Kaizen）。  

7. 选项思维  
1）并不会一成不变地按照计划实施，而是根据情况调整任务的优先度，选择适当的任务来进行。  
2）情况随时都会发生变化，保证团队有足够的自由，尽晚决定，减少变更带来的成本。    

8. 纵观全局  
团队所有成员都应该能了解团队内的一切工作，而不是只考虑某一个角色或岗位的业务内容。  

9. 拉动系统  
1）流程中的下游步骤会从它前面的步骤拉取工作，下游步骤在没有拉取前，前面步骤则无法继续。  
2）为了实现上面机制，进行限制在制品（Work In Progress，WIP）来减少整个交付时间。  

10. 限制在制品（Work In Progress，WIP）的目的  
1）激励团队中每个人都保持忙碌状态。  
2）减少“部分完成的工作”和“多任务切换”带来的浪费。  
3）避免因为接受计划以外的开发请求导致请求堆积，造成在迭代结束时得到大量半成品的结果。  

11. 看板（Kanban）  
1）基于精益思维：不指定角色，没有特定项目管理或开发的具体方法。  
2）可视化工作流：纵观全局（例如：定义、设计、构建、集成、测试、部署）  
3）限制WIP：保证拉动系统的正常运作。  
4）管理流动：观察工作过程中的速度，来调整管理流程步骤。  
5）显式化流程策略：显示工作状态，如工作步骤、进度、状态等。  
6）实现反馈回路：让团队实现所有策略和改进，度量效果，确保有效性。  
7）协作式改进并且实验性进化：最终使整个工作流程越来越有效。  

12. 任务板和看板的区别  
1）任务板用于项目管理：待办，进行中，完成  
2）显示任务状态，进度跟踪，优先级，自组织  
3）看板用于流程管理：定义、设计、构建、集成、测试、部署  
4）显示所有特性，WIP限制，工作流，允许变更

13. 创建一个工作流  
1）定义：产品负责人从用户得到一个特性请求，并编写用户故事。  
2）计划：团队决定下一个发布包含的特性。  
3）构建/测试：团队构建特性并完成代码审查。  
4）集成：团队测试集成的特性，并修正bug。  
5）用户验收测试（UAT）：最终用户评估特性。  
6）完成：将这个特性包含在下一个版本中发布。  

---