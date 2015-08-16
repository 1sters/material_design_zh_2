# 书写

明确、精炼、简洁的文本让交互界面更加可用，并且更容易让人信任。力求写出所有人都能理解的文本，无论他们的文化或者语言。

除了这些准则，还需要翻阅具体 UI 元素的指南，例如[错误](https://www.google.com/design/spec/patterns/errors.html)，[对话框](https://www.google.com/design/spec/components/dialogs.html)，[设置](https://www.google.com/design/spec/patterns/settings.html)以及[数据格式](https://www.google.com/design/spec/patterns/data-formats.html)。

> 语言  
> 语气  
> 大小写和标点符号
> 全球化书写

## 语言

### 使用“你”对用户说话

直接使用“你”对用户说话，不要用“我”。不要用“我”或者“我的”之类的短语。

例外：
- 一些法律选择：“我同意遵循 UX 书写的规则。”
- 一些 Google Play 种类，例如“我的音乐”或者“我的书籍”

```
你的账户
```
正确

```
我的账户
```
错误

### 不要使用“我们”

书写要专注于用户以及用户可以用你的应用做的事情，而不是你或者你的应用正在为用户做的事情。

```
通过这些 Google+ 上受欢迎的贴子快速开始
```
正确

```
为了让你快速开始，我们将为你展示一些 Google+ 上受欢迎的贴子。
```
错误

```
你可以使用这个页面删除你的 Google+ 档案
```
正确

```
这个贴子允许你删除 Google+ 的档案
```
错误

一个例外是当一个人（不是软件）真的是在为一个用户采取操作，例如重审一个提案或者反馈一个建议。这里，“我们”的使用是合适的，并且比强制被动的选择更加人性化。

```
We’ll review your appeal and respond within a few days.
```
正确

```
Your appeal will be reviewed, and you will receive a response within a few days.
```
错误

### 做到简洁

UI 文本会对导航和发现有帮助。最好的 UI 文本是一些小的段，这样在浏览的时候就不会阅读太多。

```
Send money to anyone in the U.S. who has an email address. It’s fast, easy, and free.
```
正确

```
Send (and receive) money with friends and family in the U.S. with an email address. It’s a two-step process with little-to-no latency and there aren’t any charges for the recipients of the money.
```
错误

让你的语句和短句短一点。用尽量少的概念。

```
Read the instructions that came with your phone.
```
正确

```
Consult the documentation that came with your phone for further instructions.
```
错误

### 使用简单的单词形式

使用主动动词（“狗咬了树”）而不是被动动词（“树被咬”），除非被动动词更加短和简单（“树被咬”）或者没有明确的主体。

### 用现在时书写

大部分 UI 发生于现在，所以你可以用现在时书写。

如果你需要使用过去时或者未来时书写，使用简单的动词形式。

```
Message sent
```
正确

```
Message has been sent
```
错误

### 书写简单直接

简单直接的语言对于用户来说更加容易理解，因为他们通常是大概浏览一个界面。

```
Save changes?
```
正确

```
Would you like to save your changes?
```
错误

### 使用每个人都理解的简单单词
在多个同义词之间进行选择时，挑选最简单的。

```
Turn on Location History
```
正确

```
Enable Location History
```
错误

不要使用只有内部专业人士才能理解的术语，不要使用我们为了 UI 功能发明的名称。

```
Preparing video…
```
正确

```
Buffering…
```
错误

```
“Ok Google” isn’t supported on your phone
```
正确

```
“Ok Google” is only supported on dual-core devices
```
错误

像“slider”和“menu”这样的通用术语还好，将用户引导 UI 元素的标签上，而不是元素的种类（例如菜单和按钮）。

```
Click Continue
```
正确

```
Click the Continue button
```
错误

### 省略不必要的短语

跳过许多通用的介绍性短语，直接说重点。

```
Delete this photo?
```
正确

```
Are you sure you want to delete this photo?
```
错误

```
Register to vote
```
正确

```
You must register before you can vote
```
错误

```
Want to…
```
正确

```
Do you want to…
```
错误

### 在一个操作链中使用一致的动词

一个操作的框架概念是一个典型的动词。挑选一个，在一个操作中一致地使用。

```
Remove photo
```
正确。菜单条目

```
Delete photo
```
错误。菜单条目

```
Remove photo?
```
正确。对话框标题

```
Remove photo from page?
```
错误。对话框标题

```
Remove this photo from this page?
```
正确。对话框文本

```
Cancel | Remove
```
正确。对话框按钮

```
Cancel | OK
```
正确。对话框按钮

### 目标引导而不是方法引导

激励用户学习如何完成一个任务。

```
To remove a photo from this album, drag it to the trash
```
正确

```
Drag a photo to the trash to remove it from this album
```
错误

### 只在必要时显示细节

不要用所有的细节加重用户的负担。只在用户探索和需要信息时，逐步展示功能的细节。

```
Remove downloaded book?
```
正确

```
Are you sure you want to remove this downloaded book? You won’t be able to access it unless you’re online.
```
错误

### 永远不要说“永远不要”

避免使用“永远不要”以及其他很绝对的词。

```
Your circle names aren’t shared
```
正确

```
We’ll never share your circle names
```
错误

### 按钮以及相关元素的文本

按钮出现在对话框以及相似的用户界面中，也可以以蓝色或者带下划线的文本显示。

|| 按钮 || 用法 ||
|-------|--------|
|| 操作 || 查看关于在一个操作链中使用一致性动词的规则 ||
|| 后退 || 为多步骤使用 ||
|| 取消 || 取消一个操作 ||
|| 关闭 || 让一个消息或者对话框消失，不带来任何影响 ||
|| 完成 || 多步骤过程完成之后的确认 ||
|| 了解 || “好的”或者“关闭”的另外一个可选项 ||
|| 了解更多 || 把它当作一个扁平的按钮 ||
|| 下一步 || 用作多步骤处理 ||
|| 不用了，谢谢 || 省略句号 ||
|| 现在不了 || 不要滥用这个短语，除了很有必要，出于法律原因或者其他紧急原因。永远不要使用“现在不了”代替“不用了，谢谢”。 ||
|| 好的 || 使用一个与手边任务有关的操作，例如“删除”或者“保存”；“好的”正在被滥用。 ||
|| 跳过 || 给予用户一个选择，跳过当前的步骤 ||


## 语气

###友好、尊重、关注用户

你的 UI 中的文本应该补充你的视觉 UI ：直观，有效，随和，以及值得信赖。展示魅力，但是不要抢了用户的风头。

```
MyApp isn’t responding

Do you want to close it?
```
正确

```
Sorry!

Activity in MyAppActivity (in the  MyApp app) is not responding
```
错误

### 谦逊

不要夸张或者过度承诺。展示一个功能做什么，不要说它如何好。

```
All your savings in one place
```
正确

```
Great deals at places you’ll love
```
错误

```
More restaurant reviews
```
正确

```
All restaurant reviews
```
错误

### 友好

关注于每个功能的好处。在功能（按钮，菜单条目，链接，以及提示）的进入阶段，省略完成细节，注意事项，以及限制。

```
To save power, switch Location mode to Battery saving mode.
```
正确

```
Manually control GPS to prevent other apps from using it.
```
错误

### 积极

以一个积极的语气展示信息：令人安心。

```
Use 24 characters or fewer for file names.
```
正确

```
Your file name must be less than 25 characters.
```
错误

### 必要

对于每一个消息，问你自己：用户是否真的有必要知道这个？放在一边的错误使得用户专注于自己的任务。有时最有效的 UI 是根本没有文本的。

一个用户的简单操作成功时，避免使用表明这很令人吃惊或者不寻常的消息。

```
Signing in...

Your phone is contacting Google. This can take up to five minutes.
```
正确

```
Signing in...

Your phone needs to communicate with Google servers to sign in to your account. This may take up to five minutes.
```
错误

## 大小写和标点符号

### 使用语句风格的大写

为所有的标题、头部、标签以及菜单条目，还有任何你想用的地方，使用语句风格的大写。

避免全大写，除了 material 规格需要的地方，例如，按钮风格。

```
Search settings
```
正确

```
Search Settings
```
错误

```
SEARCH SETTINGS
```
错误

### 只在当作产品提到一个产品的时候大写产品

不要在使用时大写那些你创建的东西。

```
Visit our Google+ page.
```
正确

```
Visit our Google+ Page.
```
错误

### 略过句号以及其他不必要的标点符号

对于标签、悬停文本、设置标签，大量链接，广告，以及等等，避免使用句号。这给予你拼接句子和句子片段的灵活性，例如，在一个列表中。这还避免了视觉混乱，帮助用户在一瞥之下理解你的文本。跳过 UI 标签之后的冒号（“Share with”而不是“Share with:”）。

使用句号，或者将一个段落分成句子：
- 需要使用不止一个句子——即使他们都是很短的句子。
- 有一系列的标签，其中一个标签必须是一个句子。让它们都变成完整的句子，并加上句号（或者问号，等等）。
- 句子是更大更正式的 UI 元素中的部分，例如对话框中的主题文本。

### 使用缩写

不要为了遵守规则使得用户难以理解一个句子。例如，“do not”可以比“don't”带来更多的强调。

```
it’s, can’t, wouldn’t, you’re, you’ve, haven’t, don’t
```
正确

```
it is, cannot, would not, it’ll, should’ve
```
错误

### 避免感叹号

问你自己，会有人这样喊出来吗？

```
Welcome!
```
正确

```
Learn about the new features of Calendar!
```
错误

```
Good job!
```
正确

### “1, 2, 3” 而不是 “one, two, three”

使用数字而不是单词来代表数字。

一个例外是混合使用数字时：“Enter two 3s.”。

```
You have 3 messages
```
正确

```
You have three messages
```
错误

### 标点符号

在短语和标签之后省略标点符号来构建一个简洁可读的界面。

使用标点符号来增加清晰度和语法正确性。

|| || 代表/符号 || 描述 ||
|| 句号 || . || 为 toasts，snackbars，butterbars，以及标签中的提示中的段落和短句子省略。但是需要为主题内容中的整句子加上标点，例如，在对话框的主体中。在引号中包含（除非是你正在告诉用户输入什么，否则是否包含很含糊。  ||
|| 逗号 || , || 在引号中添加，使用序列化的逗号。 ||
|| 感叹号 || ! || 避免为你不会真正喊出来的内容添加感叹号。 ||
|| 冒号 || : &#58; 或者 \u003A || 为标签省略，例如表单中的标签 ||
|| 引号 || “ &ldquo; 或者 \u201C ” &rdquo; 或者 \u201D ‘ &lsquo; 或者 \u2018 ’ &rsquo; 或者 \u2019 || 使用真正的引号，而不是英寸或者脚符号。右单引号还被用来做省略号。不要使用通用引号。这对于引号，省略号以及撇号都是不正确的。 ||
|| 撇号 || &prime; 或者 \u2032 以及 &Prime; 或者 \u2033 || 只在英寸、弧分以及分钟中使用撇号。例如： 3° 15′。只在英寸、弧分以及分钟中使用双撇号。例如：3° 15′ 35″。不要使用通用引号代替撇号 ||
|| 省略号 ||  … Option-; &hellip; || 用来在一个操作过程中指示（“下载中…”）或者一个不完整或者截断的文本中。省略号前没有空格。为打开对话框或者开启其他进程的菜单条目或者按钮省略。中线省略号（三个圆点）也被用来代替敏感数据的截断，例如信用卡。 ||
|| 双尖角括号 ||  >>, << &laquo; 或者 \u00AB &raquo; 或者 \u00BB || 为开启其他页面的链接或者按钮省略 ||
|| 长破折号 || — &mdash; or \u2014 Shift+Option - || 避免：通常表面你的句子结构很复杂。不要用连续的连字符代替长破折号。 ||
|| 短破折号 || – &ndash; or \u2013 Option+ - || 代替连字符来表示一段范围。省略短破折号与连接字符之间的空格。（我们的日期和时间库通过包围的空格来设置短破折号，对其他语言也是合适的。）例如：8:00 AM–12:30 PM 3–5 kg ||
|| 连字符 || - || 使用连字符来避免符合连成词中的含糊性。 例如：“anti-inflammatory” “5-mile walk” ||

## 全球化书写

各种年龄、文化、背景以及教育层次的人们依赖于英语版本的产品。许多书写规则支持非本地英语书写以及本地化（为了全球化使用而进行的翻译和转化）。简单、明确的英语让每个人更容易理解你的产品。

本节专注于如何书写英语，让你的产品对于英语以及全球的其他语言更加可用。

### 不要使用特别文化的成员，隐喻，或者例子

特别文化背景的语言会很难翻译，并且在某些本地化中不合适。

```
Discover great offers
```
正确

```
Snag great offers
```
错误

```
No offers left.
```
正确

```
Bummer. There are no offers left.
```
错误

```
Great job!
```
正确

```
You really hit it out of the park!
```
错误

### 注意“左”和“右”

在一个产品本地化时，使用从右到左脚本语言的界面可能需要镜像。

### 避免性别含糊

英语是很少数几个允许性别含糊的语言（例如，“you can see their picture”）。许多其他的语言都是必须指定性别的（“you can see his or her picture”）。

### 书写清晰的字符描述

作为代码中评论，为你的字符串提供清晰的描述。语言学家依赖于描述性的文本来将一个有意义的字符串翻译到其他文化，而不是原始文本的逐字转化。







