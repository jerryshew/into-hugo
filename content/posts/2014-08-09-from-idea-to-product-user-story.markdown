---
showDate: true
date: "2014-08-09"
layout: post
tags: ['collection', 'life', 'product']
title: "\u4EBA\u4EBA\u90FD\u8BE5\u5B66\u4E60\u7684\u6280\u672F\uFF1A\u4ECE Idea \u5230\
  \u6210\u54C1\uFF0C\u64B0\u5199 User Story \u7684\u80FD\u529B"
---

>作者：xdite 原文地址：<a href="//blog.xdite.net/posts/2014/05/29/from-idea-to-product-user-story" target="_blank">人人都该学习的技术：从Idea 到成品，撰写User Story 的能力</a>

眼尖的朋友看到，最近我开的两堂课：*Deliver Project on Time敏捷专案管理实务-六月班*与*Intermediate Rails - Rails实战就业班（六月)*, 都加入了User Story撰写的教学部分。纷纷偷问我为什么要加这个东西进去？

Rails Meetup 三年多来，在辅导培训过非常多Rails Developer 之后，我开始发现当今的网站开发教育中漏掉了很重要的一环，就是「规划Application 开发的技术」。

<!--more-->

线上教育什么技术都有教：基本的Ruby on Rails，基本的jQuery，基本的CSS。看起来好像你上了这些基础班，就可以开始写一个网站，找到一份工作。```但这却跟现实有一段相当大的差距。```我访问过很多征才厂商和初级开发者，开始了解到问题出在哪里。

具备网站简单的开发能力只是必备的基础，```雇主最看重且会决定录取```的能力，却是「把Idea变成实际Application的能力」。就是今天老板开一个需求，员工要能做出规划，并且在时间内执行完毕。

很多成长为Senior Developer 的前辈没有意识到这也是一门技术，所以面对「如何培养规划实做能力」的问题，因此往往会觉得，你多写习题就可以练成了，或找到一份工作被多操一下就会了。但这又回到鸡生蛋、蛋生鸡的问题，没有能力写出中小型Application，又怎么容易找到可以成长的工作。

## 打破鸡生蛋，蛋生鸡的循环：用户故事的木构建筑

我后来一直思考如何解决这个问题。才发现其实很久以前我已经解决了这个问题，只是我一直没有意识到..，就是：「透过撰写User Story 的训练，练习出如何设计架构的能力。」(这个技术四年来也一直在我部门/公司中施行训练）

### 什么是用户故事

User Story，是Scrum这个敏捷框架会用到的一个开发方法。具体解释可以看ihower曾经写个的这份整理，写的很棒。

传统开发流程是PM 花上很多的时间进行访谈写成规格，RD 再转成Application。不过往往这个转换过程中，却容易出现相当大的风险。

当中的问题出在于PM 的「规格」有很大的机会天马行空，即使不天马行空，也有可能不贴近使用情境，或者是根本脱离真实使用情境。RD 自然拿到规格和画面Workflow 进行「转换」时，万分痛苦。

当然，更多时候， RD 根本不知道要怎么「转换」。这就是为什么每个专案都花了很多时间进行了需求访谈，也可能写了详细的规格，专案却始终容易出包，都是在「转换过程」中出现了问题。

User Story 强调透过一份简单的情境规格，具体的描述出软体在「使用者」的手上，是怎么样被「操作」的。能够让RD 在开发时，能够尽可能地贴近真实被需要的Application。而不需要的功能，或者无法被实作的功能，将在一个一个循环之中，被舍弃。

初学的范本是：作为一个(某个角色) 使用者，我可以做(某个功能) 事情，如此可以有(某个商业价值) 的好处。

几个User Stories 的范例如下：

+ 使用者可以在网站上张贴履历
+ 使用者可以搜寻有哪些工作
+ 公司可以张贴新工作
+ 使用者可以限制谁可以看到他的履历

### 为什么User Story 可以帮助培养开发能力

透过把冰冷的规格转成具体的小情境，RD 可以更知道要怎么将架构切分成较小且可以单次就开发完毕的小元件。利用一个一个小的故事，开发出一个一个的小功能，再堆叠成一个完成的网站。同时透过User Story 的内容对比，RD 能够开始有办法排出轻重缓急，甚至估算出正确时程。

我发现很多入门的Rails开发者，在学完基础的Rails（比如说学完<a target="_balnk" href="//railsbridge-docs-zh-tw.herokuapp.com/docs/"><font><font class="">Intro to Rails</font></font></a> 、 <a target="_balnk" href="//railstutorial-china.org/"><font><font class="">Rails turtorial</font></font></a>。这些从CRUD run到deploy到Heroku的简单一日课程之后。就无法再进行下去了.. ..

根本原因是初学者不知道下一步如何进行自己点子的实作。

许多的书籍都有具体给定步骤与架构，因此在自行练习的时候没有问题，但在自己自由设计题目时，却不知道如何开展。或者是自己有了一点基础想法，拍了某​​些网站的screenshot & workflow。拿回家时却不知道怎么breakdown。

这就是为什么我在

+ <a  target="_balnk" href="//rocodev.kktix.cc/events/agile-project-managment">Deliver Project on Time 敏捷專案管理實務 - 六月班</a>

+ <a  target="_balnk" href="//rocodev.kktix.cc/events/intermediate-rails-2014-06">Intermediate Rails - Rails 實戰就業班（六月)</a>

