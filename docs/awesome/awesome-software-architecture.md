<div class="github-widget" data-repo="simskij/awesome-software-architecture"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins>
<div align="center">

<img src="https://raw.githubusercontent.com/simskij/awesome-software-architecture/master/./banner.png" />

## Awesome Software Architecture<br/>
  
[![awesome-badge](https://awesome.re/badge.svg)](https://awesome.re)
  
[Software architecture](https://en.wikipedia.org/wiki/Software_architecture) 旨在描述高层次 
软件的结构以及创建它们的准则. 由于该主题范围很广，因此可能 
包含一些在更多细分市场中也存在的资源. 
  
</div>



## Principles
- [Flexibility](https://medium.com/faun/flexibility-a-software-architecture-principle-6eafe045a1d4) -能够适应环境和可用性要求的变化，而无需涵盖结构变化.

## Design Patterns
- [Ports and adapters pattern](https://jmgarridopaz.github.io/content/hexagonalarchitecture.html) -将应用程序核心逻辑与其使用的服务分离.
- [Observer pattern](https://medium.com/datadriveninvestor/design-patterns-a-quick-guide-to-observer-pattern-d0622145d6c2) -一对多状态更改通知.
- [Design Patterns: Elements of Reusable Object-Oriented Software, by Gamma et al](https://www.amazon.com/Design-Patterns-Elements-Reusable-Object-Oriented/dp/0201633612/) -开始一切的那个：orange_book:.
- [Software Design Patterns: A Guide](https://airbrake.io/blog/design-patterns/software-design-patterns-guide) -常见软件设计模式简介.
- [Software Design Patterns and Principes (quick overview)](https://www.youtube.com/watch?v=WV2Ed1QTst8) -常见设计模式的原因以及它们的优点和缺点.
- [CQRS](https://docs.microsoft.com/en-us/azure/architecture/patterns/cqrs) -使用单独的接口将读取数据的操作与更新数据的操作分开.
- [Event Sourcing](https://docs.microsoft.com/en-us/azure/architecture/patterns/event-sourcing) -不仅将数据的当前状态存储在域中，还可以使用仅追加存储来记录对该数据执行的全部操作.
- [Feature Toggles](https://www.martinfowler.com/articles/feature-toggles.html) -功能切换（通常也称为功能标志）是一项强大的技术，可让团队无需更改代码即可修改系统行为.
- [Behavior Driven Development (BDD) and Functional Testing](https://medium.com/javascript-scene/behavior-driven-development-bdd-and-functional-testing-62084ad7f1f2) -BDD使用易于理解的软件用户需求描述作为软件测试的基础.
- [N-tier architecture style](https://docs.microsoft.com/en-us/azure/architecture/guide/architecture-styles/n-tier) -层是一种分离职责和管理依赖关系的方法.

### Scalability and Resilience
- [Circuit Breaker](https://martinfowler.com/bliki/CircuitBreaker.html) -保护故障资源以防止级联故障
- [Bulkhead](https://docs.microsoft.com/en-us/azure/architecture/patterns/bulkhead) -分区资源以隔离故障

## Methodology

- [No silver bullet, by Brooks](http://worrydream.com/refs/Brooks-NoSilverBullet.pdf) -以小幅增长的方式开发软件：orange_book:.
- [Clean Architecture, by Martin](https://www.amazon.com/Clean-Architecture-Craftsmans-Software-Structure/dp/0134494164) -构建可持续和可维护软件的关键原理和概念：orange_book ：.
- [Technical Debt, by Fowler](https://martinfowler.com/bliki/TechnicalDebt.html) -累积技术债务的成本和影响.
- [The Magic Tricks of Testing, by Metz](https://www.youtube.com/watch?v=URSWYvyc42M) -简约的理想作为一种实用的软件测试方法.
- [TDD, Where did it all go wrong?, by Cooper](https://www.infoq.com/presentations/tdd-original/) -关于TDD做法和界限的建议，以减少耦合.

## Documentation

- [arc42](https://arc42.org/) -用于软件和系统架构的文档记录和通信的模板.
- [Architectural Decision Records](https://adr.github.io/) -版本和文档架构决策与使用代码的方式相同.
- [Documenting architecture](https://dzone.com/articles/documenting-architecture-1) -关于如何有效记录软件体系结构的实用技巧.


## Workshop formats

- [Event Storming](https://www.eventstorming.com/) -探索领域驱动设计的格式.
- [MoSCoW Prioritization](https://www.knowledgehut.com/blog/agile/how-to-prioritise-requirements-with-the-moscow-technique) -快速而简捷地确定需求优先级的方法.
- [Story mapping](https://www.jpattonassociates.com/wp-content/uploads/2015/03/story_mapping.pdf) -通过创建故事图可视化您的需求.
- [Impact mapping](https://www.impactmapping.org/) -用于构建产品和交付项目的战略规划技术.
- [Business Model Canvas](https://en.wikipedia.org/wiki/Business_Model_Canvas) -使业务计划变得简单而直观.
- [Business Model Generation, by Osterwalder & Pigneur](https://www.amazon.com/Business-Model-Generation-Visionaries-Challengers/dp/0470876417) -轻松可视化您的价值主张，成本和收入流：orange_book:.

## Modeling

- [The C4 Model](https://c4model.com/) -使用上下文，容器，组件和代码描述软件.
- [Wikipedia: Data modeling](https://en.wikipedia.org/wiki/Data_modeling) -简短的数据建模简介.

## Tools

- [Sparx Systems Enterprise Architect](https://sparxsystems.com/products/ea/index.html)  -面向对象的建模套件. 仅适用于Windows.
- [Visual Paradigm](https://www.visual-paradigm.com/)  -与Enterprise Architect类似. 适用于多个平台.
- [Lucidchart](https://www.lucidchart.com)  -付费的基于云的图表编辑器. 在所有常见平台上均可用.
- [Draw.io](https://www.draw.io)  -自由和简单的图表编辑器. 与Visio及其同类产品相当. 在所有常见平台上均可用.
- [Structurizr](https://structurizr.com) -基于C4模型的建模工具（请参见上文）.
- [PlantUML](http://plantuml.com/) -与图表的减价一样，PlantUML将类似英语的语法渲染到图表中.
- [PlantUML for Atlassian](https://marketplace.atlassian.com/apps/1215115/plantuml-for-confluence-cloud?hosting=cloud&tab=overview) -在Atlassian套件中增加了对基于PlantUML的图的支持.

## Frameworks

### Agile

- [Scrum](https://www.scrumguides.org/) - Framework for developing and maintaining complex products.
- [SAFe](https://www.scaledagileframework.com/) -可扩展的敏捷框架.
- [Nexus](https://www.scrum.org/resources/scaling-scrum) -Scrum联合创始人Ken Schwaber表示，可扩展Scrum. 
- [The death of Agile, by Allen Holub](https://www.youtube.com/watch?v=HZyRQ8Uhhmk&feature=youtu.be) -“敏捷”如何摆脱了敏捷性的基本原理，以及我们需要做些什么来解决问题.
- [Agile Architecture Pt. 1, by Allen Holub](https://www.youtube.com/watch?v=0kRCFVGpX7k) -在敏捷世界中我们如何与建筑合作. 
- [Agile Architecture Pt. 2, by Allen Holub](https://www.youtube.com/watch?v=txbS0WJC1bo) -在敏捷世界中我们如何与建筑合作. 
### Lean software development

- [Wikipedia: Lean Software Development](https://en.wikipedia.org/wiki/Lean_software_development) -面向软件开发领域的精益生产的翻译.
- [Rolling rocks downhill, by Clarke Ching](https://www.amazon.com/Rolling-Rocks-Downhill-Software-Projects/dp/1505446511) -有关敏捷和精益软件开发的商业小说：orange_book ：.
- [The Goal: A Process of Ongoing Improvement, by Goldratt](https://www.amazon.com/Goal-Process-Ongoing-Improvement/dp/0884270610)  -有关制造环境中持续改进的商业小说. 容易适应软件开发：orange_book:.
### Extreme programming

- [Extreme Programming](http://www.extremeprogramming.org/) -最流行的敏捷过程中最具体的部分，重点是工程和开发实践.

### DevOps

- [Wikipedia: DevOps](https://en.wikipedia.org/wiki/DevOps) -结合软件开发和运营实践，以缩短上市时间，同时保持高质量.
- [The Phoenix Project, by Gene Kim et al](https://www.amazon.com/Phoenix-Project-DevOps-Helping-Business/dp/0988262592) -IT，Devops并帮助您赢得业务：orange_book ：.
- [The Unicorn Project, by Gene Kim](https://www.amazon.com/Unicorn-Project-Developers-Disruption-Thriving-ebook/dp/B07QT9QR41) -开发人员，数据时代的数字颠覆与繁荣：橙色图书：.
- [Keep CALMS and carry on](https://dwpdigital.blog.gov.uk/2019/03/25/keep-calms-and-carry-on-how-we-do-devops/) -BPDTS如何使用CALMS模型作为其devop适应的参考。 
- [Chaos Engineering at Netfix](https://www.youtube.com/watch?v=6ilMZqKdMMU) -混沌工程学是软件工程学中的一门新学科，使人们对大规模分布式系统的行为充满信心. 
- [Adidas DevOps Maturity Framework](https://github.com/adidas/adidas-devops-maturity-framework) -根据CALMS对DevOps的定义，该框架定义了一组功能和指南，这些功能和指南在被采用时可提高团队的效率，效力和幸福感.
## Bonus

- [How to learn software design and architecture - a roadmap](https://www.freecodecamp.org/news/software-design/) -有助于了解对软件体系结构的牢固了解的其他内容.

## Contributing

想要为使此列表变得更好做出贡献吗？ 是的，太棒了！ 在开始之前，请先阅读我们<a href="code_of_conduct.md">的行为准则</a>和<a href="contributing.md">贡献准则</a>.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

在法律允许的范围内， [simskij](https://github.com/simskij) 放弃了此作品的所有版权以及相关或邻近的权利.
