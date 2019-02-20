# Summary

----------------------------------------------------------------------------------------------------------------------------

- Author: Chen Meng
- Date: 2019/01/31
- This is a summary of the first training meeting at Thoughworks on 2019/01/26
- **GitHub link: [Summary.md](https://github.com/NickMengChen/Summary_Jan2019.git)**

----------------------------------------------------------------------------------------------------------------------------



## Culture

- 专业IT服务型公司
- 5000+， 14 国家， 40间办公室
- Roy Sigham 20世纪80年代创办
- 3 Pillars
- 经营可持续的业务
- 推动IT变革，追求软件卓越
- 积极提倡社会和经济公正



### 经营可持续的业务

​    IT 组织优化，技术咨询，测试策略，客户体验
​    
​    和客户一起完成机器复杂的项目和软件，尽可能快速地讲概念转化成价值
​    
​    ### 推动IT变革，追求软件卓越s
​    
​    **技术雷达**: Thoughworks 每年都会有两期技术雷达的报告。
​    
​    
​    
​    ![avatar](https://raw.githubusercontent.com/NickMengChen/Summary_Jan2019/master/pic/Tec.png)
​    
​    
​    
### 积极提倡社会和经济公正
- ​社会公正工作，招聘和多样性
​    
## Agile (敏捷方法)
### 敏捷宣言
​    
​    **个体和互动** 高于 流程和工具
​    
​    **工作的软件** 高于 详尽的文档
​    
​    **客户合作** 高于 合同谈判
​    
​    **响应变化** 高于 遵循计划
​    
### Scrum
​    
​    ​    ![avatar](https://raw.githubusercontent.com/NickMengChen/Summary_Jan2019/master/pic/Scrum.png)
​    ​    
​    ​    From Wiki:
​    ​    
​    ​    > **Scrum** is an agile framework for managing knowledge work, with an emphasis on software development. It is designed for teams of three to nine members, who break their work into actions that can be completed within timeboxed iterations, called “**sprints**”, no longer than one month and most commonly two weeks , then track progress and re-plan in 15-minutes stand-up meetings, called daily scrums.
​    ​    
​    ​    ​    See: [Scrum](https://en.wikipedia.org/wiki/Scrum_(software_development))
​    ​    ​    
#### Roles:
​    ​    ​    
Product owner: The product owner represents the product’s stakeholders and the voice of the customer, is responsible for the product backlog and accountable for maximising the value that the team delivers.
​    ​    ​    ​    
Development team: The development team is responsible for delivering potentially shippable product increments every sprint.
​    ​    ​    ​    ​    
Scrum Master: Scrum is facilitated by a scrum master, who is accountable for removing impediments to the ability of the team to deliver the product goals and deliverables.
​    ​    ​    ​    ​    ​    
### XP
​    ​    ​    ​    ​    ​    
​    ​    ​    ​    ​    ​    ![avatar](https://raw.githubusercontent.com/NickMengChen/Summary_Jan2019/master/pic/xp.png)
​    ​    ​    ​    ​    ​    
From wiki:
​    ​    ​    ​    ​    ​    
> **Extreme programming (XP)** is a software development methodology which is intended to improve software quality and responsive to changing customer requirements. As a type of agile software development, it advocates frequent “Release” in short development cycles, which is intended to improve productivity and introduce checkpoints at which new customer requirements can be adopt.
​    ​    ​    ​    ​    ​    
 See: [Extreme Programming](https://en.wikipedia.org/wiki/Extreme_programming)
​    ​    ​    ​    ​    ​    ​    
### 敏捷方法之极限编程和Scrum的区别
​    ​    ​    ​    ​    ​    ​    
See: [百度百科“Scrum”](https://baike.baidu.com/item/Scrum/1698901?fr=aladdin)
​    ​    ​    ​    ​    ​    ​    ​    
#### 区别一：**迭代长度不同**
​    ​    ​    ​    ​    ​    ​    ​    
​    ​    ​    ​    ​    ​    ​    ​    ​    XP的一个Sprint的迭代长度大约是1-2weeks，但是Scrum的迭代长度是2-4weeks
​    ​    ​    ​    ​    ​    ​    ​    ​    
#### 区别二： **迭代中，是否允许修改需求**
​    ​    ​    ​    ​    ​    ​    ​    ​    
XP在一个迭代中，如果一个User Story(用户素材, 也就是一个需求)还没有实现， 则可以考虑用另外的需求将其替换， 替换的原则是需求实现的时间量是相等的。而Scrum是不允许这样做的，一旦迭代开工会完毕, 任何需求都不允许添加进来，并有Scrum Master严格把关，不允许开发团队受到干扰。****
​    ​    ​    ​    ​    ​    ​    ​    ​    ​    
#### 区别三： **在迭代中，User Story是否严格按照优先级别来实现**
​    ​    ​    ​    ​    ​    ​    ​    ​    ​    
XP是务必要遵守优先级别的。但Scrum在这点做得很灵活，可以不按照优先级别来做，Scrum这样处理的理由是：如果优先问题的解决者，由于其它事情耽搁，不能认领任务，那么整个进度就耽误了。另外一个原因是，如果按优先级排序的User Story #6和#10，虽然#6优先级高，但是如果#6的实现要依赖于#10，则不得不优先做#10。
​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    
#### 区别四： **软胶囊的实施过程中，是否采用严格的工程方法，保证进度或者质量**
​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    
Scrum没有对软件的整个实施过程开出工程实践的处方，要求开发者自觉保证。但XP对整个流程方法定义非常严格，规定需要采用TDD、自动测试、结对编程、简单设计、重构等约束团队的行为。
​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    
### Workflow
​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    
See: [Scrum](https://en.wikipedia.org/wiki/Scrum_(software_development))
​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    
#### Daily Scrum(stand-up)
​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    
**All members of the development team come prepared. The daily scrum:**
​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    
*Starts precisely on time. Check missing*
​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​        
*Happen at same time and place everyday.*
​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​        ​        
*maximum 15 mins*
​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​        ​        ​        
**Anyone is welcome, though only development team members should contribute**
​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​        ​        ​        ​    
**Three QUESTIONS**
​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​        ​        ​        ​    ​    
*What did I complete yesterday that contributed to the team meeting our sprint goal?*
*What do I plan to complete today to contribute to the team meeting our sprint goal?*
*Do I see any impediment that could prevent me or the team from meeting our sprint goal?*
​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​        ​        ​        ​    ​    ​        ​        ​        
#### Sprint Planning
​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​        ​        ​        ​    ​    ​        ​        ​        
- **At the beginning of a sprint, the scrum team holds a sprint planning event to**
- Mutually discuss and agree on the scope of work that is intended to be done during that sprint
- Select product backlog items that can be completed in one sprint
- Prepare a sprint backlog that includes the work needed to complete the selected product backlog items
- The recommended duration is four hours for a two-week sprint (pro-rata for other sprint durations)
- During the first half, the whole scrum team (development team, scrum master, and product owner) selects the product backlog items they believe could be completed in that sprint
- During the second half, the development team identifies the detailed work (tasks) required to complete those product backlog items; resulting in a confirmed sprint backlog
- As the detailed work is elaborated, some product backlog items may be split or put back into the product backlog if the team no longer believes they can complete the required work in a single sprint
- Once the development team has prepared their sprint backlog, they forecast (usually by voting) which tasks will be delivered within the sprint.
​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​        ​        ​        ​    ​    ​        ​        ​        
## Feedback
​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​        ​        ​        ​    ​    ​        ​        ​        
### 反馈的套路 - **SBI**
- 在什么情况下 (situation)
- 观察到的行为 (Behaviour)
- 造成的影响 (Impact)
- 反思 (Reflection) (optional)
​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​        ​        ​        ​    ​    ​        ​        ​        
### 通用句式
**基于行为**：我看到了。。。想找你确认下
**对话**：有空吗？想找你聊一下，找个安静的地方可以吗？
**不要激进**：我观察到。。。我猜测是。。。想找你确认下是这样吗？
**安全私人的环境** : 我们找个会议室吧。
​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​        ​        ​        ​    ​    ​        ​        ​        ​    ​    ​    ​    
#### Feedback 公式
特定的时间+观察到的行为+你的感受+平等的私人对话+可执行的建议+继续的支持
​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​        ​        ​        ​    ​    ​        ​        ​        ​    ​    ​    ​    ​        
### 如何接受反馈
​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​        ​        ​        ​    ​    ​        ​        ​        ​    ​    ​    ​    ​        
不要抗拒+有效倾听+表达感谢+采取行动
​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​        ​        ​        ​    ​    ​        ​        ​        ​    ​    ​    ​    ​        ​        
## Retrospective
​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​        ​        ​        ​    ​    ​        ​        ​        ​    ​    ​    ​    ​        ​        
**目的**： 团队通过对本迭代的⼯工作过程进⾏行行回顾，分析团队的改进空间，回顾会是保持团队持续改善的重要⼯工具。
**时机**：在下个迭代的计划会议之前开展，例例如迭代最后⼀一周的周五下午，时⻓长不不超过2⼩小时
**WHO**： 全体团队成员，SM组织
**HOW**：
​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​        ​        ​        ​    ​    ​        ​        ​        ​    ​    ​    ​    ​        ​        ​    ​    ​    ​    
- 会前收集迭代过程的数据，包括但不不限于未完成的⽤用户故事、燃尽图、迭代产能、质量量数据、 业务数据变化、活动执⾏行行效果数据等
- 会前，团队成员应清晰明确迭代⽬目标的达成情况
-  会议⼀一开始，团队⾸首先回顾本迭代的过程和收集的数据
-  团队就上个迭代的运作情况采⽤用头脑⻛风暴暴⽅方式提出有哪些是做得好的、不不好的、以及问题
-  团队就不不好的⽅方⾯面，集体制定改进建议，并制定⾏行行动措施和计划
-  团队成员认领改进措施，在后续迭代内跟进措施的执⾏行行情况
**WHAT**: 团队的改进Backlog（包括改进点和负责⼈人）、团队更更新的⼯工作协议
​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​        ​        ​        ​    ​    ​        ​        ​        ​    ​    ​    ​    ​        ​        ​    ​    ​    ​    
### 原则
​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​        ​        ​        ​    ​    ​        ​        ​        ​    ​    ​    ​    ​        ​        ​    ​    ​    ​    
1. Scrum Master要引导团队整体产⽣生改进建议和制定措施，不不是⾃自⼰己发⽣生问题，⾃自⼰己制定措施
2. 回顾会议对事不不对⼈人，不不要演变成批⽃斗会
3. 回顾会议要营造⼀一个开放、⾃自由、正向的⽓气氛，不不要演变成吐槽会
4. 好的，不不好的地⽅方，都应以实例例来说明，⽽而⾮非感觉
5. Action应该是在下个迭代就能看到成效，且必须有Owner
6. Action由SM纳⼊入到团队的待办事项列列表中
​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​    ​        ​        ​        ​    ​    ​        ​        ​        ​    ​    ​    ​    ​        ​        ​    ​    ​    ​    
