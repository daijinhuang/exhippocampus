---
layout: page
title: 我的游戏人生
categories:
    - misc
header:
    image_fullwidth: the_great_hall_view.jpg
    caption: Alice Madness Returns Screenshot (The Great Hall)
    caption_url: http://www.ea.com/alice/images/greathall
---

我是在香港土生土长、现于上海工作的游戏程序员。有曰人生如戏，当代若说人生如游戏或更有共鸣。然而，我们是这游戏的玩家而不是设计师，世事往往并非各遂其愿，却又带来无尽惊喜。游戏中与其以赚取货币提升等级为目标，不如享受过程，尽兴而归。适逢其会，有缘和大家分享我的成长点滴。


## 童年玩意

我生于1977年英国殖民时代的香港。家境并不富裕，童年羡慕其他小朋友拥有许多玩具，曾经想过将来要做玩具设计师，现在做游戏编程，也许也不差太远。当年缺乏玩具，就找到些不花钱的玩意儿，例如折纸。从小父母每周带我去借阅图书，包括折纸书籍。回想起来，我怀疑幼年的我是从折纸中学到如何阅读说明去自我学习的，并且尝试做事情以完美为目标。那时候我的技术还不错，例如可以用一张正方形纸，不用粘贴折九只头尾相连的鹤。当然，单单按照说明来执行并不太有趣，后来便学会设计纸模型。首先是做些长方体、锥体之类，记得有一次按书用纸做足球形的截角20面体，被同学取笑说足球应该是圆的。设计了一些规则的几何体之后，就可以设计一些不规则形状的，例如一辆跑车。由于要在纸上画设计图，也学会了一些作图法，后来也学习了建筑设计的透视技法。大约从小学三年级开始，父母让我参加了校内开办的电脑兴趣班。课程之初，是通过教育软件去学一些电脑知识（用BBC Micro），之后再慢慢加入一点BASIC编程内容。不过我最喜欢的，都是课堂结束前的电脑游戏时间。

小学四年级，我当上了学校图书馆的管理员。有一天馆里送来一台Apple IIe，听说是一家公司换IBM PC而留给学校的。那台没软盘没录音机的Apple IIe，只能用来编写BASIC程序，不能玩游戏。当时心里传来一道声音——

> “想玩游戏？自己写啊！”

我借来一堆Apple IIe书籍，阅读、上机编程，把午休和放学后的时间都用上了。课上和晚上，还会把程序写在纸上，在脑海中运行程序。那时候写的程序，主要围绕游戏和图形。记得曾经在Apple上重写BBC Micro上玩的“撞砖”游戏，从中学到了一点游戏模拟技巧，后来还学习了一点6502汇编。在学习的过程中，我意识到编程的世界是虚拟的、完美的，不像机械或电子等物理系统有许多限制，几乎凡是想得到的事情都能用编程实现，并且能完全自动化地执行。这让我感到，编程本身，比使用软件的乐趣要大得多。

## 初试啼声

从小学升上中学，1990年的暑假我终于获得人生第一台电脑——一台二手的286。那个暑假我躲在家中，使用GW-BASIC继续编程。286可以存档，意味着可以写更大型的程序。规模越大，更让我认识到BASIC语言在编程上的局限。尽管如此，当时仍然很快乐地编写了不同类型的程序：图形、音乐、游戏。通过阅读书籍，我还学会了画不同的二维图形，包括曲线、分形（fractal）、简单的三维渲染等。

在升中二的那年暑假，我就开始转为学习C语言。DOS对许多设备都没有直接支持，不同的设备甚至连标准的接口都没有。所以那时编程，还必须学一些x86汇编知识，以及使用不同设备的底层技术。

中二时得知有一个“微电脑教育（MIE）”比赛，这是我个人电脑比赛生涯的开始。我用Turbo C写了一个名为《3D Solid Maker and Viewer（三维实体制作及检示工具）》的软件，其实只是个非常原始的三维建模软件，可以设置简单的摄像机动画。当时花了许多时间去编写GUI系统，就是要由绘画控件、处理滑鼠键盘事件等做起。基于知识经验所限，系统架构很糟糕，并有大量硬编码。初试啼声，这个作品最后获得全场总亚军，大大增强了我对编程的信心。

## 进入业界

1992年前后，我在BBS上结识了一群有意开发游戏的朋友，成立了香港首家游戏工作室M&P System。最初我并没有直接参与开发，只是向朋友们学习更多游戏开发的知识，写过一些引擎和工具的原型，有时帮忙做点小事情。例如在公司首个作品《疯狂双响炮》（1993年）中，我设计了一个游戏关卡和做游戏测试。之后公司开发RPG《勇者传奇》（1994年）时，我在开发另一个RPG，做了地图编辑器和引擎，可操控主角行走，也有初步的战斗模式。

后来公司改组为阿博克。我在新项目里首次担负重任，那时我在读中四理科班。这个新项目《王子传奇》是我发出的提案，一个奇幻背景的策略角色扮演游戏（SRPG），采用等角（isometric）的无缝（seamless）游戏世界。我主要负责游戏策划、编剧、游戏性编程（gameplay programming）。项目的野心很大，或是太大。整个项目约由6位成员，历时18个月完成。

