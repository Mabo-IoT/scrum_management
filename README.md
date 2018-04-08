# [a more better version](http://scrumreferencecard.com/scrum-%E5%8F%82%E8%80%83%E5%8D%A1/)

# 定义
- ### transparency 透明化
- ### inspection 查看 跟踪
- ### adaptation 调整

# 方法
- sprint（冲刺目标） planning
- daily scrum
- sprint review
- sprint retrospective 回溯

# 价值观
- commitment， courage，focus， openness， respect


# 团队
- ### product owner(定义工作成果是否完成并合格)，管理product backlog
    - 清晰发布并表述   product backlog（产品需求日志）
    - 按适当排列顺序和优先级发布
    - 完善development的工作成果
    - 确保backlog的可视化，透明化，以及团队可理解性，以及下一步做什么
    - 确保development team了解product backlog的优先级
    
    - #### product owner 必须是一个人而不是委员会（确保需求无扯皮，以及发布的及时性），如果想改变任务优先级，必须要通知product owner，团队中的每个人必须尊重product owner的决定，任何人都不能强迫development团队去做product backlog 要求以外的工作！

- ### development team 由做product开发的专业开发人员构成，每一个Done 需要sprint review，只有development team才能控制done事件的增量，通过内部协作来达到最大效率，特性如下：
    - 自我组织管理，任何人不得命令或告知development team 如何将product backlog 转化为实质的工作成果（防止外界对任务的干扰），即使是scrum master！
    - development team 是cross-functional(全栈...)，相互帮助，以确保product的增量完成
    - development team内无title，以防工作内容只分配到某个人身上，或成果只分配到某个人身上
    - 在development内不存在什么sub-team，子开发团队，以防再分出测试，架构，分析等等团队(团队每个成员的内容按任务分配，而不是按职能分配)
    - 也许每个成员有自己擅长或特殊的领域，但是要把整个team看成一个整体，不能擅自分割
    - ##### 团队人员数量
        - 原则上确保小而精，但是有能力应对目前大型复杂项目工程。
        - for example ： 小于3个虽然足够敏捷，但是可能无法应对大型项目工程，大于9个虽然看起来能力足够，但是会增加更多的交流沟通成本
        - product owner 和 scrum master 不在此列，除非他们也参与 开发工作
- ### scrum master（促进和支持team向敏捷开发流程靠拢，帮助每一个成员了解敏捷开发理论，规则以及价值观，类似于servant-leader角色，并负责与scrum团队外界的沟通交流）
    - ### scrum master to product owner
        - 确保product的目标，内容，领域让每一个scrum team 成员了解
        - 找到更适合product backlog管理的技术
        - 帮助scrum team 理解每一条backlog的具体含义
        - 通过经验，理解产计划
        - 确保product owner了解如何安排product backlog 去最大化产出价值
        - 理解敏捷性
        - 促进敏捷性开发事件的实施；
    - ### scrum master to development team
        - 辅导 development team 的自我组织管理和内部功能交叉管理
        - 帮助 developemt team 产生高价值性的产品
        - 隔离并移除妨碍development team进度的事情；
        - 促进敏捷开发事件的实施
        - 促进敏捷开发环境的培养，当团队偏离敏捷开发时，及时纠正；

    - ### scrum master to the organization
        - 促进整个团队敏捷开发氛围的养成

