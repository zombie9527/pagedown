修改的地方：
	
	Markdown.Converter.js
		723行 定义_DoVideos函数
		731行 定义writeVideoTag函数
		537行 调用_DoVideos函数

	Markdown.Sanitizer.js
		31行 添加video_white
		33行 添加tag.match(video_white)

	Markdown.Editor.js
	修改的行号
		1505
		1870
		1864
		41
		73
		119
		1262
		doLinkOrImage改名为doLinkOrImageOrVideo

添加了快捷键 ctrl+M 插入video标签

![视频按钮](https://github.com/JYFiaueng/pagedown/blob/master/videobutton.png)
![show](https://github.com/JYFiaueng/pagedown/blob/master/show.png)

2017年3月10日 22:30:41