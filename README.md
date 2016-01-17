v1.6.1更新内容
UPDATE:解压缩显示解压缩的文件
UPDATE:解决BUG
UPDATE:全新按钮，效果看hezi.be

v1.6更新内容
ADD:目录面包屑导航，可以随时进入母目录
ADD:显示解压缩的文件，显示解压错误的提示
ADD:全新界面
UPDATE:解决远程上传失败的问题
UPDATE:优化代码，解决CSS的BUG
UPDATE:导航栏中取消自杀按钮
UPDATE:导航栏中增加返回原目录的按钮
UPDATE:设置默认密码为hezi.be
UPDATE:Windows下不再显示权限设置

v1.5.3更新内容
UPDATE:美化界面
UPDATE:修改菜单和按钮为浮动显示
UPDATE:解决上传解压的同时删除失败的问题
UPDATE:解决部分空间mb_detect_encoding函数不支持的问题
UPDATE:解决PHP5.4版本setcookies显示Cannot modify header information的问题
UPDATE:解决PHP5.4版本end函数Only variables should be passed by referen的问题
UPDATE:精简代码

v1.5.2更新内容
UPDATE:删除过时函数mysql_list_tables
UPDATE:编辑文件时可以编辑任意编码的函数了
UPDATE:解决压缩文件时多了一个"."文件的BUG
UPDATE:移动时自动在后面加上/
UPDATE:显示文件夹的时候自动在后面加上/
UPDATE:现在FileBox的代码更加紧凑
UPDATE:使用Curl代替原来的远程下载（若服务器不支持，还是使用原来的函数），增加效率
UPDATE:使用file_put_content代替部分fwrite函数

v1.5.1更新内容
UPDATE:这是正式版的第一个维护版本
UPDATE:为所有Input加上了一个label，直接点击文字即可选中选择框！
UPDATE:修改编辑框字体，默认为Yahei Consolas Hybrid，下载本字体后可以获得更好的体验
UPDATE:修改默认英文字体，为Verdana
UPDATE:解决压缩是子目录获取不到.htaccess的BUG
UPDATE:删除“目录压缩”功能
UPDATE:现在可以显示文件夹的大小了

v1.5.0更新内容
ADD:文件复制功能
ADD:文件安全登录次数（$safe_num）
UPDATE:删除无用代码
UPDATE:优化错误提示
UPDATE:从v1.5开始，FileBox正式支持中文文件和目录的编辑和删除等功能
UPDATE:解决全站备份出现的错误
UPDATE:优化部分界面的HTML代码
UPDATE:解决不显示.htaccess等以“.”开头文件的BUG

v1.4更新内容
ADD:文件权限的读取与编辑（Chmod）
UPDATE:解决重命名时点击按钮无效的BUG
UPDATE:因为批量删除功能的添加，取消“单个文件删除”的功能
UPDATE:直接点击文件名直接进入文件而不是编辑
UPDATE:文件“查看”与文件夹“压缩”功能合并，节约空间
UPDATE:删除部分无用代码
UPDATE:网站自杀时增加友好提示
UPDATE:当一次编辑完后可以选择继续编辑
UPDATE:部分页面添加了返回功能，优化文件大小显示
UPDATE:全部代码缩进，增加可读性

v1.3更新内容
ADD:批量移动功能
ADD:多文件压缩功能
ADD:FTP上传拓展 支持修改端口 支持修改上传目录 支持上传后同时删除被上传的文件
UPDATE:把全选的Checkbox移到下面 更易理解它的作用
UPDATE:解决目录压缩会多出一个.目录的BUG
UPDATE:如果没有输入FTP端口，默认使用21
UPDATE:给Table和Form加上了max-height，防止文字溢出后显示不正常
UPDATE:优化部分提示，优化代码

v1.2更新内容
1. 对大部分函数增加了缩进，增强了文件的易读性
2. 上传时增加“提取上传的压缩文件”和“同时删除压缩文件”两个选项
3. 增加访问目录时可以返回上级目录功能，增加“全选”功能
4. 人性化提示，现在错误提示全部使用printerror()函数
5. 解决上传文件会省略最后一个文件的BUG
6. 解决远程文件无法下载的BUG

v1.1更新内容
1. 美化界面 
2. 优化代码
3. 增加操作完后返回原来的目录的功能
4. 将原本的目录选择改为用Text框自定义目录，不会再出现文件名太长页面被撑大和想移动和上传文件却要的先创建文件夹的冏事
5. 增加批量上传功能，为上传时的文件选择框添加Multiple属性，支持选择多个文件后上传
6. 优化多处的文字提示，取消原来的禁止错误信息显示的代码
7. 效率优化 用preg_replace()替换ereg_replace()等
