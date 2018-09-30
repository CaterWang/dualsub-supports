Dualsub
=======

[简体中文](./README.zh-CN.md)

Dualsub is an extension to make YouTube player display two subtitles(aka closed caption) in the same time.

*Note: This project is not open source, this repository only for document and issue trakcer*

| Screenshot |
| :--------: |
| <img src="https://raw.githubusercontent.com/muzuiget/dualsub-supports/master/images/main.png" /> |

| Select Language | Auto Translate |
| :-------------: | :------------: |
| <img src="https://raw.githubusercontent.com/muzuiget/dualsub-supports/master/images/language.png" /> | <img src="https://raw.githubusercontent.com/muzuiget/dualsub-supports/master/images/translate.png" /> |

Features
--------

* Render as native

The second subtitle will be inserted to the original subtitle as a new line, and set font size a bit smaller.

* Any subtitle source

You can choose any subtitle source from the player, or use "auto translate" to translate it to another any language.

* Optimized merge algorithm

Two subtitles never overlay each other, even they have difference time positions.

Install
-------

Install from [Chrome Store](https://chrome.google.com/webstore/detail/dualsub/gnlibmlfpencglodjpgnalbdebfhpmfp)

Usage
-----

First, you need to switch to YouTube New Look, if you still are not enabled, goto https://www.youtube.com/new to enable it.

After install the extension, at video page, a Dualsub toolbar will show on the right of the "view count" title. The Dualsub toolbar only control the second subtitle. The subtitles display or not still control by the player toolbar.

The are two drop-down menus on Dualsub toolbar.

* left one: select source language, includes "auto-generated" subtitle.
* right one: use YouTube bulit-in "auto translate" to translate the source language.

Troubleshooting
---------------

If you jump to another video page, but find out the Dualsub toolbar not showing, try to press `<F5>` to reload the page. Because YouTube not doing a really reload, it is hard to trace the video page had changed.

TODO
----

* custom the font style
* swap two subtitle positions
