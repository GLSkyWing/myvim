# myvim

vim插件

组合用的
vim surround
vim repeat

http://blog.csdn.net/wklken/article/details/9076621

http://linux.cn/article-2355-1.html


buffers
b 1
b 2
buffers  查看buffer中的文件
:bp
:bn

tab
s+T open a tab
s+H 前一个tab
s+L 后一个tab



快捷键
,er ,sr 打开和保存vimrc配置


Y 复制到行尾
,f+数字 设置折叠等级
,fc 找merge conflict
,/ 取消搜索关键词高亮

:cwd 
cd. 
切换目录到当前文件目录

:w!! 忘记sudo sudo保存

打开文件的方式
,ew
,es
,ev
,et

,ff  查找关键词 并提示跳转

zl zh  水平滚动

,q  format


c-u  undo tree


c-p ctrlp -> c-f 切换  ,fu 函数查找 c-r 切换正则


,jt  json change


插件 
1. tab格式化  ,a(格式化的字符)  按照字符格式化
   2.ctrlp  c-p查找文件 c-r 查找buffer ,fu查找函数
   3.tagbar ,tt tag
   4.vimtags 
   5.fugitive git的插件 后面看
   6.youcompleteme 最后看
   7.undo tree : c-u
   8.indent line 
   9.wildfire  

   10.auto-pair  里面的c-h跟我的冲突 去掉以后就好了 还有一个restore_view.vim 会保留这个状态 不知道什么原因 去掉以后 更改autopair就好了






