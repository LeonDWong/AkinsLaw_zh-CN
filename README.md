## Preview

在某次订阅邮件中看到这篇 [Akin's LAWS](http://spacecraft.ssl.umd.edu/akins_laws.html?__s=ecoqrensc6fdgmbksadk)，感觉里面的观点对于一个工程师来说都是值得借鉴和思考的，故而凭借着自己有限的理解能力和翻译能力进行了汉化，以此自省，如何做一个更好的工程师。

## Laws

> 带 \* 的是目前还无法很好理解的，如果有任何观点，欢迎在 issue 里提出。

1. 工程化是由数字完成的。不包含数字的分析仅仅是观点。

   > Engineering is done with numbers. Analysis without numbers is only an opinion.  
   > `个人理解：成功的工程化是可以估量的，而估量必须要有数据。这对于软件开发亦是同理，你的应用快了多少？PV、UV 增加了多少？等等，这些都是可衡量的，并且是非常宝贵且必须的数据。`

2. 设计一个好的太空船会花费无止尽的努力。这就是为什么在问题出现的时候再去通过设计使他们运行是一个好主意

   > To design a spacecraft right takes an infinite amount of effort. This is why it's a good idea to design them to operate when some things are wrong.  
   > `个人理解：对于一个应用的开发历程，没办法一开始就设计的 100% 完美，必须通过不断的迭代，发现问题，解决问题来完善应用，与 Scrum 中的‘行走的骨架’类似。`

3. 设计是一个可迭代的过程。必要的迭代数比你已经做完的迭代数更多。这在任何时候都是真实存在的。

   > Design is an iterative process. The necessary number of iterations is one more than the number you have currently done. This is true at any point in time.  
   > `个人理解：一个好的项目迭代是无止境的，除非这个项目死了`

4. 你最好的设计的努力将会不可避免的在最后设计中变得没用。学会拥抱失望。

   > Your best design efforts will inevitably wind up being useless in the final design. Learn to live with the disappointment.  
   > `个人理解：针对某个技术进行调研，可能你准备了 3 套方案，最终被采纳的，不是你认为最好的方案。Take it easy。`

5. 3点决定一个曲线

   > \(Miller's Law\) Three points determine a curve.  
   > `个人理解：世间万物都有规律，数据亦有模式。*`

6. 如果用马克笔来做记录的话，每件事都是线性的。

   > \(Mar's Law\) Everything is linear if plotted log-log with a fat magic marker.  
   > `个人理解：把项目中心里程碑连起来的话，大概能得到一个曲线，甚至直线，但绝不是波浪线。`

7. 在设计的开始之初，最有资格领导一个队伍的人至少是有能力设计的人。

   > At the start of any design effort, the person who most wants to be team leader is least likely to be capable of it.  
   > `个人理解：不懂技术的人来管技术团队，大概率会变成一场灾难。`

8. 自然的说，最适合的往往是在中间某处。不要相信那些说最适合是在极端的断言。

   > In nature, the optimum is almost always in the middle somewhere. Distrust assertions that the optimum is at an extreme point.  
   > `个人理解：正态分布？？？*`

9. 没有你所需的所有信息绝不是作为不开始分析的一个令人信服的借口。

   > Not having all the information you need is never a satisfactory excuse for not starting the analysis.  
   > `个人理解：覆盖不够全面的分析总比没有分析来的强。`

10. 在怀疑的时候，去鉴定。在紧急的时候，去猜测。但要保证在确定之后能够回过头来处理问题。

    > When in doubt, estimate. In an emergency, guess. But be sure to go back and clean up the mess when the real numbers come along.  
    > `个人理解：大胆推理，小心论证。并且最重要的是能解决问题。`

11. 某些时候，通往终点最快的方法是抛开一切，立马开始。

    > Sometimes, the fastest way to get to the end is to throw everything out and start over.  
    > `个人理解：保证项目不会过时，比如一个双 11 活动，即使再设计得再好，过了双 11 没意义了。`

12. 正确的解决方式决不止一个。即使错误的方式有一堆。

    > There is never a single right solution. There are always multiple wrong ones, though.  
    > `个人理解：工程师思维必须开放，能够快速接受新事物。`

13. 设计基于需求。某个东西设计得比需求要求的“更好”，并不是一个正当的行为。

    > Design is based on requirements. There's no justification for designing something one bit "better" than the requirements dictate.  
    > `个人理解：自己为 PRD 上没有的功能而加班，大概连宵夜都没有。`

14. “更好”是“好”的敌人

    > \(Edison's Law\) "Better" is the enemy of "good".  
    > `个人理解：你设计的应用已经足够好的时候，没必要为了 5% 的提升，去花费原来 100% 的资源去做优化，不论如何，还是要给予需求。`

15. 提升设计的能力最初体现在接口。这也是最初可以把他搞砸的地方。

    > \(Shea's Law\) The ability to improve a design occurs primarily at the interfaces. This is also the prime location for screwing it up.  
    > `个人理解：提供简单，稳定，可用，可扩展的接口，大家都喜欢。反之。`

16. 前人所做的类似分析并没有直接得到年代所累积的智慧的恩惠。因此没有理由去觉得他们的分析比你的更可信。更没有理由把他们的分析当成你的。

    > The previous people who did a similar analysis did not have a direct pipeline to the wisdom of the ages. There is therefore no reason to believe their analysis over yours. There is especially no reason to present their analysis as yours.  
    > `个人理解：不要盲信。*`

17. 分析被公众于世这件事与它正确的可能性无关。

    > The fact that an analysis appears in print has no relationship to the likelihood of its being correct.  
    > `个人理解：不要盲信。*`

18. 过去的经验对于确认一个件事的真实是非常出色的。即使过多的真实会会毁掉其他有价值的设计。

    > Past experience is excellent for providing a reality check. Too much reality can doom an otherwise worthwhile design, though.  
    > `个人理解：不要过于依赖经验论。`

19. 众多的可能性会阻止你变得比世上任何人都聪明。如果你的分析说你的终端速度是光速的两倍，你可能发明了曲速引擎，但更可能的是你搞错了。

    > The odds are greatly against you being immensely smarter than everyone else in the field. If your analysis says your terminal velocity is twice the speed of light, you may have invented warp drive, but the chances are a lot better that you've screwed up.  
    > `个人理解：hmmmmmmm。*`

20. 一个坏的设计加上一个好的说明终究会完蛋。一个好的设计加上一个坏的说明会立马完蛋。

    > A bad design with a good presentation is doomed eventually. A good design with a bad presentation is doomed immediately.  
    > `个人理解：对工程师来说，表达能力同样重要。如果你不能在关键场合很好的表述你的成果，那么你的成果很可能会付诸东流。例如：年度考核，推销新系统`

21. 你在教室里听的东西有一半是胡扯。受教育就是能够分辨出那一半是哪一半。

    > \(Larrabee's Law\) Half of everything you hear in a classroom is crap. Education is figuring out which half is which.  
    > `个人理解：对于知识更新比较快的领域来说，很可能学校的教程会显得落伍，好的老师不单单会教你书本上的知识，也会告诉你哪些是有用的，哪些是没用的。（对于应试教育来说，感觉更是如此）`

22. 遇到疑问时，用文档记录下来。

    > When in doubt, document. \(Documentation requirements will reach a maximum shortly after the termination of a program.\)  
    > `个人理解：遇到问题就记下来，不要因为刻意忽略掉。因为你记录的问题，在未来得到答案后，不仅有利于你自身的成长，还有助于避免因隐藏的问题导致的严重后果。`

23. The schedule you develop will seem like a complete work of fiction up until the time your customer fires you for not meeting it.

    > 你开发的计划会像一个完整的小说工作直到你的顾客因为看不到它而把你炒了。  
    > `个人理解：项目的迭代都是可持续的，很少有一锤子买卖，迭代会在需求消失的时候断掉。`

24. 它被称为“工作 故障 架构”，因为“工作”会一直堆积直到“故障”发生，除非你对它强制使用一些“架构”。

    > It's called a "Work Breakdown Structure" because the Work remaining will grow until you have a Breakdown, unless you enforce some Structure on it.  
    > `个人理解：架构的重要性，虽然使用某些架构也并不是银弹。`

25. 追寻一个测试的失败，一直都有可能精炼分析来展示你一直有负面区间。

    > \(Bowden's Law\) Following a testing failure, it's always possible to refine the analysis to show that you really had negative margins all along.  
    > `个人理解：测试中出现的错误，肯定是有原因的，不要因为难以复现就忽略。工程师犯错可以被原谅，但隐藏错误就不可原谅。`

26. 不要做非正演讲这种傻事

    > \(Montemerlo's Law\) Don't do nuthin' dumb.  
    > `个人理解：学会大声说话，清楚自己的定位。工程师很容易给人一种 nerd 的感觉。`

27. 计划只会从一个方向移动。

    > \(Varsi's Law\) Schedules only move in one direction.  
    > `个人理解：项目排期都可以整成一个时间线，留有足够的空间，可以保证整个时间线不会因为特殊事件而打乱。（实际上排期一般不会考虑到突发状况，一旦出现，都是临时调整排期，或者直接 delay）`

28. 世上没有免费的发射井。

    > \(Ranger's Law\) There ain't no such thing as a free launch.  
    > `个人理解：跟“世上没有免费的午餐相似”（字面意思）`

29. 要得到一个对于最终项目需求的精确评估，需要把一开始的时间评估乘以PI，并且把十位数的小数点往右移一位。

    > \(von Tiesenhausen's Law of Program Management\) To get an accurate estimate of final program requirements, multiply the initial time estimates by pi, and slide the decimal point on the cost estimates one place to the right.  
    > `个人理解：低估开发所需工期，永远是项目 delay 的一大主要原因。迭代限制在一个可控的时间内是一个比较明智的选择。`

30. 如果你想要设计新的工程系统的最大的效果，学会去画图。工程师们总是顺利设计一辆跟最初画家概念相似的车。

    > \(von Tiesenhausen's Law of Engineering Design\) If you want to have a maximum effect on the design of a new engineering system, learn to draw. Engineers always wind up designing the vehicle to look like the initial artist's concept.  
    > `个人理解：好的技术文档，总是缺少不了图片说明。`

31. 你无法通过爬树去月球。

    > \(Mo's Law of Evolutionary Development\) You can't get to the moon by climbing successively taller trees.  
    > `个人理解：了解你所用技术的局限性是非常必要的。`

32. 硬件完美工作的时候，真正重要的访客一般都不在。

    > \(Atkin's Law of Demonstrations\) When the hardware is working perfectly, the really important visitors don't show up.  
    > `个人理解：总要做好最坏的打算，设计系统需要有一些兜底方案。`

33. 一个好的计划热火朝天的立马开工比一个下周的完美的计划更好。

    > \(Patton's Law of Program Planning\) A good plan violently executed now is better than a perfect plan next week.  
    > `个人理解：你的竟对不会等你去制定一个完美的计划。`

34. 根据你拥有的，在你所在的地方，尽你所能。

    > \(Roosevelt's Law of Task Planning\) Do what you can, where you are, with what you have.  
    > `个人理解：不要用目前不存在的技术去做设计。`

35. 一个设计师知道他做到完美的时候，不是没什么可以加上去的了，而是没什么可以被拿掉的了。

    > \(de Saint-Exupery's Law of Design\) A designer knows that he has achieved perfection not when there is nothing left to add, but when there is nothing left to take away.  
    > `个人理解：至繁归于至简（Simplicity is the ultimate sophistication）。`

36. 任何平凡的工程师可以设计出优美的东西。一个好的工程师设计系统来达到高效。一个更好的工程师设计系统来达到有效。

    > Any run-of-the-mill engineer can design something which is elegant. A good engineer designs systems to be efficient. A great engineer designs them to be effective.  
    > `个人理解：一个工程师最主要的就是解决关键问题。过度设计并不是一个好的现象。更好的工程师的设计出的有效解决问题的系统，而不是优美，高效率完成的系统。`

37. 在一件任务的成功关键是明确各自的责任。

    > \(Henshaw's Law\) One key to success in a mission is establishing clear lines of blame.  
    > `个人理解：明确并承担自己的责任是任何人在做任何事都应做的，没有人愿意和不负责任的人一起工作。`

38. 性能驱动需求，不论系统工程说明书上是怎么说的。

    > Capabilities drive requirements, regardless of what the systems engineering textbooks say.  
    > `个人理解：很多时候在定义项目需求的时候，都需要 RD 先进行技术调研，那是因为只有明确当前的技术能支持到什么地步，才可以真正确定能做到什么程度。具体问题，具体分析。`

39. 任何“刚好”包含一个火箭的探索项目，实际上，就是一个火箭项目。

    > Any exploration program which "just happens" to include a new launch vehicle is, de facto, a launch vehicle program。  
    > `个人理解：即使换了实现语言，一个 CRUD 服务就是一个 CRUD 服务。`

40. 保证一个新的人类太空项目预算足够并且按照计划有三个关键  
       1\) 没有新的火箭  
       2\) 没有新的火箭  
       3\) 不管你做什么，不要开发任何新的火箭

    > \(alternate formulation\) The three keys to keeping a new human space program affordable and on schedule:  
    > 1\) No new launch vehicles.   
    > 2\) No new launch vehicles.  
    > 3\) Whatever you do, don't develop any new launch vehicles.  
    > `个人理解：避免不停重复造轮子。`

41. 直到你让它工作起来之前，你都无法让它变得更好。

    > \(McBryan's Law\) You can't make it better until you make it work.  
    > `个人理解：先完成核心功能，再去寻求优化。`

42. 一直以来都没有足够的时间去做好，但某种程度上，一直都有把它做完的时间。

    > There's never enough time to do it right, but somehow, there's always enough time to do it over.  
    > `个人理解：某个项目在开始的时候，没有足够的时间去设计好，那么，在之后肯定会花不少时间去优化，重构。`

1. 太空是一个完全无情的环境。如果你在工程中搞砸了，某人会死

   > Space is a completely unforgiving environment. If you screw up the engineering, somebody dies \(and there's no partial credit because most of the analysis was right...\)  
   > `个人理解：对于平常的软件开发，或许不会出现这么严重的后果。但如果某次更新的代码 bug 导致用户流失，甚至造成 PR 事件，造成资损。那么后果同样很严重，千万不要轻视自己的工作成果。`

## Other

[Akin's LAWS](http://spacecraft.ssl.umd.edu/akins_laws.html?__s=ecoqrensc6fdgmbksadk)

<a href="http://www.ece.uvic.ca/~elec399/201409/Akin's%20Laws%20of%20Spacecraft%20Design.pdf" target="_blank" rel="noopener">Other Explanation</a>


