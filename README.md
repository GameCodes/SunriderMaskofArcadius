# SunriderMaskofArcadius
Sunrider Mask of Arcadius Chinese Patch / 太阳骑士汉化补丁

Translated by Pastolle at <http://steamcn.com/t183927-1-1>.

## Usage

Something like:

````bash
cd steamapps/common/Sunrider/
git clone https://github.com/GameCodes/SunriderMaskofArcadius.git
git checkout cn

wget -P game/Font https://github.com/googlei18n/noto-cjk/raw/master/NotoSansCJKsc-Regular.otf
````

## Description

Steam免费游戏《Sunrider: Mask of Arcadius》个人汉化最终版

STEAM游戏本体下载链接<http://store.steampowered.com/app/313730/>  
汉化补丁下载链接<http://pan.baidu.com/s/1jIPcRqu>  
不要问我里面的DecensorPatch是什么东西我不知道，我也不知道这东西的用法是把里面的内容复制到game文件夹下，更不知道这游戏有和҉谐剧情这玩意是用来解锁那部分剧情的


之后的剧情作为一个新游戏发布了，所以也是时候给这些前期剧情做个最终版了。本汉化基于游戏7.2版本，同样因为之后的剧情作为新游戏发布的缘故，本游戏本体大概不会再有更新了。  
之所以叫最终版不是说整个游戏都已经汉化完了，而是“这个版本里没汉化的地方今后也不准备汉化了”的意思。因为剩下的部分要么涉及到很麻烦的改图要么涉及到很艰深的改程序要么是我压根没找到文本在哪里，所以汉化就到此为止了。原则上所有剧情和大部分战斗指令应该都翻好了，机体升级之类的我实在没能搞定的地方就只能期待各位的英语基础了。

当然要是有人愿意帮我解决掉这些问题搞一个完美汉化出来我当然也很欢迎，另外如果有夸张的错误的话也会适当进行修正的（如果真的有人玩这个游戏还向我反馈出来的话）。  
游戏内置的存档导入功能似乎不可用，好像和系统设置的编码有关，反正我自己的电脑上也没搞成。所以想要继承存档的就别想了，专心了解剧情吧。

游戏介绍：  
这款游戏是欧美人做的日系风格GALGAME，战斗部分是机器人战斗风格的回合策略。玩家作为一名太空战舰的舰长，和来自全宇宙不同地方的妹子们卿卿我我，提升她们的好感度，之后……  
（发现好感度并没有什么卵用，女朋友被制作组钦定了）

咳咳女朋友部分不谈这是下一部分解放日  
http://steamcn.com/forum.php?mod=viewthread&tid=180846&fromuid=240181
（SteamCN蒸汽动力）或
http://bbs.nga.cn/read.php?tid=9191006
（NGACN）  
才涉及到的剧情。另外这个游戏并没有完成，而是采用做完一部分发布一部分的方式发布的，目前出到第三部分，所以钦定的女朋友并不是最终结局，之后也会有转折的。本部分是前两部分，是免费游戏，第三部分起则是收费游戏有兴趣的推荐打折后再入。


复制自补丁内文档的使用说明：

补丁使用方法：将game文件夹复制到游戏目录下，覆盖游戏本身内容。

Decensor Patch是反和҉谐补丁，请自行判断是否安装，安装方式也是将其中的game文件夹复制到游戏目录下覆盖游戏本身内容。反和҉谐补丁官网下载地址为 <http://forum.loveinspace.moe/thread/3/content-restoration-mod-instructions-steam>  
还原英文文件夹用于在需要的时候取消汉化，使用方法同上：将game文件夹复制到游戏目录下，覆盖游戏本身内容。

并非所有英文完全翻译，未翻译部分请善用英语基础  
如果遇到空白对话或者选项就是没翻译到的部分，如果遇到请告诉我  
游戏整体理论上已经可以运行，但是我只确保了汉化后的游戏可以在我的电脑上进入游戏，没有进行系统的测试，可能存在一些问题


因为汉化是出于为了更好传教的心情，所以欢迎转载。转载时原作者名写上Pastolle就可以

QQ反馈群334511947。申请入群请说明是游戏反馈

有任何反馈意见和建议欢迎通过论坛短信/留言/QQ等方式提出，最有效的联系方式是QQ。


翻译：Pastolle  
改图：Sunkice  
程序协力：呆呆蜗牛deparsoul nobody


感谢制作组愿意让我以爱好者的身份翻译这个游戏用来与大家分享

---

重要提示：汉化失败的一个可能原因  
因为我不懂程序，代码的写法不规范导致部分电脑上无法正确执行汉化语句。根据NGA论坛朋友的提示，出现汉化失败的朋友可以尝试一下这个办法