都加入了用户故事的教学部分，因为细分应用，简单的项目管理就是新手进阶成职业的一大瓶颈门槛。

### 为什么非程式设计师也需要学习撰写User Story

在Deliver Project on Time 敏捷专案管理实务的五月班，有一位很有意思的报名者，他报名是因为长期参与NGO 的活动，但却觉得NGO 的专案规划以及执行专案能力不佳。因此想要透过上这个班，实际学习专案管理能力。

其实不只是NGO，通常非程式设计师出写出的规格通常都较脱离现实，是因为误以为了软体开发只要提供了「栏位」「画面」「流程」「仿照知名网站的Workflow），这样就是完成专案的规划。

事实不然，程式设计师往往希望你提供的是软体使用「需求」，以及软体「使用情境」，这样他们才容易设计出好的软体。很多规格书满满的screenshot，或者是标注模仿某知名网站Workflow。其实都不是程式设计师想要且需要的东西，他们希望你有办法简单叙述你要什么，你想要的流程是什么，你背后的生意逻辑是什么。（aka 你真的知道自己在干什么）

好方便「程式设计师」后续「规划」「软体架构」。

User Story 可以很容易的协助双方达成一致性的目标，因为User Story的书写语言并不是什么技术文字，而是一个又一个的情境。可以作为一个相当好，双方又容易接受的桥梁。同时透过撰写User Story，自己也可以越来越厘清这个网站真正需要的东西是什么，不需要真的实际写程式，不懂程式也可以设计出合理的网站架构。

这就是我建议为什么非程式设计师也需要学习撰写User Story 的原因。

### 学习资源

要学习撰写User Story 以及学习进行简单的小专案管理。你可以购买Scrum 系列的书，或者是以下几本我觉得不错的书：

+ <a  target="_balnk" href="//www.amazon.com/User-Stories-Applied-Software-Development/dp/0321205685/ref=pd_sim_b_6?ie=UTF8&amp;refRID=1DNNH8XATJPHK5XRKMFS">User Stories Applied: For Agile Software Development</a>

+ <a target="_balnk" href="//www.amazon.com/Extreme-Programming-Explained-Embrace-Edition/dp/0321278658">Extreme Programming Explained: Embrace Change</a>

+ <a target="_balnk" href="//www.amazon.com/Extreme-Programming-Installed-Ron-Jeffries/dp/0201708426/ref=sr_1_1?s=books&amp;ie=UTF8&amp;qid=1401342352&amp;sr=1-1&amp;keywords=extreme+programming+installed">Extreme Programming Installed</a>

当然，如果你想偷懒，最快的方式，还是报名我以下的这两个讲座/ Workshop。我有直接整理好的讲义以及结合Project Management 的实战技巧。

+ <a target="_balnk" href="//rocodev.kktix.cc/events/agile-project-managment">Deliver Project on Time 敏捷專案管理實務 - 六月班</a>

+ <a  target="_balnk" href="//rocodev.kktix.cc/events/intermediate-rails-2014-06">Intermediate Rails - Rails 實戰就業班（六月)</a>

希望以上这些学习资源能够帮助到你。

(如果你有相关的疑问，欢迎透过<a target="_balnk" href="//learn-rails.today/pages/contact"><font><font class="goog-text-highlight">这个表单</font></font></a>联络我）
