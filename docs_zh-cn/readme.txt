        M.U.G.E.N

  Version 1.1 Beta 1
  27 Jul 2013

  (c) 1999-2013 Elecbyte


About
-----

M.U.G.E.N是一款2D格斗游戏引擎，
拥有许多可定制的组件。

这是一个公开的测试版本。测试版包含了一些正在开发的功能，
并且比稳定版有更多的错误。

请访问我们的论坛elecbyte.com以获得支持，
错误报告和其他有用的资源。

这个发行版包含了一个样本角色 "功夫侠"。
你可以在他的目录下的readme文件中查看他的活动列表。
  chars/kfm/




Updates
-------

See history.html for updates.



Contents
--------

I.      M.U.G.E.N信息 M.U.G.E.N Info
II.     按键配置 Key Configuration
III.    运行游戏 Running the Game
IV.     游戏热键 Game HotKeys
V.      速度问题 Speed Issues
VI.     内存问题 Memory Issues
VII.    已知的问题 / 注意事项 Known Issues / Notes
VIII.   示例内容 Sample Content
A.      许可协议 License Agreement
B.      鸣谢 Acknowledgements


=====================================================================
I. M.U.G.E.N信息（M.U.G.E.N Info）
=====================================================================

M.U.G.E.N可免费用于非商业目的。
对于其他用途，请联系我们。
请参阅附录A的完整许可文本。

系统要求
-------------------

操作系统：需要Microsoft Windows XP SP2或更新版本。

CPU：建议使用 Intel Core 双核处理器或同等配置，以满足高清分辨率的要求。

内存：512 MB或更多
（实际要求可能会根据角色和舞台的复杂性而有所不同）。


What M.U.G.E.N?
---------------

M.U.G.E.N 是一款2D格斗游戏引擎，最初发布于1999年。
M.U.G.E.N 的设计初衷是让用户制作出符合
90年代中期2D格斗游戏技术水平的游戏。
然而，它很快就发展成为高度可定制化的引擎，
可以对每个角色的行为进行非常精细的控制。
事实上，有一些为M.U.G.E.N定制的游戏，
其行为并不像典型的2D格斗游戏。

大多数为M.U.G.E.N创建的内容往往是以
单个角色、阶段或主题（motifs）的形式发布的
（主题（motifs）就像主题（themes）一样，
可以控制游戏的外观和感觉）。组装游戏很简单，
只要下载你选择的内容，然后配置M.U.G.E.N来了解它。

M.U.G.E.N是专为没有什么编程经验，
但有一定艺术天赋和耐心学习的人设计的。
当然，有一定的编程背景确实会让你有一点头绪。
不过，如果你只是想玩玩下载的内容，
你只需要知道如何解压文件和
编辑文本文件即可。

M.U.G.E.N也是某个东西的首字母缩写词，但我们忘了
它是什么。:)

以下是你在 M.U.G.E.N 中可以找到的功能示例。
- 自定义标题画面，角色选择画面，生命和能量
  条，游戏音效，字体等等。
- 角色可以有任意数量的声音和精灵（sprites），
  大小受电脑内存限制。
- 可选择多种分辨率，从320x240到
  1920x1080的全高清。
- 过场动画（Cutscenes）。

游戏引擎
- 每个角色最多使用7个按钮。
- 常规动作、特殊动作、超级动作等。
- 发射（Projectiles）和特效。
- 移动终止和连击，多段式移动和投掷。
- 你的角色能做什么是由脚本语言（和
  你的想象力）定义的。


How M.U.G.E.N?
--------------

M.U.G.E.N 最初是使用 DJGPP 和 Allegro 这
两个优秀的编译器和游戏库为 DOS 开发的。
如今，M.U.G.E.N 是使用 Visual Studio Express 和 SDL
为 Microsoft Windows 开发的。


Where M.U.G.E.N?
----------------

http://elecbyte.com/mugen


Why M.U.G.E.N?
--------------

说实话，我们当时是在做一款射击游戏，
突然间就变成了这个样子。虽然一开始
我们是在做一款射击游戏，但是我们注意
到当时PC上并没有什么好的商业格斗游戏。
而一些灵感来自于早期的引擎，比如SFIBM。


Who M.U.G.E.N?
--------------

如果您想联系我们，请在我们的网站上
填写联系方式。
http://elecbyte.com/


When M.U.G.E.N?
---------------

我不太记得我们是什么时候开始这个项目的，但
大约是在1997年或1998年。我们的第一个公开发布版本是
9X.06.27。



=====================================================================
II. 按键配置（Key Configuration）
=====================================================================

