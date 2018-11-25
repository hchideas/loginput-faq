# 码表

## 主码表

落格输入法允许你给输入法挂载自己喜欢的码表，\(什么是码表？请移步“常见概念”章节[什么是码表](https://docs.logcg.com/chang-jian-gai-nian/codetable)了解更多\)

如果你选择导入一个码表，那么如下选项就可以生效了，如果你取消勾选了“主码表”，那么下面的这些选项就会失效。

### 逐码显示编码反查

默认关闭，只有在使用主码表后才能开启，开启此模式会在你输入时，在候选词末尾追加显示未键入的编码内容。

### 码表顺序空码下滑

这是一个比较特殊的高级行为控制，如果你不使用码表，就没任何影响。对于码表用户，如果你的码表里有 abcd 码对应了“你好”但 abc 是空码，如果开启了“空码下滑”，那么你输入 abc 的时候就会自动显示“你好”。——对于一般码表用户来说，你可以无视它。

### 空码空格清空 Buffer

如果你输入的码是“空码”，即无法从码表中匹配到任何内容 aka 候选栏为空，那么你按下空格时就会清空 Buffer 而不是上屏 Buffer。

### 上屏模式

上屏模式是为了配合不同码表而生的，我们为你提供了除默认“空格上屏”外的四种不同的自动上屏规则：

* 四码唯一直接上屏：如果你输入的编码数量为 4 且此时候选栏只有一个候选，那么这个候选会直接上屏；如果有多个候选，那么在你输入第五个字母的时候，第一个候选会自动上屏，你可以继续输入；
* 统一第五码顶字上屏：当你输入的编码数量为 5，则自动上屏候选栏中第一个候选，你可以继续输入；
* 空码顶字上屏：如果你输入的下一个字母组合导致候选栏无候选，那么之前的候选会上屏；
* 空码直接上屏：如果你输入的字母组合后续不存在编码（即接下来空码），那么当前候选上屏。

## 辅码

落格输入法允许你给输入法挂载独立的直接辅助筛选码码表（简称辅码），\(什么是辅码？请移步“常见概念”的[什么是辅码](https://docs.logcg.com/chang-jian-gai-nian/assist)章节了解更多\)

如果你选择导入一个辅码码表，那么如下选项就可以生效了，如果你取消勾选了“辅码”，那么下面的这些选项就会失效。

### 末字辅码提示

默认关闭，只有在加载了辅码后才能开启，开启此模式会在你输入时，在候选词末尾追加显示可能的辅码内容。

### 辅码首选后移

在使用辅码进行筛选时很有可能会遇到筛选后首选还是同样的候选——在这种情况下，我们认为你可能并不想要那个首选（毕竟如果你期望那个候选，就直接上屏不用再辅了），那么这时我们会为你将首选和次选进行互换。

### 四码词汇优先

为了避免一个双拼+双辅识别为生僻字作为首选覆盖双拼+双拼作为两个字词汇的情况发生，我们特地开启此模式，所有全码双辅都会出现在次选避免冲突。
