这是一个基于Jekyll搭建起来的博客环境，仅用于个人的学习记录之用。

### 搭建环境

```
1、 操作系统：windows10
2、 版本管理：github桌面版
3、 需要环境：Ruby、Python
4、 博客工具：Jekyll
5、 评论插件：友言 (仅一段带uid的JS代码)
6、 代码高亮：pygments(基于Python)
7、 音乐插件：虾米播播
8、 视频插件：优酷、YouTube
 ```
 1. 高亮代码插件的使用  
     {% highlight ruby linenos %}  
         编写高亮代码  
     {% endhighlight %}  
 2. 虾米播播插件单曲的使用  
     {% xiamiplayer 1775595262/singlePlayer.swf %}
     到[虾米播播的主页](http://www.xiami.com/widget/isingle?spm=0.0.0.0.wPvgsq)选择要下载的歌曲生成`code`，然后你可以看到其中flash链接类似下面的**http://www.xiami.com/widget/127353892_1775595262/singlePlayer.swf**选择复制粘贴*1775595262/singlePlayer.swf*即可在你的博客张添加这首歌曲，但是单曲是无法自动播放的。   
 3. 虾米播放列表的使用
    {% xiamiplayerlist 2070331,1775595262,1769167647,136064,1774917404,1774054136,1772001102,2131688,1772130323,378181,_235_346_FF8719_494949_0/multiPlayer.swf %}
     和虾米播播插件单曲一样，你只需要复制flash代码下的下划线后全部的内容就可以了。下划线的之前的1775595262是我的虾米播播的唯一id。  
 4. 优酷插件的使用  
    {% youku XMTQ4OTU3MjE5Mg==/v.swf %}
