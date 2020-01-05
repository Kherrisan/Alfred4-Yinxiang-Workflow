# Alfred4-Yinxiang-Workflow

**改好的Workflow在Release里面**

由于 Alfred4 无法使用老的 workflow 来操作印象笔记，所以我从论坛上下了 alfred4 对应于 Evernote 的 workflow，并对脚本进行了一些修改，使得其能够在 Alfred4 中操作 印象笔记。

**我就是个从没接触过Alfred Workflow开发、AppleScript开发的小白，只是尝试通过各种小修小补来实现功能，不保证完美运行。**

## 涉及的改动

1.所有scpt文件中的 com.evernote.Evernote 改为 com.yinxiang.Mac
2.bundleid 由 com.runningwithcrayons.Alfred3 改为 com.runningwithcrayons.Alfred3
3.workflow.scpt 中的 my_data 写死成绝对路径

## 使用环境

1. macOS Catania
2. Alfred 4.0.5
3. 印象笔记 9.2.0
4. [基于Evernote Workflow 9 beta 4 (Alfred 4)](https://www.alfredforum.com/topic/840-evernote-workflow-9-beta-4-alfred-4/)

至少我在如上的环境下是可以正常使用该Workflow的。