这是默认的按键配置。当你运行游戏时，你可以从
选项菜单改变它。

Button      Player 1      Player 2
------      --------      --------
  Up        Up arrow      W
 Down       Down arrow    S
 Left       Left arrow    A
Right       Right arrow   D
  X         L             R
  Y         semicolon     T
  Z         double-quote  Y
  A         comma         F
  B         period        G
  C         slash         H
Start       Enter         U

如果你有一个操纵杆（joystick），你可以通过选项界面启用它。
按F1进入输入配置，并从那里设置你的操纵杆。
按操纵杆类型选项上的 左/右 键来启用或禁用
每个玩家的操纵杆（joystick）。



=====================================================================
III. 运行游戏（Running the Game）
=====================================================================

在“资源管理器”中，双击 mugen.exe 开始。

Main menu        Function
---------        --------
Arcade           一对一对抗电脑
Versus           一对一对抗你的朋友
Team Arcade      多种团队合作模式与电脑对抗
Team Versus      多种团队合作模式，与你的朋友对抗
Team Co-op       与你的朋友一起对抗电脑
Survival         看你能在无尽的战斗中坚持多久！
Survival Co-op   与你的朋友作为伙伴玩生存模式
Training         尝试动作和连击
Watch            观看 AI 控制的角色战斗
Options          设置基本游戏选项
Exit             退出 M.U.G.E.N

对于 "Arcade" 模式，你按的键
将决定你在哪一边玩。如果你选择了玩家1
的一个按键，你的角色将在左边开始。
如果您用玩家2的键选择，您将从右侧开始。

对于 "team" 模式，您首先选择您想在哪个团队模式中
开始游玩。按向 上/下 选择模式。某些模式，例如 Turns
mode ，允许您通过按 左/右 来设置团队中的玩家数量。
按一个键选择选项。在 "Team Arcade" 中，
选择玩家后，您可以选择对手的团队模式。
这些是不同类型的团队模式：
  Single - 只有你一个人。你的角色有两个回合。
  Simul  - 你和你的伙伴同时进行。你的团队有两个回合。
  Turns  - 你和最多3个伙伴。当一个角色被KO时，
           下一个角色会加入进来。每个角色有一个回合。
角色的起始生命会根据每方
玩家的数量进行调整。

Team Co-op 模式略有不同。唯一允许的团队模式
是Simul，它是自动选择的。玩家一首先要
选择自己的角色，然后由玩家二选择伙伴
角色。当玩家二选择完毕后，玩家一选择对方的
团队模式。

在 Survival mode 中，有无穷无尽的对手。
目标是击败尽可能多的对手。当你的队伍被KO时，
游戏就结束了。你可以选择单人或组队玩。
单人模式给你最高的生命点和治疗（当你赢得
一个回合）。你的队伍中的玩家越多，每个玩家
能受到的伤害就越少，每回合结束后你得到的
每次治疗量也越少。

在 "Watch" 模式中，首先选择团队模式和角色
站在玩家一的一方，然后对玩家二进行同样的操作。


Turns mode 下的开关顺序
-----------------------------

当你在玩 Turns team 模式时，你可以在其中一种情况下
改变你的团队顺序：

1. 在比赛开始前加载
2. 在你输掉一局后，在下一局加载前

按住方向键可以实现顺序的切换。
向前按住可使队伍顺序向前旋转一名成员。
向后按住可使你的队伍顺序向后旋转一名成员。
如果您有4名可用成员，您可以通过按住向上
旋转2名成员。注意，你只能和还没有被KO的
成员一起转换。

下面用一张图来说明一下工作方式。

	         starting team
            1 2 3 4  |  1 2 3  |  1 2
           ----------+---------+------
 hold fwd:  2 3 4 1  |  2 3 1  |  2 1
 hold back: 4 1 2 3  |  3 1 2  |  2 1
 hold up:   3 4 1 2  |  ^      |  ^
            ^           |         |
            |           |         |
     这是要进来的人物（this is the character that will come in）


命令行参数（Command-line arguments）
----------------------

M.U.G.E.N 接受 Quick-VS 模式的可选命令行参数。

其格式为（可选参数用方括号括起来）：

  ./mugen [player1 player2 [-s stage]]

例如，要在名为 KFM 和 Suave 的玩家之间开始快速对战，
你可以输入：

  ./mugen kfm suave

要在一个名为 TEMPLE 的舞台（stage）上扮演相同的两个角色，请输入：

  ./mugen kfm suave -s temple

你可以为你的角色指定代替的 .def 文件：

  ./mugen kfm/newkfm.def suave -s temple

