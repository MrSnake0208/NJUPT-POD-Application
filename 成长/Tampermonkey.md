## 是什么？

Tampermonkey俗称油猴，是一个可以安装脚本的插件。

> 脚本是一种可执行文件，它可以为你做很多事情
>
> 可以说你访问的所有网站，背后都是脚本的身影

而安装的这些脚本，它可以帮助你实现许多神奇的事情。

## 如何安装？

安装链接：[Tampermonkey - Microsoft Edge Addons](https://microsoftedge.microsoft.com/addons/detail/tampermonkey/iikmkjmpaadaobahmlepeloendndfphd)

点击上述链接，进去后点击「安装」即可，这时候在你浏览器的右上方会出现如下图标，那么说明你已经安装成功了

![image-20220401223047369](https://picture-1301432580.cos.ap-nanjing.myqcloud.com/blog/202204012230535.png)

## 脚本哪里找？

* [Greasy Fork - 安全、实用的用户脚本大全](https://greasyfork.org/zh-CN)
* [Github]([Greasy Fork - 安全、实用的用户脚本大全](https://greasyfork.org/zh-CN))

### Greasy Fork

![image-20220401223344727](https://picture-1301432580.cos.ap-nanjing.myqcloud.com/blog/202204012233770.png)

当你打开网页，映入眼帘的便是搜索框，在搜索框中输入你想搜索的脚本，如「文库」，然后点击右侧的放大镜，即可进行搜索

![image-20220401223433601](https://picture-1301432580.cos.ap-nanjing.myqcloud.com/blog/202204012234702.png)

在点击搜索后，展现在你眼前的便是脚本了，这时候挑选你需要的点击进去，便会进入脚本的详细说明页面，一般来说脚本的开发者会在该页面写一些说明，使用前一定要**看说明！！看说明！！看说明！！**

![image-20220401223517261](https://picture-1301432580.cos.ap-nanjing.myqcloud.com/blog/202204012235342.png)

这时候点击「安装此脚本」便会跳转到我们安装的Tampermonkey里，在这个页面也点击安装，至此一个脚本便已安装完成

![image-20220401223645932](https://picture-1301432580.cos.ap-nanjing.myqcloud.com/blog/202204012236963.png)

安装完成了，那如何使用呢？这里以我安装的「秒传链接」为例，在说明中开发者已经明确说明，这个脚本是应用于 pan.baidu.com，那么当我们打开 pan.baidu.com 时，便会发现右上角的小猴子旁边多了红色的数字，数字代表，在这个页面中，有几个脚本在运行，这边可以看到，我刚刚安装的「rapidupload-userscript」也在其中，并且是绿色的，表示它已经被开启了

![image-20220401223845635](https://picture-1301432580.cos.ap-nanjing.myqcloud.com/blog/202204012238667.png)

这里由于该脚本的开发者设置了弹窗，所以在页面上我可以看到弹窗，不一定所有脚本都有弹窗哦

![image-20220401223953009](https://picture-1301432580.cos.ap-nanjing.myqcloud.com/blog/202204012239065.png)

随后，在页面上方（或者任意地方）我就看到了网站原来不自带的按钮，说明脚本成功运行了，这时候就可以用了，脚本使用流程大抵如此。

如若在阅读后仍觉不懂，可以将未看懂的点告知编写团队，编写团队将会为你答疑解惑并对文档进行完善。

![image-20220401224031857](https://picture-1301432580.cos.ap-nanjing.myqcloud.com/blog/202204012240880.png)

### Github

Github是一个网站（在其他章节中我们会详细描述它是怎样的），会有很多大神在上面分享脚本，这上面有些脚本并不会在其他的找脚本的平台上被展示出来，但是其开发者可能会在其他网站上宣传其脚本，大多数都是指引你来这个平台。

接下来我以「[the1812/Bilibili-Evolved: 强大的哔哩哔哩增强脚本 (github.com)](https://github.com/the1812/Bilibili-Evolved)」为例，向大家展示如何使用它安装脚本。点击上面的链接，大家会看到如下界面，可能大家会一脸懵逼，这是啥啊？没关系，大家向下拉，只要是好的作者，一定会写说明的

![image-20220401224446536](https://picture-1301432580.cos.ap-nanjing.myqcloud.com/blog/202204012244655.png)

往下拉我们看到了这个（别问为什么这里面的字都镜像了，愚人节专供），开发者在里面写了很多内容，当然对于我们最重要的肯定是「安装」「设置」「文档站点」，点击相应的按钮，我们便会跳转到相应的位置

![image-20220401224518496](https://picture-1301432580.cos.ap-nanjing.myqcloud.com/blog/202204012302635.png)

这里以点击「安装」为例，文档向下跳转到「安装」部分，它这里面说要安装「Tempermonkey」和其他monkey，由于我们已教学如何使用Tempermonkey，便可以略去，下面看到作者写的注意事项，在详细阅读后，选择我们要安装的版本，点击「安装」

![image-20220401224645020](https://picture-1301432580.cos.ap-nanjing.myqcloud.com/blog/202204012246135.png)

欸嘿，你看，是不是又跳到了「Tempermonkey」？这时候点击安装，就安装好了，如果报错的话，关掉跳出来的页面，再点击安装，这样一般问题就都解决了，可以使用脚本了。

## 如何开关脚本？

当我们进入了「脚本」生效的网页时，右上角的猴子旁边会显示我们开了几个脚本，点击它便会出现如下画面

![image-20220401224933572](https://picture-1301432580.cos.ap-nanjing.myqcloud.com/blog/202204012249617.png)

绿色表示已开始，灰色表示未开启，假如我想关闭掉已开启的脚本，只需要点击其前面的按钮即可，反之亦然，记得点完后要刷新才能生效哦。

## 精品脚本推荐

这里不推荐一些可能产生不好影响的脚本，如需请自己查询

* [Bilibili-Evolved: 强大的哔哩哔哩增强脚本](https://github.com/the1812/Bilibili-Evolved)

* [知乎增强](https://greasyfork.org/zh-CN/scripts/419081-知乎增强)

* [CSDN/知乎/哔哩哔哩/简书免登录去除弹窗广告](https://greasyfork.org/zh-CN/scripts/428960-csdn-知乎-哔哩哔哩-简书免登录去除弹窗广告)