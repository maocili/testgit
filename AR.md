## 睿视可实现AR操作

[睿视文档]

*  在线视频/音频/[视频]/模型动画 控制

    设置视频循环播放和全屏播放,模型可设置循环播放
    
    可设置触发事件(如模型被点击时):
    
    使视频播放、停止暂停、重新播放

* 显示/隐藏控制

    设置触发事件(如视频播放时)：

    使素材 显示或隐藏

* 自定义动画

    设置触发事件

    素材移动坐标轴

* 手势控制

    可控制素材 移动 旋转 缩放

* 图文信息控制

    在浏览器内打开一段文字

* 打开网页

    打开一个网页

* 全景图控制

    设置触发事件

    打开一个全景图


## [视+] 
    
[AR导游]

有在线开发平台，可以快速展示效果

目前不支持用户交互（拖动 缩放 点击）

模型 obj

需要下载 视+ app


## [easyAR]

SDk 需要二次开发

支持用户交互

云识别图库更高的识别率

模型使用unity

支持人体姿态识别

支持手势识别

WebAR （小程序）：

1. 支持的动画文件格式只有FBX、 DAE,、 JSON，现在使用的ASCII码FBX， FBX格式文件需要ASCII和二进制两种文件，最好可以给到源工程文件，3dmax/maya/blender导入导出有不兼容的地方需要手动调整。

2. 动画部分，虚拟节点，控制器等不支持。

Android/IOS


### 4.0 测试版（现3.0）

1. 实时建图 定位
2. 支持稀疏空间地图（单地图2000平米）
3. 多人共享 
4. 稠密空间地图


## [Dumix]
### [入门教学]
| 基础物料 |         素材要求  |
|----------|------------------------------------------------------------------------------- |
|   2D素材      |        表现为⼀个贴有静态图⽚的平⾯，导出格式为jpg或png                       |
| 识别图| 识别图是一张用于扫描触发AR场景，并实现跟踪效果的图片，识别图格式为jpg。[识别图要求]      |
| 音频| 表现为在AR场景中播放一段音频，音频素材导出格式为mp3。制作软件参考：Cool Edit等。          |
|   视频      |        表现为一个播放视频的平面，视频素材分为普通视频和带透明通道的透明视频，格式均为Mp4。普通视频正常导出即可。透明视频在制作的时候需参考规范如下： [百度AR视频制作规范]              |
|   模型      |        POD或者GLTF( 推荐使用maya和3dsmax)                                    |
|             |FBX导POD工具      [密码：y1ks]                                                |
|             |FBX导GLTF工具      https://github.com/facebookincubator/FBX2glTF/releases     |
|             |                                                                              |

SDk 需要二次开发
### SDK支持：
1. Android SDK
2. IOS SDK
3. Unity SDK

Unity SDK支持发布Android和iOS应用，并且手机需要保持联网状态。

|功能|	Android|	iOS|	Mac|	Window|
|----|--------|-------|-------|----------|
|单目Slam|	✓ |	✓	  |      |          |	
|2D跟踪|	✓ |	✓	  |✓     |         ✓|
|本地识图|	✓|	✓	  |       |          |	
|手势识别|	✓|	✓     |       |          |		
|云端识图|	✓|	✓	  |      ✓|     	✓|
|肢体识别|	✓|	✓		
|IMU|	✓|			

## [网易洞见]

SDK 正在申请






[视频]:https://ravvar.cn/helps?i=15
[睿视文档]:https://ravvar.cn/helps
[视+]:http://www.sightp.com/product/lightapp.html
[AR导游]:http://www.sightp.com/case/110.html
[easyAR]:https://www.easyar.cn/
[Dumix]:https://dumix.baidu.com/content#/
[入门教学]:https://ai.baidu.com/docs#/DuMixAR-MakeContent-GettingStarted/top
[识别图要求]:https://ai.baidu.com/docs#/DuMixAR-MakeContent-Practise/78bcde56
[百度AR视频制作规范]:http://ar-fm.cdn.bcebos.com/upload/content-document/20180625/037190b088a70a05ae8a87d29e594c43_video_2.0.pdf
[密码：y1ks]:https://pan.baidu.com/s/1orzb1JHoW262kgZJ-XFWuQ
[网易洞见]:https://ar.163.com