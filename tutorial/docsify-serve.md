# docsify本地部署

在点击`clone or download`之前，确认本机是否有[git](https://git-scm.com/)与[node](https://nodejs.org/zh-cn/)生产环境若没有请点击下载，安装比较傻瓜化，一直点`下一步`或`next`即可

右击选择`git bash`在命令行中输入 `npm i docsify-cli -g`

![](https://raw.githubusercontent.com/loremwalker/fq-book/master/tutorial/imgpng/2018-05-24_225913.png)

点击`clone or download`接着再点击`DownloadZIP`下载压缩包

![](https://raw.githubusercontent.com/loremwalker/fq-book/master/tutorial/imgpng/2018-05-25_001210.png)

解压缩后进入到`fq-book-master/docs`目录中右击打开`git bash`输入`docsify init .`

![](https://raw.githubusercontent.com/loremwalker/fq-book/master/tutorial/imgpng/2018-05-25_004625.png)

打开`index.html`，在`repo`下方添加`lodaSidebar: true`并保存

![](https://raw.githubusercontent.com/loremwalker/fq-book/master/tutorial/imgpng/2018-05-25_005149.png)

接着使用`docsify serve`完成本地部署，在浏览器中输入`localhost:3000`即可看到效果

![](https://raw.githubusercontent.com/loremwalker/fq-book/master/tutorial/imgpng/2018-05-25_005409.png)