以下是其他用处的命令行选项：

 -h            显示帮助
 -r <sysfile>  加载一个主题（motif）（更多信息见下文）
 -p3 <pname>   将名为 pname 的角色加载给 player3
 -p4 <pname>   将名为 pname 的角色加载给 player4
 -s <sname>    在 stages/ 中加载一个名为 sname.def 的舞台（stage）

要获得命令行选项的完整列表，请键入：

  ./mugen -h


使用主题（Using motifs）
------------

主题（motifs）是对游戏界面中使用的图形和
声音，以及角色名册等其他东西的自定义配置。
基础图主题（motif）在 data/ 目录下。
自定义主题（motifs）作为子目录放在
data/ 下。例如，"kfm" 主题被放置在
data/kfm/ 中，要使用它，你可以输入：

  ./mugen -r kfm

下面是 motif 包含的内容（以及每个文件所在的文件）：
- 人物名册和舞台列表 (select.def)
- 标题界面图像，声音和音乐 (system.def)
- 角色界面图像，声音和音乐 (system.def)
- 与图像界面对应的音乐 (system.def)
- 胜利界面图像，声音和音乐 (system.def)
- 设置界面图像, 声音和音乐 (system.def)
- 文件名和剧本 (图标logo, 简介intro, credits, etc) (system.def)
- 实际的剧本文件
- 战斗演示选项 (system.def)
- 进行 / 游戏结束选项 (system.def)
- 战斗界面图像和声音 (fight.def)
  战斗画面包括生命和能量条，“回合X”
  图像和声音，常见的击中火花和音效等。

要设置默认的 motif ，请使用文本编辑器编辑 data/mugen.cfg ，
并在 [Options] 下更改 "motif"。

要安装下载的主题（motif），首先将文件解压到一个
新的目录中。打开那个目录，看看里面是否有文件；
如果有，就把那个目录移到 M.U.G.E.N 的 data/
目录中。如果有一个单独的目录，则将该底层目录
移到 data/ 目录中。

要制作你自己的主题（motif），在 data/ 下创建
一个子目录，用你的 motif 的名字命名，然后把
system.def 复制到新目录中。如果你想编辑除了
system.def 以外的其他文件，请把它们复制到你的
motif 目录下，并在那里修改它们。任何不存在
于 motif 目录下的数据文件都会默认为 data/
目录下的文件，所以如果你没有复制 select.def ，
那么当你运行时选择 motif 时，
就会使用 data/select.def 。

包含样品主题：
mugen1 - 为1280x720分辨率设计的 motif。
         这是默认的 motif。
big    - 让你有很多空间来放置角色。
kfm    - “功夫男”的 motif。


训练菜单（Training Menu）
-------------

训练模式下有一个训练菜单。您可以用方向键选择菜单
项目，并按任意攻击键或暂停键退出暂停模式。
以下是可用的选项：

虚拟对象（Dummy）控制：合作（Cooperative）， AI， 或手动（Manual）
 在合作模式下，虚拟对象（dummy）将执行您在
 训练菜单中其他地方指定的动作。在AI模式下，
 虚拟对象（dummy）将像普通电脑对手一样行动。
 在手动模式下，可以用对手的按键控制虚拟对象（dummy）。

防守模式: 无（None）， 自动（Auto）
  如果防守模式设置为自动（Auto），虚拟对象（dummy）将
  尝试阻止大多数攻击。如果防守模式设置为无（None），
  虚拟对象（dummy）将不会阻挡任何攻击。

虚拟对象（Dummy）模式: 站立，蹲下，跳跃，W 跳跃
  根据您的选择，虚拟对象（dummy）将站立、
  蹲下或反复跳跃。如果你选择 W 跳跃，假人
  将尽可能长时间地保持空中跳跃。

距离（Distance）：任意（Any）、近（Close）、中（Medium）、远（Far）
  如果您选择“近”、“中”或“远”，虚拟对象（dummy）
  将根据需要 向前/向后 行走，试图与您保持适当的
  距离。如果选择“任意”，虚拟对象（dummy）将不会
  向前或向后移动。

按键塞（jam）: None, A, B, C, X, Y, Z, Start
  虚拟对象（dummy）会反复触发选定的按钮。很适合
  测试角色的格挡。

您可以在训练菜单处于活动状态时按 M 将其最小化。
再次按 M 可重新启用。



=====================================================================
IV. 游戏热键（Game HotKeys）
=====================================================================

这些是在战斗界面中识别的热键。

