# RollCall
点名播报小程序

一款基于 Python + CustomTkinter + Windows SAPI 的“随机点名”桌面工具，提供：  
- 圆角扁平化现代化 UI  
- 红色闪烁高亮“被点中”姓名  
- 播报中文姓名（基于 Windows SAPI，无需额外 TTS 引擎）

使用方法：
在names.txt中每行写入一个名字，并将其放在rollcall.exe文件的同目录下。
之后再运行rollcall.exe文件即可实现对names.txt名单中人员的随机点名。
