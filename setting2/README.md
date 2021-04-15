
### 左侧菜单栏文字大小调整


在Mac下如果你想修改你的VScode的侧边栏的字体大小，首先你的在你的Application中找到你的VSCode程序
然后使用Show Content打开安装包的内容
然后按照以下路径找到对应的文件：


右击APP图标/查看内容/Contents/Resoures/app/out/vs/workbench/workbench.desktop.main.css


通过文档编辑器打开这个文件，并且查找 “.part>.content”这个关键字


然后修改对应的那个px大小，重启你的VSCode转换，你就能修改你的侧边栏的大小