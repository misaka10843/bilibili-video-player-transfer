# bilibili-video-player-transfer
# 如何使用html调用bilibili官方播放器
首先需要获取视频的aid和cid  
   1.怎么获取呢？  
   2.在b站视频页中查看网页源码  
   3.搜索字符:aid  
   4.就可以看见aid，bid和cid了  
   5.然后将aid和cid粘帖到对应位置就可以啦  

 然后使用iframe标签
 <iframe src="http://player.bilibili.com/player.html?aid=av号&amp;cid=cv号&amp;page=1&amp;as_wide=1&amp;high_quality=1&amp;danmaku=0" > </iframe>  
 其中，danmaku这个参数也可以调整:
 1为默认开启，0为默认关闭  

# 扩展  
其实还可以使用其他标签调整播放器，一些调整方法可以看index.html