# scrum events
- 所有的events都有时间窗口，一旦一个sprint开始，其时间窗口不能被缩短或延长。
- sprint 是events容器，events 是用来确保项目整体进度的透明性以及可追踪性

    ## sprint
    ### sprint 是scrum的核心，一个时间节点容器去追踪事件，直到事件done，每一个sprint都会在上一个sprint结束时立即开启

    - ### sprint 包括 sprint planning，daily scrum，the development work， the sprint review，sprint retrospective

    - ### 在sprint 期间
        - 不能随意改动，以防危及到sprint 整体目标
        - sprint 质量保证不能减少
        - product owner 与 development team 要及时沟通，确定时间及内容节点
    - ### 每一个sprint必须看成一个项目，最好在不超过一个月的时间内完成。如果不在一个月内完成，那么sprint的目标就可能改变，复杂性就会提升，那么项目的未完成风险就会增加。sprint能保证至少一个月内项目进度以及项目目标的可追踪性，也会将整体风险限制在一个月内。
    - ### cancelling a sprint
        - sprint 可以在sprint时间窗口期内关闭，只有product owner有权限去关闭一个sprint
        - 当sprint goal 改变时，可以取消sprint。当项目目标或者技术变更时，也许会发生sprint goal 改变的情况，但是由于一个sprint的时间窗口很短，所以这种情况一般很少发生
        - 当sprint cancelling发生时，所有这个sprint下完成的工作要进行review。已完成的工作移交prodoct owner，未完成的记录prodocut log
        - sprint cancellation 会耗费很多资源，这一般会给团队带来很大创伤（积极性以及工作效率）

    - ### sprint planning
        - #### sprint planning 一般用来创建 sprint events，确定时间窗口，sprint master 组织plan，确保每个人理解项目目标，创建合理的 sprint event
    - #### 主题如下
        - ##### 在这个sprint 里要做什么
            - development team 列出这个sprint要做的功能性需求；product owner 讨论了解 这个sprint要到达的目标，如何才能算是完成这个目标；这个topic输入的是product backlog（项目要求），项目进度安排，development team的项目容量，以及development过去的产出效率。项目能完成多少预期目标进度完全取决于development team，只有development team 可以声明在这个即将到来的sprint里要实现多少需求。
            - 在plan中产生一个sprint goal，这个goal与product backlog（项目需求）吻合，并产生一个能让development team明白为何要做这些的原因
        - ##### 怎么完成sprint里的工作
            - 通过对goal的分解，development team决定需要分配哪些完成这个goal的小需求，product backlog（项目需求）和这个sprint 需要做的需求一起组成了sprint backlog
            - 分解sprint需求
            - product owner 和 development team 讨论决定任务量的多少
            - sprint planning 会议结束，development team 应该向product owner 和 scrum master解释如何去完成sprint goal，需要分解成哪些小目标去做

    - ### sprint goal
        - sprint goal 需要能满足 product backlog（项目需求）
        - 如果觉得偏离项目需求，必须重新讨论sprint backlog

    ## Daily scrum
    - ### 一个15分钟的会议，会上，development team 交流接下来的工作，每天同一时间，同一地点举行以消除其复杂性
        - 昨天工作内容
        - 今天工作计划
        - 工作上问题

    - ###  scrum master 确保会议的举行，但是责任是development team的，scrum master确保会议在15分钟以内
    - ### 这一会议可以追踪进度，增加团队内部沟通，提升团队协作水平和技术水平

    ## sprint review
    - ### 在sprint结束时举行，以讨论goal是否完成，项目需求是否满足。这是信息交流会进度追踪会，其目的是反馈和沟通
    - ### 如果是一个1月的sprint事件需要4小时的会议，shorter for shorter
    - ### 主题包括：
        - 与会人员scrum team和其他项目相关者
        - product owner汇报项目整体上哪些完成了，哪些未完成
        - 开发团队讨论sprint中做的好的与不好的方面
        - 开发团队解释sprint做了哪些，回答关于sprint进度的问题
        - product owner 确定项目进度需求以及项目进度日期
        - 整体讨论接下来该做什么（所以也是sprint planning的一个预热）
    
    ## sprint retrospective
    - ### 3小时for 1月 sprint，shorter for shorter
    - ### 在sprint review 和 下一个sprint planning中间
    - 主题：
        - 回溯上一个sprint中与敏捷开发有关的人、关系、进度、工具
        - 讨论敏捷开发流程中好的与不好的流程
    - ### 主要用于scrum流程的改进与scrum团队的建设

# scrum artifacts
- ### product backlog
    - 整个项目需要完成的进度，product owner对此负责，包括项目内容，可实施性，可操作性以及项目优先级
    - product backlog（项目进度需求）nerver complete！！项目需求是动态的！！
    - 优化工作不超过10%
    - development team 负责所有工作的完成
- ### monitoring progress toward goals
    - 燃尽图等可视化工具有助于进度的管理，但是还是要依靠经验，因为在复杂环境下，谁也无法预料即将发生的事情，但是发生过的事情可以用作未来的参考

- ### sprint backlog
    - 区别于product backlog， 一个追踪整体项目，一个追踪一个sprint里的进度
    - sprint backlog细节要丰富，即每一步都有所记录和体现
    - 只有开发团队能改变sprint backlog

- ### monitoring sprint progress
    - 任何时间内，都能清晰地看到sprint backlog的总数
    - development team 通过追踪backlog，可以追踪项目的进度
- ### increment
    - 项目进度增量是现在sprint和以前sprint完成的全部增量
    - 增量需可视化

# artifact transparency
- scrum 依赖透明化，所以必须要一起努力做到透明化
- ## definition of “done”
    - 必须要制定好完成的标准！