# 使用插件[ckplayer](http://www.ckplayer.com/manualX/)

## 它的特点

- 代码简单
- 兼容低版本IE
- 兼容PC和移动端播放
- 播放体验较好

##踩坑
- [删除右上角水印的方法](http://www.ckplayer.com/manualX/27.html)

## Demo
```
<!DOCTYPE html>
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
    <title>ckplayer插件</title>
    <script type="text/javascript" src="ckplayer/ckplayer/ckplayer.js" charset="UTF-8"></script>
</head>
<body>
    <div id="video" style="width: 100%; height: auto;"></div>
    <script type="text/javascript">
        var videoObject = {
            container: '#video', //容器的ID或className
            variable: 'player', //播放函数名称
            poster: 'ckplayer/material/poster.jpg', //封面图片
            autoplay: true,
            video: 'http://www.w3school.com.cn/example/html5/mov_bbb.mp4'
            //http://www.w3school.com.cn/example/html5/mov_bbb.mp4
        };
        var player = new ckplayer(videoObject);
    </script>
</body>
</html>
```
</br>
---
# 另
- [用htlm5怎样实现网页中插入优酷视频并居中显示](https://jingyan.baidu.com/article/375c8e1999b52025f2a229a6.html)