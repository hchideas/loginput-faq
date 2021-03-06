# 键盘手势操作大全

我们按照不同的手势将功能分类，落格输入法键盘支持的手势包括“长按”、“上下轻扫”、“左右拖动”、“左右轻扫”、“双击”等。

## 长按

* 在键盘按钮 `a`或 `l`上长按以进入单手键盘；

  在任何情况下，尝试在键盘`a`或`l`按钮上长按，即可进入单手键盘模式。

> 对于使用德沃夏克（Dvorak）键盘布局的用户，需要使用键盘按钮`a`或`s`来进入单手键盘模式；对于阔码（Colemak）键盘布局则是`a`和`o`；沃码（Workman）则是`a`和`i`。另外对于分号模式下快蹄（Qwerty）键盘布局分号在最右边，则变为长按分号键。

* 在键盘退格按钮长按以连续删除；
* 在回车按钮上长按以输入换行符；

  比如在 TIM 中，长按回车按钮以换行。

* 在候选词上长按以删除学习到的候选词；

  特别的，如果是系统词库或码表中的候选词，则不能通过这种方式删除，这种方式仅可以删除键盘学习到的智能联想结果以及用户词。

  > 对于非落格输入法 X 用户，你需要在候选词上`上划`而不是长按来进行同样的操作。macOS 用户则是 control + 1 。

* 在其他任意字母按键上长按以进入快捷编辑模式；

  此模式允许用户快捷选择输入框中的文字并进行简单的编辑，需要注意的是键盘的剪切板是独立于系统的，两者并不互通；另外你还可以在这个界面快捷开关一些临时选项，以及临时地调整键盘的高度。

## 上下轻扫（点划）

* 在字母 `e` 下划进入英文模式；
* 在字母`p`下划进入隐私模式；

  隐私模式下，键盘的智能联想不会分析和学习你的输入内容，键盘也不会从你键入的过程中学习新词，键盘也不会记录你的按键次数以及上屏字数等。

* 在字母`b`下划进入键盘大团结管理面板；

  在这个面板中你可以管理键盘本地存储的智能联想矩阵以及键盘学习到的用户词——一键清空；你也可以查看键盘的按键数量统计。

* 在字母`n`下划进入键盘的快捷笔记功能；

  你可以在任何地方进入此功能快速记录想法便签并存储到键盘的“快捷短语”中。

* 在其他按键上 下划 打开表情和短语；

  总之，为了让键盘界面更加简洁美观——同时又能兼顾左右手用户，我们把表情和短语的功能做到了同一个面板上，同时打开的方法也由固定的按钮变成了更加灵活的手势，现在你在键盘任意字母上下划即可打开表情与短语界面，打开的第一个界面取决于你上次关闭是的界面。你可以在候选条上显示出来的标签上来回切换 Emoji 、颜文字以及快捷短语。

  > 特别地，由于键盘上下点划实际上是完全可以自定义，上文中的点划功能为默认设置，所以具体的上下点划功能以用户实际定义为准，

* 在空格上点划（向上轻扫）来输入通配符；

  如果你使用了主码表，那么你就可以通过在空格上点划来输入一个通配符。

* 在候选栏下划收起键盘

  一般来说，不同的 app 都有自己的收起键盘的功能实现，比如在聊天软件中点击屏幕就是收起键盘，比如淘宝 app 中在某些地方就自带了一个收起键盘的按钮……总之，如果在某些特殊的地方，你实在需要这个功能而 app 本身又没有提供，那么就从候选栏下划来收起键盘。

## 左划

* 候选栏左划加载更多候选字；

  我们经过统计发现基本上来说，大多数用户并不会每次都打单字，而单字加载又是一个吃性能的大户，所以每次输入，只要你不输入单字，然后一次性输入越长，那么性能就浪费越多。我们现在并不会在候选栏加载所有的候选，实际上后台根本就不会去查询这些字。只有你在需要的时候_（即拉动候选条时）_，才会重新加载完整的候选。

* 清空输入的 buffer；

  在退格键上向左单指轻扫，就可以快速清空无意义的 buffer 内容而不用一个一个的删除了。

* 时光回溯；

  在回车键上向左单指轻扫，就可以回溯之前的上屏。

## 拖动

* 在键盘上左右滑动以移动光标

  在不输入任何内容的情况下在键盘上单指左右轻划可以快速移动光标；特别地，如果你开启了设置中的“输入中允许移动光标”，那么你就可以在输入的过程当中也能灵敏地移动光标了。

* 快捷输入符号

  如同系统输入法那样，你只需要按住“123”并拖动到对应的符号上，就可以快捷地输入符号而不需要切换到符号键盘再切换回来。

* 快捷输入大写字母

  如同系统输入法那样，你只需要在 shift 键开始拖动并在对应的字母上停止，就可以快速输入一个大写字母到 Buffer 从而方便你输入英文词汇。

## 双击

* 锁定大写输入

  如同“快捷输入符号”中描述的那样，你也可以用同样的手势来快速输入大写字母——不过，如果你打开了 ⇧ 作为次选，那么在有候选词的时候 ⇧ 就会上屏次选而不是打开大写键盘。最后，你也可以双击它来锁定大写键盘而不必每次都切换。