在游戏文件夹下找到“screens.rpy”，用记事本打开

把最前面init -99 python:下面的那行

`config.default_language = "Chinese"`
变成
`config.language = "Chinese"`
试试





万一有更新会更新在此处的占楼

以及汉化过程中的一些小故事

### 1. 耻辱

翻译的时候经常伴随着手滑或者眼花，所以回头看的时候发现一些让人哑口无言的低级失误也是家常便饭，这种时候最想做的事情前三名是：  
找块豆腐撞死  
找块果冻撞死  
找块酸奶撞死


比如说：  
ava "Two pirate ryders, inbound fast. Both infantry class. There's one more bomber-class ryder leading them, designation Havoc."  
ava "两架海盗的太空骑士快速接近中，都是步兵级。另外还有一架名称为“灾厄”的炮兵级宇宙骑士指挥他们。"

同一句话里的同一个单词ryder居然被写成了两种东西，这是何等的羞耻！不出意外的话这是“宇宙骑士”这个词第一次也是最后一次出现，因为最开始就决定把ryder这个词翻成“太空骑士”了……

顺便一提bomber-class被翻成了“炮兵级”，为了和前面的“步兵级”对应，用 “轰炸机级”总觉得和前面的“步兵级”完全不是一个世界了……而且作为兔国人，我们有“第二炮兵”这一优良传统，所以发射导弹的就叫炮兵级了（自我吐槽：为啥不叫二炮级）。


###2. 说都不会话了

尽管我自己是拿“意译为主，剧情自洽为第一优先”作为水平低下的安慰，翻译过程中还是经常出现“对着英语把意思顺下来，后来发现根本连不成中文”的情况。  
栗子就不举了，因为总感觉这种情况到处都是……（栗子：你才不举！）


###3. 阿萨嘉

首先我要先放上一段她的台词：  
asa "Hey, Ava! Whatcha doin' over here?"  
asa "嘿，艾瓦！整啥呢？"

所以这小妮子根本就不好好说话，台词各种没头没脑！这让我纠结了好久到底要怎么表现她的这种说话风格。最开始想拿个什么地方的方言，然而这让我意识到自己根本不懂任何方言，最后决定把她的第一人称改成“咱”来作为她的标签。

因为原来给她分配的“船长先生”这个专属称呼太长，第二版里把这个称呼变成了“老大”。


###4. Captain、Commander及其他

Captain是美国海军的O-6军阶，与陆军的上校相当。Commander是O-5，与中校相当。Admiral则是O-10，相当于陆军的四星上将。只是军阶倒并没有什么让人头疼的，但是这三个单词还代表着“船长”、“指挥官”以及“舰队司令”，导致翻译的时候我完全没法拿捏人物之间到底是在用职位互相称呼还是在用军衔互相称呼。

在初版翻译中所有的Captain都翻作了船长/舰长（具体叫船长还是舰长取决于我主观臆断的人物性格），而Commander写成了指挥官。第二版翻译在自我纠结以及与QQ群内小伙伴们讨论后决定：上级对下级采用军衔称呼，下级对上级用职位称呼。例如希尔兹叫艾瓦的Commander翻译作中校，而科莉斯卡叫艾瓦的Commander翻译作大副。格雷虽然是联盟的舰队司令，但是并不是太阳骑士号的直属指挥官，所以对他的称呼都是“上将”。

问我纠结这些有什么意义？当然是毫无意义……


###5. 皇帝？国王？

sol "The Emperor and the Crown Prince were killed in anassassination, leaving the throne to my father, the second prince."  
sol "It is a weapon of unimaginable power. Yet, it canonly be helmed by one of the King's daughters."  
所以到底是皇帝还是国王……

好吧，中央已经研究决定了，历史上崩溃的那个神圣鲁维亚帝国叫皇帝，现在这个鲁维亚叫国王。所以涉及到过去的鲁维亚的King都视作笔误，翻译里统一作皇帝。


###6. 日语！？

解放日推出了官方日语和日文配音，而这也导致了某种意外问题……  
ica "The Havoc's a morbidly obese, hideous lady, butsoldier boy's got a point."  
ica "こんなバカ重くて、優雅の概念が微塵も無い機体だが、 優等生の言う通りだ。"

我虽然不懂日语，但是汉字还是看得懂的，soldierboy哪里看起来像优等生了！当然，由于之前采用的“士兵小子”这个说法我自己和不太满意，所以这里综合了英文和日文，翻作了“模范兵”。  
日语翻译脱离原文的发挥在解放日里俯拾皆是，还好这个前作不存在这样的情况，像上文提到的改动主要是出于前后一致性的考虑。至于解放日里……那是另一个故事了……
