SQVIM
===  
VIM配置文件  
使用Vundle管理插件，Vundle安装方法：http://www.cnblogs.com/qiangji/archive/2011/07/31/Vundle.html

###2012-12-22
* 修改mkview时候保存的位置，防止在win7下权限不够的问题

###2012-12-21
* 去除sinpMate插件，有冲突（插入模式下不可以复制，回退也有问题），使用XPTemplate替代
* 增加Ctrl+Tab 切换tab映射

###2012-12-12
* 增加sinpMate插件
* 增加DoxygenToolkit插件
* 增加进入和退出buf时，自动保存加载上次文件状态（包括语法着色信息，折叠信息等）

###2012-12-11
* 增加格式化全文的快捷键 Ctrl-K,Ctrl-D （仿Visual Studio）

###2012-12-10
* 增加pyflakes插件（python语法检查）
* 增加vim-ipython插件（配合supertab实现python自动完成）

###2012-12-09
* 增加mardown自动预览功能

###2012-12-07
* 增加markdown语法支持

###2012-12-05
* 增加[当前行下移]快捷键：ctrl + n

###2012-11-21
* 鼠标左键双击选中当前单词

###2012-11-15
* 修改Nerd Tree配置
* 修改Tag List插件快捷键为F10
* 修改Nerd Tree插件快捷键为F11

###2012-11-09
* 增加资源管理器打开当前文件功能 F12
* 增加清楚搜索高亮快捷键
* 修复鼠标双击选中单词的一个bug

###2012-11-08
* 增加鼠标左键双击高亮所有当前选中的关键字
* 修改vundle插件的默认安装位置  

###2012-11-07
* 增加supertab插件
* 增加powerline插件
* 设置NERDTreeFind快捷键为 [Leader] t。 使用此快捷键可以快速打开当前文件的位置
* 增加Ctrl+F搜索的映射快捷键
