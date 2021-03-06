完全用 GNU/Linux 工作(1)
=======================

## 摈弃 Windows 低效率的工作方式，发掘 Linux 身上的 UNIX 气质

我已经半年没有使用 Windows 的方式工作了。Linux 高效的完成了我所有的工作。

GNU/Linux 不是每个人都想用的。如果你只需要处理一般的事务，打游戏，那么你不需要了解下面这些了。

我不是一个狂热的自由软件份子，虽然我很喜欢自由软件。这篇文章也不是用来推行自由软件运动的，虽然我觉得自由软件运动是非常好的。

这篇文章也不是用来比较 Linux 和 Windows 内核效率，文件系统，网络服务的。我现在是作为一个用户而不是一个开发者来说话的，我们的讨论是基于操作，应用层面的。是为了告诉大学里还不了解，或者不理解 UNIX 的科学工作者和大学生，UNIX 比 Windows 更适合用于科学研究工作，请大家理解 UNIX 的工作方式，不要用 Windows 的标准来要求 Linux，而要用一个科学工作者的标准来要求自己，用 UNIX 的思想来武装自己。

我显然是反对在大学，特别是理工科专业推广 Windows 的。我也反对在对“娃娃” 们的计算机启蒙教育中使用 Windows。因为 Windows 不论从技术上，经济上，思想风格上都是与我们培养高科技人才的目标格格不入的。Windows 的流行属于历史遗留问题，爷爷一级的人当然已经不可救药，但是我们不应该让下一代继续走上歧途。

## UNIX 不是计算机专家的专利
当我建议一些非计算机专业的人用 Linux 的时候，很多人说：“UNIX 是计算机系的人用的，我们不能理解。” “UNIX 是男孩用的，我们女孩不用。”

但是其实世界上的大多数科学家和工程师几乎用的都是 UNIX 作为他们的电脑工具。就因为它简单，可靠，稳定，强大，有趣。甚至很多时候 UNIX 就是唯一的选择。

你说：“我们都会用 UNIX 的话，你们计算机专业的人还用来干什么？” 很容幸的告诉你，计算机专业的有一部分人就是专门为你们提供这样强大而方便的计算机工具的。如果他们制造的工具只有自己会用的话，那这个工具还有什么用？

## 理解 GNU/Linux
不要用 Windows 的标准来要求 Linux。

由于GNU/Linux这个词太长，下面如果没有特别指明，“Linux”就是指“GNU/Linux”。

在这个年代，恐怕没有人需要我来介绍 Linux 是什么了吧？如果你觉得“Linux 只不过是跟 DOS 差不多的东西”，那请问问你旁边的 Linux 用户，Linux 到底是什么？

那为什么我还要写一篇这样的文章？因为，我发现还有很多人不不理解 Linux 和 UNIX，虽然他们也在用它，但是他们有时会问：“为什么 Linux 不能像 Windows 那样 ……？”，“怎么Redhat Linux不能 mount NTFS 分区！”，“Linux 下用什么整理硬盘？”，“什么时候OpenOffice才能完全兼容Word文件啊？”，“现在还有什么Windows能干的事情Linux干不了的？”……

他们有40G的硬盘，却只为 Linux 分配了2G空间，有时还抱怨“这个东西怎么占这么多硬盘！” 似乎 Windows 该占用大部分硬盘。他们把重要的数据装在Windows的分区，似乎信不过Linux。他们总是到处寻找新奇的，好看的GUI程序，对命令行的东西一概不屑一顾。他们对Drag&amp;Drop，菜单配置，自动升级非常感兴趣。他们如果找到一个很像 Windows 程序的 Linux 程序，一定会很高兴的说：“哈哈！Linux 也能……了！” 如果Linux在某种测试中胜过Windows，他们会高兴得跳起来。他们没有办法用Linux解决问题的时候，甚至用Wine来运行Windows程序。有时实在没办法，只好重起到 Windows，或者干脆省得麻烦，在 Windows 下装一个 VMWare 虚拟一个 Linux 玩。

你如果出现了上面的情况，说明你的思想受到了 Windows 的某种潜移默化的影响和误导。你没有能够从本质上理解存在于 Linux 身上的 UNIX 思想。你支持 Linux，你喜欢 Linux，你能从中感觉到快乐，这非常好。你现在只需要明白的是：Linux 从来就不是一个玩具，它是天才UNIX的后代。UNIX 是自晶体管发明以来最伟大的发明，它从诞生那一天开始就比 Windows 的设计出色。

你要体会什么叫做“设计”，一个糟糕的设计并不是到后来缝缝补补就可以变好的，而一个出色的设计，不但可以以不变应万变，而且可以影响到后来者。一个出色的设计配上一个出色的实现，那就是非常出色的发明。Linux 就是这样的一个出色的发明。Linux 并不需要追赶 Windows，也不需要打垮微软。它的最终目标是改变整个计算机世界，还人们自由，给人们乐趣和方便。

## Unix 是简单的，你不需要成为一个天才也能理解这种简单。

