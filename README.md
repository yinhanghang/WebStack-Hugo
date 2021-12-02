# Hugo 版 WebStack 主题

本项目是基于**纯静态**的网址导航网站 [Hugo](https://gohugo.io/) 主题。

来自[https://github.com/shenweiyan/WebStack-Hugo](https://github.com/shenweiyan/WebStack-Hugo)

# 安装

```
1.安装hugo，可以设置环境变量，也可以使用绝对路径执行
2.新建文件夹作为站点目录，命令行窗口（CMD）进入。
3.执行，在当前目录创建站点
	hugo.exe  new site ./
4.进入themes目录，克隆仓库，执行
	git clone git@github.com:yinhanghang/WebStack-Hugo.git
5.文件说明及操作
	1.将exampleSite目录中的文件移到站点目录。选择替换
		content：about目录下可以修改about.md，其他没必要修改
		data：webstack.yml文件配置网站的内容
			  friendlinks.yml文件配置友情链接
		config.toml文件配置站点信息
	2.除了layouts和static都可以删掉
6.启动，在站点目录进入命令行窗口，执行
	hugo.exe server --theme=WebStack-Hugo
会出现提示：一般是127.0.0.1:1313可以启动服务
		
```

```
themes目录文件树：
WebStack-Hugo
    +---exampleSite
    |   +---content
    |   |   +---about
    |   |   \---post
    |   \---data
    +---layouts
    |   +---partials
    |   \---_default
    \---static
        \---assets
            +---404
            |   +---css
            |   +---img
            |   \---js
            +---css
            |   \---fonts
            |       +---elusive
            |       |   +---css
            |       |   \---font
            |       +---font-awesome
            |       |   +---css
            |       |   +---fonts
            |       |   +---less
            |       |   \---scss
            |       +---fontawesome
            |       |   +---css
            |       |   \---fonts
            |       +---glyphicons
            |       +---linecons
            |       |   +---css
            |       |   \---font
            |       \---meteocons
            |           +---css
            |           \---font
            +---images
            |   +---logos
            \---js
            
            
            
            
```

# 个性化

1.图片的修改：根据config.toml文件，或者直接到themes\WebStack-Hugo\static\assets\images目录下修改

2.一些文字，可以在config.toml文件中修改。

3.图标修改，浏览器使用F12寻找名字到themes\WebStack-Hugo\layouts文件中修改html文件

4.其他一些信息都建议到themes\WebStack-Hugo\layouts中查找修改



###  主题演示地址

- [https://bioitee.com](https://bioitee.com)

- [https://shenweiyan.github.io/WebStack-Hugo](https://shenweiyan.github.io/WebStack-Hugo)

- [hugo_webstack](https://serverless-page-bucket-x58n26ro-1304440070.cos-website.ap-shanghai.myqcloud.com/)

  