Key       Function
---       --------
Pause     暂停
ScrollLck 暂停中的帧步（Frame-step）
Esc       退出

以下热键是用于调试的，可以通过在 mugen.cfg 中
设置 AllowDebugKeys = 0 来禁用。

Key       Function
---       --------
F1        设置玩家2的生命值为0
Ctrl-F1   设置玩家1的生命值为0
F2        设置两个玩家的生命值为1
Ctrl-F2   设置玩家1的生命值为1
Shift-F2  设置玩家2的生命值为1
F3        为两个玩家生命值回满
F4        重新这局
Shift-F4  重新加载舞台（stage），角色和战斗数据
F5        时间结束
F12       截图（保存为 mugen?.pcx）
Ctrl-C    切换碰撞箱、目标数据（包括其他
          的剩余点）和 NotHitBy 属性的显示
Ctrl-D    切换调试信息显示
Ctrl-I    迫使两个玩家进入待机状态
Ctrl-L    切换生命条和能量条的显示
Ctrl-S    尽可能快速地运行游戏
Ctrl-V    启用V-sync（停止 "剪切（shearing）"）。
Ctrl-#    （其中 # 为1-4）切换第 # 个玩家的AI。
Ctrl-Alt-# （其中 # 为1-4）启用 / 禁用第 # 个玩家
Space     恢复所有玩家的全部生命和能量。



=====================================================================
V. 速度问题（Speed Issues）
=====================================================================

如果你发现它在你的机器上运行得很慢，你可以做一些
事情来提高它的性能。你可以在 data/mugen.cfg 中
更改这些选项。

关闭其他应用程序
  关闭其他会占用 CPU 和内存的应用程序
  以提升M.U.G.E.N的运行速度。

使用最有效的视频模式
  在某些系统中窗口运行游戏会很慢。试着
  用全屏运行。在 mugen.cfg 中设置 FullScreen = 1 。

设置一个较小的分辨率
  如果 MUGEN 在高清分辨率下运行太慢，请尝试运行 640x480 或 640x360
  分辨率。

关闭阴影
  你可以关闭阴影来加快渲染速度。
  查找 data/mugen.cfg 并将 [Config]
  下的 "DrawShadows" 设为0。

使用跳帧（frameskip）译注：一种软件功能，可以跳过某些动画帧的显示，从而以牺牲视觉平滑度为代价来提高性能。
  默认启用自动跳帧（Auto-frameskip）功能。
  在电脑速度不够快的情况下，游戏将不会绘制一些帧，
  这有助于保持恒定的游戏速度。
  如果你想以恒定的帧率运行，你可以反复按下Ctrl-F
  来调整跳帧。它会从“自动”到“无”再到“跳过1”再到
  “跳过2”，然后再回到“自动”。
  这只在你进入战斗画面时有效。

释放内存
  内存不足时，内存可能会交换到硬盘上，
  这将严重影响性能。请参阅下一节有关如
  何减少内存使用的信息。

禁用预缓存
  如果您发现在后台加载时游戏速度缓慢太多，
  则可以禁用预缓存。但是，这将增加加载时间。
  在 [Misc]下，将 precache = 0。



=====================================================================
VI. 内存问题（Memory Issues）
=====================================================================

如果您发现由于内存不足而导致程序退出或运行缓慢，
请执行以下解决方案：

减少玩家缓存
  M.U.G.E.N将尝试将玩家保留在内存中，
  以减少加载时间。您可能希望减少一次保留
  在内存中的玩家的数量。
  打开 data/mugen.cfg ，然后在 [Misc] 部分
  下查看。将 PlayerCache 更改为较小的数字。
  0将为您节省最多的内存。

减少角色数量
  包含大量角色会消耗大量内存。您可以将角色
  名册分成多个主题（motifs）。请参阅本自述
  文件中的“使用主题（Using Motifs）”。

禁用缓冲读取
   通过关闭此选项，可以在加载角色时节省内存。
   它位于 [Misc] 部分下，称为"BufferedRead"。
   加载时间将因此增加。

减少影响和限制
  将 [Config] 下的选项设置为较小的数字（有关说明，
  请参见 mugen.cfg ）。减少 HelperMax 可以节省更多。

启用系统文件卸载
  将 [Misc] 下的 UnloadSystem 设置为 1。

优化你的精灵（sprite）文件
  生成精灵文件时，请启用诸如 sprite.autocrop 和
  sprite.detectduplicates 之类的设置。如果您的
  精灵使用32位或更少的颜色，请考虑使用lz5压缩（请
  参阅 work/kfm/kfm-sff-optimized.def ）。



