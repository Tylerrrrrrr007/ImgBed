# ImgBed

## 点击图片查看不了？用cdn加速的地址cdn.jsdelivr.net/gh/替换raw.githubusercontent.com

https://**raw.githubusercontent.com**/Tylerrrrrrr007/ImgBed/main/Obsidian/-OK-brightgreen.svg
![raw](https://raw.githubusercontent.com/Tylerrrrrrr007/ImgBed/main/Obsidian/-OK-brightgreen.svg)

换成
https://**cdn.jsdelivr.net/gh**/Tylerrrrrrr007/ImgBed@main/Obsidian/-OK-brightgreen.svg
![jsdelivr](https://cdn.jsdelivr.net/gh/Tylerrrrrrr007/ImgBed@main/Obsidian/-OK-brightgreen.svg)

## 其他地址：来源油猴镜像，如fastgit

https://**raw.githubusercontent.com**/Tylerrrrrrr007/ImgBed/main/Obsidian/-OK-brightgreen.svg
![raw](https://raw.githubusercontent.com/Tylerrrrrrr007/ImgBed/main/Obsidian/-OK-brightgreen.svg)

换成————https://**raw.fastgit.org**/Tylerrrrrrr007/ImgBed/main/Obsidian/-OK-brightgreen.svg
![fastgit](https://raw.fastgit.org/Tylerrrrrrr007/ImgBed/main/Obsidian/-OK-brightgreen.svg)

## 详解

💣github是国外站，开启cdn加速服务会快很多，比如我用手机/电脑上传到github以后，对比一下github用户界面/github服务器/github经过cdn加速的链接：

　　1.链接是https://github.com/……后面一堆是用户名/仓库名/blob/main（或者main/文件夹名）/文件名

　　例，https://github.com/Tylerrrrrrr007/ImgBed/blob/main/s_Mosaic_8_14_15.jpg

　　2.它本身在服务器的地址是https://raw.githubusercontent.com……/后面一样（不同点是没有了blob这个路径）

　　例，https://raw.githubusercontent.com/Tylerrrrrrr007/ImgBed/s_Mosaic_8_14_15.jpg

　　3.cdn加速是把前面替换成cdn.jsdelivr.net/gh/（同样没有了blob这个路径，也没有了main这个路径）

　　例，https://cdn.jsdelivr.net/gh/Tylerrrrrrr007/ImgBed/s_Mosaic_8_14_15.jpg

　　于是markdown语言显示是

![标题]删这五个字(https://cdn.jsdelivr.net/gh/Tylerrrrrrr007/ImgBed/s_Mosaic_8_14_15.jpg)

如下

![标题](https://cdn.jsdelivr.net/gh/Tylerrrrrrr007/ImgBed/s_Mosaic_8_14_15.jpg)