当时DOS运行于真实模式，能直接使用的内存只有640KB，完全不足以做无缝的地图渲染。最后，我们做了个大胆的决定，用汇编开发32位保护模式的引擎，用Turbo C++开发16位真实模式的游戏性部分。引擎部分由我那牛人拍档开发，而我主要编写游戏性部分。那个引擎，基本上就是要先从头写一个32位保护模式的操作系统，管理内存、磁盘读写、设备驱动等，再开发地图渲染引擎。游戏的“脚本”使用C语言来编写（包括用宏来做数据驱动），利用覆盖（overlay）机制的按需载入。

在那漫长的制作期，星期一至星期五，放学后经常会返回办公室，有时候晚上11点才回家。周末和假期，也会经常到公司干活。后来一些伙伴在项目结束前就离开公司，最后在不太欢乐的气氛下完成了这个作品，游戏内容有点虎头蛇尾。听说这作品在台湾卖得还不错，可是由于一些问题，我最终除了暑假获得的一点津贴外就没有其他经济上的收益，当然，开发经验除外。自此我离开了游戏业界，继续求学之路。

## 比赛生涯

自中二参加第一次电脑比赛之后，我又陆续参加了多次这类比赛。中三开发了一个教学软件，采用图形冒险游戏的形式去做几个化学实验。中四开发《王子传奇》时，同期开始学习C++，中五参加电脑辅助学习（CAL）比赛时，就试验用C++开发了一个地理科辅助教学软件《Landscapist（地形设计家）》，它其实是一个三维地形编辑及可视化工具，希望借此学习不同的地形，以及认识读取相应等高线图的方法。为了这个软件又开发了第二个GUI系统，这个系统采纳了面向对象设计思想。赛前自信满溢，可惜大热倒灶，只获小组季军。那个反差使我很失落，但后来也学会，单靠技术能力，不能做出大众喜爱的软件。而且也觉得名次对我越来越不重要，开发过程的乐趣和收获才是最重要的。

升上中六后，虽然我仍以个人名义参赛，但为了师弟师妹们也能参加比赛，就用Turbo Pascal开发了一个简单的二维游戏引擎，配合图像转换工具可以较容易做出作品来。为这个系统设计了易用的API，并多做了些测试以避免应用时出现问题，这些都为我积累了很好的经验。而我在这届比赛中，开发了《Logicmate（逻辑伙伴）》，这个软件是一个数字电路的设计工具和模拟器。配合高考电脑科的内容，这个软件可以用逻辑门设计数字电路。另外也有一个模式，是老师可以定义输入输出讯号，储存为习题，学生按要求去设计电路，并自动评分。周而复始，我又写了第三个GUI系统。该作品获得科学组亚军、全场总亚军和最佳教育奖。而师弟师妹们用了我的引擎拿了小组冠军和很多奖项，那又是另一种喜悦。

中七，最后一次参加CAL，我和一个同学组队参赛，用两个月的业余时间开发了两个组别的软件。在科学组制作了《Cyber Optics（奇妙的光学）》。当时Windows 95成为主流，我首次采用Visual Basic 开发这个软件。最初的感觉就是语言倒退，一大堆C++的特性都没有了。但后来也适应了，并觉得程序员不应该受语言所限，脑里能想到的，这些通用语言都能实现。另一个是语言组作品《Angel’s Adventure in English Land（小天使英语历险记）》，是一个马利奥式的横向平台动作寓教于乐（edutainment）软件。基本上是把英文词汇拼写问题加进游戏关卡里，除了跑、跳、踏、射，每关还有Boss战。这是过往软件中最好玩的一个，经过实际测试，目标对象（小学生们）也很喜欢。

## 大学之道

一直以为，我会顺利入读计算机系。因为一个意外，我未能如愿，当打算要重考，却又竟然进了香港大学的认知科学（Cognitive Science）。我当时百感交集，觉得人生走上了未知之路。那是1997年的夏天，香港回归祖国。

认知科学是一门以科学方法去研究人类心灵（Human Mind）的跨领域学科。出生以来从没想过自己会去心理学系、哲学系、语言学系、神经科学系上课，而这学科又同时含计算机系的课。回头想来，认知科学也许更适合我，开阔了我的视野，而不是把我变成一个电脑极客。再者，这学科容许文、理、商科的同学报考，能和不同背景的同学一起学习，互补长短，而那一届男女比例也刚好是1比1，不禁同情选了读工科的旧同学们。

港大校训是“明德格物（Sapientia et Virtus）”，在迎生营中却学到了另一传统口号“Working hard and playing hard in HKU”。前者出自《礼记·大学篇》，可理解为修养自己的道德，探求外在世界的物理；后者是港大学生的生活态度，努力工作学习，游戏同样尽力。

港大课程都用英语教学，起初还怕会成障碍，但很快就适应过来了。教学方式比较互动，教授也乐见学生指出黑板上的错误。虽然编程课无甚惊喜，两门算法课却都很具启发性，也系统地弥补了我这方面知识的不足。此外，还有一门人工智能课，作业内容是做黑白棋（reversi），或有额外加分的象棋。为了挑战，我选择了后者，也试用刚学不久的OpenGL做三维图形用户界面，历时两个月完成《美绿中国象棋》。