=====================================================================
VII. 已知的问题 / 注意事项（Known Issues / Notes）
=====================================================================

我们论坛上保留了最新的已知问题列表。
http://elecbyte.com/forum/



=====================================================================
VIII. 示例内容（Sample Content）
=====================================================================


此发行版中包含的样本内容为：

Content                   Location
-------                   --------
Base motif                data/
"mugen1" HD motif         data/mugen1
KFM "classic" character   chars/kfm
KFM character             chars/kfm720
Fonts                     font/
Mountain temple stage     stages/kfm.def, stages/kfm.sff
Training room stage       stages/stage0.def, stages/stage0.sff
Training room HD stage    stages/stage0-720.def, stages/stage0-720.sff
Work files                work/


所有示例内容均已根据知识共享许可
非商业许可，带有可选的出处。

基本上，这意味着您不需要我们的许可就可以
将这些内容的任何部分用于任何非商业目的。
实际上，我们鼓励您使用样本内容作为项目
的起点，并替换图形，声音和行为。
如有任何疑问，请随时与我们联系。

有关CC许可证的更多信息，请参见：
http://creativecommons.org/licenses/by-nc/3.0/



=====================================================================
A. 许可协议（License Agreement）
=====================================================================

By using M.U.G.E.N, you agree to the terms and conditions of this
license.

This license applies to the M.U.G.E.N Environment, defined as the
M.U.G.E.N executable, and other associated data files provided by
Elecbyte that are necessary for proper operation of the executable.


Usage

Under this license, permission is granted to use the M.U.G.E.N
Environment free of charge for non-commercial purposes.


Redistribution

Elecbyte provides a M.U.G.E.N redistributable package, containing a
minimal M.U.G.E.N Environment, that may be included with third party
content for redistribution. Such Works based on the M.U.G.E.N
Environment may be used and distributed, subject to the following:

i. Works containing the M.U.G.E.N Environment must be provided free
of charge and under the terms of this license.

ii. Works containing the M.U.G.E.N Environment must include an
unmodified copy of this license, as well as any other licenses
bundled with the M.U.G.E.N Environment.

iii. Works containing the M.U.G.E.N Environment must be plainly marked
as a such.

iv. You agree to indemnify Elecbyte from any legal liability for your
use, or distribution, of such Works.

Please note that Elecbyte places no restrictions on the distribution
of character files, stage files, add-on packs, or similar items which
operate under the M.U.G.E.N Environment, that do not contain any
significant portion of the M.U.G.E.N Environment itself.


Restrictions

This license is subject to the following restrictions:

1. The M.U.G.E.N Environment is copyrighted by Elecbyte and may not
be used for commercial purposes in whole or in part, altered or
unaltered, without Elecbyte's express written permission.

2. All distributions of the M.U.G.E.N Environment must retain a copy
of this license.

3. The M.U.G.E.N executable must not be modified for use or
redistribution.


Limitations

I. You agree to indemnify Elecbyte from liability for any damage
incurred to any computer hardware, software, or other property, as
well as from any injury incurred to your person or others, through
use of this software.  Elecbyte shall not be held responsible for any
failure of M.U.G.E.N and its associated tools to operate properly,
whether through deficiencies of the software or through user error.
Elecbyte disclaims all express and implied warranties, including but
not limited to warranties of merchantability and fitness for a
particular purpose.

II. Failure by Elecbyte to enforce any of the terms of this agreement
shall not constitute forfeiture of Elecbyte's right to enforce said
terms.

III. In the event of an inconsistency between this license agreement and
other Elecbyte documents, the terms of this license agreement shall
prevail, subject only to possible supersession by subsequent license
agreements. If any of the terms of this license agreement conflict with
the laws in your locale, the conflicting terms will be rendered null and
void. The remainder of this agreement shall still obtain.


Sample Content

Please note that the sample content included with the full M.U.G.E.N
package is not part of the M.U.G.E.N Environment, and is under a
separate license, the Creative Commons Noncommercial License, with
optional attribution.
http://creativecommons.org/licenses/by-nc/3.0/



=====================================================================
B. 鸣谢（Acknowledgements）
=====================================================================

Thanks to:
- All our alpha and beta testers.
- Everyone who contributed to us in any way.
- All of you who gave feedback to us.
- Everyone responsible for the software libraries we used:
  Allegro, FreeType Project, GLEW, libogg, libpng, SDL, SDL_gfx,
  SDL_image, SDL_mixer, SDL_ttf, SMPEG, zlib.  Also everyone
  reponsible for the other libraries we used in the older versions.

If we forgot to mention someone, please let us know!
