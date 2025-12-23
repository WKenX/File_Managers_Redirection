# File_Managers_Redirection (AutoHotkey v2)

⭐ Core function

- It lets you set your preferred file manager as the default.

- The redirection process hides the Explorer window and is normally invisible. The ini file is a configuration file and can be modified according to needs.

<img width="507" height="306" alt="image" src="https://github.com/user-attachments/assets/119754ff-004f-49cd-bfc6-d329f1aa4edd" />

Excluded list:

- This PC, Home, etc. need to use CLSID, such as `::{20D04FE0-3AEA-1069-A2D8-08002B30309D}`

- <a href="https://www.autohotkey.com/docs/v2/misc/CLSID-List.htm" rel="nofollow">CLSID list</a>

Change Log:
```
v1.0.18(2025-12-23): Some improvements and a new tweak: Open_Dir_First.

v1.0.17(2025-12-20): Some improvements.

v1.0.16(2025-12-18): Ensure the item is selected while also reducing waiting time. (Remove A_AhkPath.)

v1.0.15(2025-12-17): Ensure the item is selected while also reducing waiting time. (Note: When compiled to EXE and AutoHotkey is not installed, set A_AhkPath to the path of AutoHotkey64.exe.)

v1.0.14(2025-12-16): Ensure the item is selected in both XY and DOpus.

v1.0.13(2025-08-25): Some improvements.

v1.0.12(2025-02-19): FP<->Opus and menu, shortcut key changes, etc.

v1.0.11(2025-02-04): XY<->Opus

v1.0.10(2025-02-03): Adjust the code to hide Explorer window.

v1.0.9(2025-02-01): Supports desktop. Redirect to Explorer supports multiple selections and reuse of windows. redirects Opus to Explorer. hotkey switching adds tooltips.

v1.0.8(2024-07-19): Fixed flickering when redirecting control panel.

v1.0.7(2024-07-01): Adding EVENT_OBJECT_SHOW event, seems to make the window almost invisible.

v1.0.6(2024-04-28): Redirect Recycle Bin, correct regular expression.

v1.0.5(2023-11-26): Added wildcard support to excluded list.

v1.0.4(2023-11-26): Added excluded list, one per line.

v1.0.3(2023-11-17): Fixed redirection Control Panel.

v1.0(2023-09-24): Created.
```
##
# 文件管理器重定向 (AutoHotkey v2)

⭐ 核心功能

- 它可以让你将自己喜欢的文件管理器设置为默认文件管理器。

- 重定向过程会隐藏资源管理器窗口，通常情况下是不可见的。ini 文件是一个配置文件，可以根据需要进行修改。

- <img width="462" height="303" alt="文件管理器重定向" src="https://github.com/user-attachments/assets/86818a87-9318-4bd9-a10c-88c84617661e" />

排除列表:

- 此电脑、 主页等等需要使用CLSID, 比如 `::{20D04FE0-3AEA-1069-A2D8-08002B30309D}`

- <a href="https://www.autohotkey.com/docs/v2/misc/CLSID-List.htm" rel="nofollow">CLSID list</a>

变更日志：
```
v1.0.18
一些改进，和一项新调整：Open_Dir_First

v1.0.17
一些改进

v1.0.16
确保选中项目同时降低等待时间（移除A_AhkPath）

v1.0.15
确保选中项目同时降低等待时间（注意：若编译为EXE文件且未安装AutoHotkey，需将A_AhkPath设置为AutoHotkey64.exe的路径。）

v1.0.14
确保XY和Opus选中项目

v1.0.13
一些改进

v1.0.12
FP<->Opus和菜单、快捷键修改等

v1.0.11
XY<->Opus

v1.0.10
调整隐藏Explorer窗口代码

v1.0.9
支持桌面，重定向到Explorer支持了多选与重用窗口，重定向Opus到Explorer，热键切换增加了工具提示

v1.0.8
修复了重定向控制面板时的闪烁

v1.0.7
添加EVENT_OBJECT_SHOW事件，似乎可以使窗口几乎不可见

v1.0.6
重定向回收站、更正正则表达式

v1.0.5
排除列表添加通配符支持

v1.0.4
添加排除列表，[excludeList_OnePerLine]下面填写的路径都不会重定向，CLSID列表查看https://www.autohotkey.com/docs/v2/misc/CLSID-List.htm

v1.0.3
修复重定向控制面板

v1.0(2023-09-24): 创建
```
