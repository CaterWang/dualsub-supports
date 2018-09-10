DualSub
=======

DuaSub 是一个 Chrome 浏览器扩展，让 YouTube 播放器实现双语字幕。

*注意：本仓库只是作为文档和支持系统，项目不是开源的。*

| 效果截图 |
| :------: |
| <img src="https://raw.githubusercontent.com/muzuiget/dualsub-supports/master/images/main.png" /> |

| 语言选择 | 自动翻译 |
| :------: | :------: |
| <img src="https://raw.githubusercontent.com/muzuiget/dualsub-supports/master/images/language.png" /> | <img src="https://raw.githubusercontent.com/muzuiget/dualsub-supports/master/images/translate.png" /> |

特性
----

* 原生方式渲染

其实就是把第二字幕作为新行插入到原来的字幕里面，并把字体设置为小一点。

* 任意字幕语言

可选的语言就是视频自己提供的，也可以用自动翻译转成另外一种语言。

* 合并算法优化

稍微用了点算法实现避免重叠，以及处理时间轴不一致。

安装
----

目前只能以 Chrome 开发者模式安装使用，从 [Release](https://github.com/muzuiget/dualsub-supports/releases) 页面下载 zip 文件。

[为什么不在 Chrome 商店发布？](https://github.com/muzuiget/dualsub-supports/issues/1)

使用方法
--------

对于中国大陆用户，需要对 `*.appspot.com` 加入科学上网。

仅支持 YouTube 的新界面，如果你还没启用，浏览 https://www.youtube.com/new 开启。

安装扩展后，浏览视频页，扩展的工具栏会出现在“浏览次数”文字的右边。扩展工具栏仅控制第二字幕，自带字幕和字幕的显示，依旧由播放器的设置按钮控制。

扩展的工具栏就两个下拉框：

* 左边的：选择字幕语言，语音识别“自动生成”也在这里选择。
* 右边的：将左边的语言用 YouTube 自带的机器翻译成其它语言。

## 常见问题

因为 YouTube 的新界面用了黑科技，页面跳转不需真的刷新页面，例如从搜索结果页跳到视频页，即使地址栏地址变了，但是页面还是没刷新的，有时候扩展未能检测出页面变动，读取不了新视频的字幕信息，需要你手动按 `<F5>` 实际刷新一下。
