# WindowsOpenFilecatalogByInternetExplorerDirectly
网页式管理文件目录



Time :  2020/06/12 9:33:00 周五
Author : WeiTingjun
Description:
背景：	1. 打开文件时，目录层次太多，需要多次操作才能找到目标文件。例如：D:\Applications\Python38\Lib\site-packages\win32comext\authorization\demos；
		2. 时间长了，不清楚当初把文件放在哪个目录里；
		3. 打开无数文件资源管理器，再找目标文件时，需一个个的确认；
		4. 常用文件目录，每天得重复操作，耗时耗力；

提供功能：
		1. 解决以上痛点，提高工作效率
		2. 网页式集中管理文件目录，清晰明了；
		
操作指南：
		1. 将本文件放在任意位置(桌面或文件夹)；
		2. ie浏览器打开；
		3. 浏览器打开文件时，会提示“在此页上的ActiveX控件和本页上的其他部件的交互可能不安全。你想允许这种交互吗？”，点击“是”；

注意事项：
		1. 仅支持ie浏览器、windows系统；
		2. 文件夹名如果是纯数字可能会出问题(例如：D:\Applications\12)，建议修改文件夹名为非纯数字文件夹；
		3. 不支持打开文件，例如：D:\Applications\test.txt；
		4. 文件目录不要有名为“urls.txt”的文件
		