UNIX的设计者 Dennis Ritchie 说：“Unix is simple. It just takes a genius to understand its simplicity.” 但是我不这么认为，因为我不是一个天才，但是我却勇敢的把 Windows 完全删除掉，遇到不明白的事情的时候努力用 UNIX 的方式去解决，而不是寻求 Windows 的帮助。现在我体会到了 UNIX 的思想和好处，我可以用比 Windows 高效几倍的效率工作。因为我相信这样的信念：“Windows 能办到的事 Linux 一定能办到，而且办的更好。”

这小节开头的话应该改成：“Unix 是简单的，你不需要成为一个天才或是计算机专家。但是在这个冲斥着 Windows 错误观念的世界，你需要信念和勇气才能理解它的简单。” 我下面就告诉你一些我理解到的东西。首先，你要知道的是微软在国际科学领域是根本没有地位的。

## 微软的地位
微软的名声在欧洲和美国的大学里，特别是在计算机系里之坏，大家可能有所耳闻。我认识的 MIT，Stanford 的教授，贝尔实验室的专家，甚至一个欧洲小国的高中计算机老师都绝口不提微软的名字。在他们眼里，微软只是一个没有真技术，专靠在落后国家商业宣传和垄断经营的小公司。这个“小”并不是说它人少，钱少，而是说它先进技术少。

我上次和王益合作写了一个算法演示程序，那个算法是贝尔实验室一位科学家Steven Fortune很天才的发明，为了程序能够被身边大多数人使用，我们选择了 VC+MFC 作为平台。我在分析算法时还得到 Fortune 很热情的鼓励，寄给我一份资料，还多次回信耐心的给我讲解了很多细节。但是程序完成之后，我把样品发给 Fortune，他回信说：“对不起。我机器上没有 MFC。” 话说的很客气，但是我已经感觉到了他对 Windows 的不屑。然后我把 MFC 静态编译进程序再发给他，他就没有再回信了。他显然不是瞧不起我，而是确实有难处。

你能感觉到这位科学家对微软和 Windows 是什么态度了吧？不是反感，而是他心里根本没有 Windows 这个东西！微软在高科技领域没有发展，那么它怎么生存呢？到发展中国家去发展一下，他们的人民还对电脑一无所知，我说不定甚至可以打入大学的计算机系呢。我送他们软件，我捐钱盖大楼，我出钱找图灵奖获得者来演讲，让他们觉得我们都是科学家！

好了，现在全国的大学包括清华，几乎所有人机器必装盗版 Win2000，Office XP，学校的选课系统是非IE不能正确浏览，论文用 Word 编辑，演示用ppt做，email 的通知附件是 doc 文件，你不用 Word 打不开，连 863 项目都用 VC 写程序了。我很久以前就看到一份报纸说，“微软为什么不严厉打击盗版？” 这篇文章说，微软非但不打击中国的盗版行为，而且有放任之趋势。放长线吊大鱼，“以后我要你们加倍的来还我！” 确实如此，它的目的快实现了。

### Windows 笼罩下的中国计算机教育
说句丢脸的话，比尔盖茨很久以前是我的偶像…… //blush

在中国，比尔盖茨被很多人奉为神圣，“少年电脑天才”，甚至有的人提到他的名字就做出“抱拳对天”的姿势。很多人谈到微软的“新技术”，“高科技” 都是眉飞色舞。各种“VC编程圣经”，“深入了解 Visual C++”之类的书，在开头几页都会出现非常肉麻的字眼，“在那团团的混沌中，一个开天辟地的精灵，Windows 1.0，诞生了……”

微软的软件被这么多人盗用，那么人们是怎样使用这些盗版程序的呢？先看看电脑培训班，教的都是一些 DOS 命令，打字，Windows 基本操作，Word 文档处理，PowerPoint，高级班可能有 Excel，Access…… 参加各种微软认证考试，MCSE，MSDE 的人络绎不绝。考试辅导班都贴出了“280元，考过为止”之类的字样。考试参考资料更是昂贵，有些电脑书店整整两书架都是“Microsoft Press”的东西。我有个同学参加认证考试，每门考试都要200多元。而且你一次考不过可以再考，又要交钱。他后来还津津乐道跟我说，看我，花了XXXX(一个四位数)元考过了微软认证，得到一张比尔盖茨亲笔签名的证书和价值6000元的 Windows XP 内部发行版。

“电脑要从娃娃抓起”，我们再来看看娃娃们学的是什么。大部分家长给孩子买了电脑之后，他们首先就会装一个盗版的 Windows，然后买来盗版的游戏开始玩。如果哪个孩子会用 Delphi 编程序，那可不得了。报社记者，电视台争相报导，说，某某学校的初中生某某，在别人都还在玩电脑游戏这种“初级阶段”的时候就已经用 Delphi 写程序了。镜头还瞄准了他显示器上面的像框中的比尔盖茨头像！

