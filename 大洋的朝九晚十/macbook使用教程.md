# 1. 访达
![[Pasted image 20240619233506.png]]
访达类似于windows的资源管理器

# 2. 右上角-菜单栏
![[Pasted image 20240619233606.png]]
按住command然后拖移就可以改变图标的位置


# 3. 最下边-程序坞
![[Pasted image 20240619233725.png]]

![[Pasted image 20240619233809.png]]
![[Pasted image 20240619233825.png]]
最近使用过的，但是没有放到控制台的程序就会放到中间
启动台![[Pasted image 20240619233938.png]]

![[Pasted image 20240619234031.png]]最小化时也会暂放在这里


![[Pasted image 20240621151431.png]]

## 3.1 隐藏和显示
快捷键：command + option + d 


# 4. 键盘

windows的 `ctrl`、`alt`、`shift`在mac变为了`command`、`option`、`shift`
![[Pasted image 20240619234433.png]]

## 4.1 command
![[Pasted image 20240619234506.png]]
在windows中按住ctrl点选多个文件的功能，在mac中变成了按住command点选多个文件

## 4.2 复制、拷贝、粘贴
![[Pasted image 20240619235016.png]]

## 4.3 mac复制-command+D
MacBook的复制是在文件旁边直接生成一个相同的文件副本，相当于在windows里面直接复制加粘贴同时完成。
![[Pasted image 20240619235152.png]]

## 4.4 mac拷贝-command+C
Mac的拷贝和windows的复制功能是一样的
![[Pasted image 20240619235252.png]]

## 4.5 mac粘贴-command+V
mac的粘贴和windows的粘贴功能是一样的

## 4.6 mac剪切
MacBook的剪切分别针对于文本和文件
### 4.6.1 文本
MacBook 针对文本的剪切工人和windows的剪切功能是一样的，command+X

### 4.6.2 文件
先command+C拷贝文件， 再到目标的文件夹，按住command + option + v

![[Pasted image 20240620122153.png]]
## 4.7 control
 control + 空格键：切换输入法
双击control键是语音输入

# 5. 点击文件右键
![[Pasted image 20240620122307.png]]
显示简介与windows的属性差不多
制作替身和windows的创建快捷方式是一样的

# 6. 快捷关闭
command + q，会快速退出当前应用程序

# 7. 强制关闭
![[Pasted image 20240620130606.png]]
点击苹果logo选择强制退出
![[Pasted image 20240620130652.png]]
![[Pasted image 20240620130713.png]]选择要退出的程序

还可以通过活动监视器来关闭软件
![[Pasted image 20240620215754.png]]
选择要关闭的软件，再点击上面的叉就关闭了

# 8. 一键预览
选择一个文件，再按一下空格键，就可以实现一键预览
![[Pasted image 20240620215952.png]]

# 9. mac自带的截图功能
按住shift+command+3：直接全图截屏
按住shift+command+4：屏幕出现十字架
按住shift+command+4+空格：截取特定的窗口
按住shift+command+5：出现下面的图标，前三个就是上面的三种，后面是录制完整屏幕和录制区域屏幕![[Pasted image 20240620220227.png]]

# 10. 聚焦搜索
点击菜单栏右上角的放大镜或者使用快捷键command+空格![[Pasted image 20240620220427.png]]

聚焦搜索不仅可以打开文件，还可以打开已经安装的应用程序、网页、书签、历史记录
![[Pasted image 20240620220621.png]]

# 11. 安装程序
## 11.1 app store
直接安装

## 11.2 浏览器
下载dmg文件，相当于windows里的exe文件
![[Pasted image 20240620220712.png]]
打开dmg文件就相当于给mav挂载了一个磁盘，此时访达和桌面会多个一个磁盘
![[Pasted image 20240620220908.png]]
等使用完成之后，可以推出磁盘
安装就是将文件QQ移动到appications中

如果出现下面的情况：
![[Pasted image 20240620221156.png]]
这是苹果出于安全性考虑的限制
此时需要打开系统便好设置 -> 安全与隐私
在终端输入：`sudo spctl --master-disable`，此时安全与隐私就出现了任何来源
![[Pasted image 20240620221613.png]]

# 12. 卸载软件
在启动台中长按需要删除的软件，再点击上面的叉叉就可以了
但是有一些软件会颤抖，但是没有叉叉，这时候就需要到访达到菜单中，在应用程序中找到你要删除的软件本体，右键移到废纸篓

# 13. 磁盘清理
	付费的：CleanMyMac
	 免费：柠檬清理


# 14. 访达-mac文件管理
访达类似于windows的资源管理器
文件一般分为：![[Pasted image 20240620222256.png]]

有时接收导入的文件 或者 程序生成的文件， 会被mac自动识别放入到对应的文件中
![[Pasted image 20240620223512.png]]

mac里是没有windows那样有我的电脑，如果非要找一个，那么就是访达中的磁盘选项Macintosh HD
![[Pasted image 20240620223719.png]]
系统和资源库是存放系统和系统软件配置文件的地方，最好不要动。
应用程序是程序本身存放的位置。
用户文件夹存放着用户各自的文件。
mac不分区

![[Pasted image 20240620224105.png]]

将mac拖入win硬盘时，发现拖入不进去，这是由于mac使用的是apfs磁盘格式，而windows使用的是ntfs
![[Pasted image 20240620225953.png]]

![[Pasted image 20240620230050.png]]

## 14.1 mac自带的备份-时间机器
但是当我使用T7 shield不行，可能是磁盘格式的问题

## 14.2 去到上层文件夹
不要点击这个键，这个是返回上一步操作
![[Pasted image 20240621144326.png]]

要点击前往 -> 上层文件夹 或者 快捷键command+上方向键
![[Pasted image 20240621144420.png]]

## 14.3 整理文件
![[Pasted image 20240621144756.png]]

## 14.4 打开第二个文件夹
方法一：在访达中按command+t，会新建一个标签页
![[Pasted image 20240621145427.png]]

方法二：
选择要打开的第二个标签页，选择在新标签页中打开
![[Pasted image 20240621145743.png]]

当有两个标签页的时候，就可以按command+n，或者直接拖拽出来，这样就有两个访达页面

## 14.5 新建文件夹
当想将多个文件放入一个新的文件夹时，可以直接右键
![[Pasted image 20240621150329.png]]

## 14.6 多个文件重命名
框选所有的文件，然后按右键点击重新命名
![[Pasted image 20240621150556.png]]
选择格式再自定格式内容
![[Pasted image 20240621150626.png]]

## 14.7 删除文件
可以右键移到废纸篓

或者完全删除快捷键：command + option + 删除键
![[Pasted image 20240621150722.png]]

## 14.8 撤回还原
command +z 