科学之上，还有哲学。学习哲学中的逻辑学是理性思考的基础，而哲学亦讲究如何清晰表达抽象思维。因为学科关系，课堂主要讲述心灵哲学此分支，例如二元论、物理主义、功能主义等，和人工智能有关的有图灵测试、中文房间论证、玛丽房间论证等。然而，对我人生观影响更深的，是接触有关宗教、自由意志和道德方面的哲学命题。虽然学习哲学并不能像学习算术，能找到问题的“正确解答”，但是哲学提供了一些问题的可能答案，或是揭开事物的表象，尝试分析其本质。我相信，能认清自己的卑微无知，及尽量避免盲目相信别人的答案，是哲学带给我一生的收获。

本科最后一年，我选择了计算机系的教授作为毕业论文导师。题目是基于内容的图像检索（CBIR），主要使用了名为自组织地图（SOM）的人工神经网络算法，进行自动图像分类。题目也许不太重要。重要的是，我从中学到了科学研究的方法，诸如搜索和阅读论文等训练，并且能以尽量客观的方式书写学术或业务上的文章。现在每逢遇到技术问题，都能应用那时学习到的技巧，先找相关书籍和论文，分析后再思考采用哪些方案，甚至尝试一些新的点子。每年也留意工作相关的学术会议，筛选一些论文细阅，从而掌握最新技术趋势。

本科毕业时，我的导师去了香港中文大学系统工程及工程管理系任教，他邀请我到该系念硕士研究生。而得到奖学金的学生，每个学期都要担任一门课的助教。我比较特殊的经历是担任计算机架构课的助教。因为我本科不是计算机系或工程院的，没有正式上过这门课，唯有在学生上课时又一起上课，回去读教科书写导修课教程。教学也是有趣的人生经历，当尝试以最简单最好的方式向学生讲解时，自己同时也对题目有更深的了解，或许也算是教学相长之体验。作为学生，上研究院的课也和本科有莫大差别。以一个中级数据库课程为例，教授在第一课讲解了一些研究题目，同学们在那些题目中抽签取得一篇论文，之后每课就是由同学轮流讲解抽到的论文，其实就是互相教学、互相学习。

硕士的研究题目其实是深化本科论文题目，配合使用者的实验数据，找出不同算法的实际应用效能。最后成功通过答辩，也获得了博士入学资格。然而，经过两年的研究，虽然我对从事研究感兴趣，但对这方面的研究并不是特别热衷。那时，反复询问自己，最想做的是什么，最适合做的是什么。我决定，最终要回归游戏，而在进入游戏产业之前，希望在这一学习阶段做游戏方面的研究。

## 回归游戏

硕士毕业后，我加入了香港理工大学的多媒体创新中心，先做项目研究员，再思考申请博士生的研究提案。最初我参与增强现实（Augmented Reality）游戏项目。首个游戏中，玩家手里拿着一块纸板，但看到的却是一个虚拟的木制迷宫，用双手把纸板倾侧，便可把虚拟的金属珠滚到终点，当中要小心控制力道避开洞穴。另一个是跳舞游戏，能在现场环境中看见虚拟的舞伴，并要按箭头移动身体。

![增强现实游戏用于控制真实物件，并混合现实和虚拟画面](/images/ar_maze.jpg)

至于兼读攻博方面，我的研究方向是游戏世界内容的自动生成。最初做对自然环境方面的研究，利用雨水侵蚀等模型去生成地形、河流等。刚刚中文大学举办一个游戏开发的比赛，便建议联合正在中心念三维美术的同学一起创作一个作品。想法是利用之前的研究，加上自动道路生成，去制作一个全地形车（ATV）赛车游戏，游戏中的环境、赛道每次都能自动产生。最后我们十多个组员一起完成的作品《Infiniti Rally（无限赛车）》顺利夺冠。可惜，攻博中期和导师出现了严重的分歧，便暂停了历时两年的兼读博士生生涯。

接着主要是开发一个三维在线游戏平台的大型项目，供香港业界、学界使用，后来要参与较多的业务和管理。因为洽谈项目和合作，多次到英国和中国台京沪杭穗等地，见识各地业界状况。直到而立之年，有感缺乏大型游戏制作经验，便毅然离家，漂泊上海，重新投身于游戏业界。有幸能于育碧完成四平台的《美食从天降》，之后到了现在任职的麻辣马，开发我喜爱的游戏的续作《Alice: Madness Returns》。

2010年初，因读了一本有点失望的书，并在豆瓣网站写了一篇书评，认识了许多IT、出版业界朋友，也促使我建立博客、翻译游戏开发书籍以回馈社会。我的路并非一帆风顺，但是遇到出人意表之事，是好是坏，也只由自己心态去决定，随遇而安。制定或接受挑战，因为有难度的游戏才好玩。凡事独立思考，尽心尽力而为。祝你也能享受这个名为人生的游戏。

（本文原于《程序员》杂志10年10期揭载。）