我刚进入大学计算机系时还不懂得什么是操作系统，因为我以前只用过“中华学习机”。看到新入学的同学们各个谈论的都是 “Windows 95”，“VC”…… 我简直觉得我落后了好几十年一样，整个一土人，根本跟他们答不上话。好不容易找到一个比较熟的同学问了一下：“你们天天谈论的瘟95是什么啊？”答：“win95就是一个操作系统，跟DOS是一类。”“朵死是什么？” “你连DOS都不知道是什么？别在计算机系混了。” 学校上课当然不讲VC编程之类的东西，但是上 Pascal 的老师有一次就说：“嗨，我们学校真是落后。现在别人都用 C, C++，甚至 VC 了，我们还在讲 Pascal。不知道什么时候才能有VC课啊。你们出去也是要用VC的，只好自学了。” 于是，有些同学很多时候上课都捧着一本很重的“Windows 编程大全”之类的书，根本没有听课。吃饭时就念念有词的跟我说，“代码的优化是无止境的”，“匈牙利命名法真是伟大的发明” …… 这就是中国很多大学计算机系的情况。

感觉到无知了？这不是偶然的，而是微软长久以来埋下的伏笔。它要让无知的大家都把它奉为神圣，它要让支持UNIX，Xwindow的人一旦说 UNIX 好，Xwindow 好的时候，都被一群人围着说教：“这个 Windows 也能做到”，“你对 Windows 有偏见”，“微软才是主流啊”，“你敢瞧不起 win2k？”，“.NET 就是世界潮流”，“微软的毕竟是新技术”，“有钱就是有技术”…… 甚至在一番论战比较后败下来还是要说：“Windows 性能差点，但是易用性强”，“Windows 是老百姓用的，要求别那么高”，“微软那么有钱，以后想超过 UNIX 还不容易吗？”……

### 发达国家的计算机教育

我前段时间在 USENET 发文问有关 Scheme 语言的问题时，认识了一位丹麦人。他解决了我所有的问题，并且建议我阅读一些很“深奥”的有关程序语言语法，文法的书，他告诉我很多网站可以学习 LISP，Scheme，人工智能，算法。他叫我看 Jonathan Rees 的论文 &quot;Syntactic Closures&quot;。他还打包给我寄过来一份 MIT 的 &quot;How to Design Programs&quot;。他说他在自己的 PC 机上装的是 Linux，他用 Emacs 编辑，运行 Scheme 程序。他对 Emacs 的了解和爱好真是使人惊讶。他大学本科毕业时做的毕业设计是一个 Scheme 解释器。这对于我来说是望尘末及了。

他是那么的不厌其烦，我的每一个问题他都详细的回答。我有时都觉得过于详细了，怎么这么耐心啊？我觉得他似乎是我的高中老师。他是什么样的人呢？我好奇的打听了他的情况。原来，他是丹麦一所普通高中的计算机老师。

他说他在高中里讲授程序设计和算法，计算机语言文法。他说用 Scheme，他的学生不用再为内存泄漏等程序语言本身的问题而烦恼，而专注于问题和算法本身。有利于培养学生解决问题的能力，特别是用计算机解决数学问题的能力。

天哪！为什么欧洲出现那么多数学家，几何学家？你看看别人重视的是什么！我们的计算机教育如果继续这样下去，只会沿着弯路越走越远！

### 微软和它的朋友们的如意算盘

下面来看看微软的收入是怎么来的。首先，Windows 98系列操作系统，一个就是 100 多美元，每次升级又是几乎同样的价钱。Windows NT 还要贵几倍，而且有用户数目限制，5个用户的，10个用户的…… 以后如果要增加用户数目还要按比例付钱。

花了如此多钱买来的操作系统就能用了吗？它竟然连压缩程序都没有提供！你装上 Windows 之后一般第一件事就是去下载一个 WinZip 吧，“只要 29 美元”。Windows 会中病毒啊，马上花 70 美元买一个 Norton AntiVirus 吧。还有黑客呢？再买一个 Norton Internet Security 好了，100 美元。系统需要优化，磁盘需要整理，买一个 Norton System Works 是你最佳的解决方案，100美元。

可是你现在还是不能干正事啊！你想要一个 Word, PowerPoint？那就买一套 Office XP 吧，一起买便宜些，$459.90。

那些程序不会用啊！那些菜单怎么设置，到底有什么功能啊？看“帮助”也学不会。买本书看看吧，我推荐“Special Edition Using Microsoft Office XP”，不贵，$27.99。这本书里面大部分是屏幕抓图，还是买一本旧的比较划算，$17.85。

你如果只是当个秘书，上面的差不多还凑合了。可是你有更高的追求，你想成为 Windows 程序员。首先买一个 Visual Studio.NET 吧，要不然怎么编译程序。$494.95。

为了紧跟微软动向，世界潮流，不能不注册个 MSDN 什么的吧？这个贵一点，不过物有所值啊，$2,799。

嗯，你现在已经是上层阶级，白领人士了。你现在可以像这样“自由”的，“安全”的生活了：

