# File_Managers_Redirection (AutoHotkey v2)

⭐ Core function

- Redirect Explorer to Your Preferred File Manager — and Switch Between File Managers Dynamically (XYplorer, Directory Opus, File Pilot).
- Your chosen manager works like a "default" file manager.
- The redirection process hides the Explorer window and is normally invisible.
- The INI file is a configuration file and can be modified as needed.

<img width="697" height="520" alt="FileManagersRedirection_TrayMenu_New" src="https://github.com/user-attachments/assets/f2ae878d-e755-4ec8-8c71-977690479d01" />

Excluded list:

- This PC, Home, etc. need to use CLSID, such as `::{20D04FE0-3AEA-1069-A2D8-08002B30309D}`

- <a href="https://www.autohotkey.com/docs/v2/misc/CLSID-List.htm" rel="nofollow">CLSID list</a>

## Change Log

- **v1.0.25 (2026-11-01):** Added an option to disable automatic Explorer redirection, along with various bug fixes and improvements.
- **v1.0.24 (2026-10-01):** Various bug fixes and performance improvements.
- **v1.0.23 (2026-09-24):** Various improvements.
- **v1.0.22 (2026-05-17):** Reduced Explorer window flickering by using WinMove instead of WinSetTransparent and WinHide.
- **v1.0.21 (2026-05-17):** Minor improvements.
- **v1.0.20 (2025-12-30):** Added multiple-path support for XYplorer and DOpus, along with other improvements.
- **v1.0.19 (2025-12-26):** Fixed the Open_Dir_First logic for XYplorer and DOpus.
- **v1.0.18 (2025-12-23):** Added the Open_Dir_First option and made other improvements.
- **v1.0.17 (2025-12-20):** Various improvements.
- **v1.0.16 (2025-12-18):** Improved item selection and reduced waiting time. Removed the dependency on A_AhkPath.
- **v1.0.15 (2025-12-17):** Improved item selection and reduced waiting time. (Note: Compiled EXEs without AutoHotkey installed required A_AhkPath to be set to the path of AutoHotkey64.exe.)
- **v1.0.14 (2025-12-16):** Improved item selection in XYplorer and DOpus.
- **v1.0.13 (2025-08-25):** Various improvements.
- **v1.0.12 (2025-02-19):** Added File Pilot ↔ DOpus switching and updated menus and hotkeys.
- **v1.0.11 (2025-02-04):** Added XYplorer ↔ DOpus switching.
- **v1.0.10 (2025-02-03):** Improved Explorer window hiding.
- **v1.0.9 (2025-02-01):** Added desktop support, multiple selections and window reuse when redirecting to Explorer, DOpus-to-Explorer redirection, and hotkey tooltips.
- **v1.0.8 (2024-07-19):** Fixed window flickering when redirecting Control Panel.
- **v1.0.7 (2024-07-01):** Added EVENT_OBJECT_SHOW to reduce Explorer window flickering.
- **v1.0.6 (2024-04-28):** Added Recycle Bin redirection and fixed a regular expression.
- **v1.0.5 (2023-11-26):** Added wildcard support to the exclusion list.
- **v1.0.4 (2023-11-26):** Added a configurable exclusion list (one entry per line).
- **v1.0.3 (2023-11-17):** Fixed Control Panel redirection.
- **v1.0 (2023-09-24):** Initial release.

---

## 中文

# 文件管理器重定向 (AutoHotkey v2)

### ⭐ 核心功能

- 将 Windows 资源管理器（Explorer）重定向至你偏好的文件管理器，支持动态切换 XYplorer、Directory Opus 和 File Pilot。
- 使所选文件管理器能够像系统默认文件管理器一样工作。
- 重定向时将 Explorer 窗口移至屏幕外，通常不会看到窗口闪现。
- 支持临时关闭自动重定向，同时保留手动转换功能。
- INI 为配置文件，可根据需要调整设置。

<img width="350" height="267" alt="文件管理器重定向" src="https://github.com/user-attachments/assets/c3963d9f-f16b-4148-b6f4-0806faaec565" />

### 排除列表

在 INI 文件的 `[excludeList_OnePerLine]` 下，每行填写一个排除项，对应路径或项目将不会被自动重定向。

对于“此电脑”“主页”等特殊 Shell 项目，需要使用 CLSID，例如：

`::{20D04FE0-3AEA-1069-A2D8-08002B30309D}`（此电脑）

CLSID 参考：[AutoHotkey CLSID List](https://www.autohotkey.com/docs/v2/misc/CLSID-List.htm)

### 变更日志

- **v1.0.25 (2026-11-01)：** 新增关闭 Explorer 自动重定向的选项，并进行多项错误修复和优化。
- **v1.0.24 (2026-10-01)：** 多项错误修复和性能优化。
- **v1.0.23 (2026-09-24)：** 多项改进。
- **v1.0.22 (2026-05-17)：** 改用 WinMove 将 Explorer 窗口移至屏幕外，替代 WinSetTransparent 和 WinHide，减少窗口闪现。
- **v1.0.21 (2026-05-17)：** 细节优化。
- **v1.0.20 (2025-12-30)：** 新增 XYplorer 和 DOpus 多路径支持，并进行其他改进。
- **v1.0.19 (2025-12-26)：** 修复 XYplorer 和 DOpus 的 Open_Dir_First 条件判断逻辑。
- **v1.0.18 (2025-12-23)：** 新增 Open_Dir_First 选项，并进行其他改进。
- **v1.0.17 (2025-12-20)：** 多项改进。
- **v1.0.16 (2025-12-18)：** 提高项目选中的可靠性并缩短等待时间，移除对 A_AhkPath 的依赖。
- **v1.0.15 (2025-12-17)：** 提高项目选中的可靠性并缩短等待时间。（注意：编译为 EXE 且未安装 AutoHotkey 时，需要将 A_AhkPath 设置为 AutoHotkey64.exe 的路径。）
- **v1.0.14 (2025-12-16)：** 改进 XYplorer 和 DOpus 的项目选中功能。
- **v1.0.13 (2025-08-25)：** 多项改进。
- **v1.0.12 (2025-02-19)：** 新增 File Pilot 与 DOpus 之间的切换功能，并调整菜单和快捷键。
- **v1.0.11 (2025-02-04)：** 新增 XYplorer 与 DOpus 之间的切换功能。
- **v1.0.10 (2025-02-03)：** 改进 Explorer 窗口隐藏方式。
- **v1.0.9 (2025-02-01)：** 新增桌面支持、重定向到 Explorer 时的多选及窗口复用功能、DOpus 到 Explorer 的重定向，以及快捷键切换提示。
- **v1.0.8 (2024-07-19)：** 修复重定向控制面板时的窗口闪烁问题。
- **v1.0.7 (2024-07-01)：** 新增 EVENT_OBJECT_SHOW 事件，减少 Explorer 窗口闪现。
- **v1.0.6 (2024-04-28)：** 新增回收站重定向功能，并修正正则表达式。
- **v1.0.5 (2023-11-26)：** 排除列表新增通配符支持。
- **v1.0.4 (2023-11-26)：** 新增可配置的排除列表，每行一项。
- **v1.0.3 (2023-11-17)：** 修复控制面板重定向问题。
- **v1.0 (2023-09-24)：** 初始版本发布。
