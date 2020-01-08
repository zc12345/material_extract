# material_extract

extract image/audio/video materials from installed game directory. 

从游戏安装目录/安装包中提取图片/音频/视频资料等。

## 1. 视觉小说系列

### 1.1 5pb系列（Steins; Gate等）

1. [mpk格式音频和CG文件提取](https://github.com/rdavisau/sg-unpack)
2. [bk2格式视频文件查看：RAD Video Tools](http://www.radgametools.com/)

### 1.2 key社系列（Clannad等）

1. g00格式图片文件：g00cnv.exe
2. [nwa格式音频文件提取](https://github.com/hasenbanck/nwatowav)
3. nwa 转 MP3：M_AudioConverter_1.24.setup

### 1.3 KrKr引擎

1. [Krkr资源提取](https://github.com/xmoeproject/KrkrExtract)

### 1.4 [Renpy引擎](https://www.renpy.org/)

1. [rpa格式资源文件提取](https://github.com/Lattyware/unrpa)
2. 代表作品：Doki Doki Literature Club（心跳文学部），Everlasting summer（永恒之夏）

### 1.5 其他

1. 通用提取工具: Crass
2. CG和立绘合成工具：GalPhotoAuto


## 2. 手游（Unity）

### 2.1 Arknights（明日方舟）

#### 1. 资源提取

1. 将安装包apk文件改名rar或者zip等压缩格式，然后解压缩，音频立绘等资源在$/assets/AB/$目录下
2. 使用[AssetStudio](https://github.com/Perfare/AssetStudio)等unity提取工具查看$.ab$格式资源文件并进行解包
3. 使用GalPhotoAuto进行立绘合成
4. 使用[waifu2x](http://waifu2x.udp.jp/)或者[MoePhoto Image Toolbox](http://hgalgame.com/?p=610)等提高分辨率（waifu2x的效果好像更好一些）


## 3. 参考

1. [Ren’Py 引擎游戏文件解包与游戏汉化](https://doge.im/tools/extract-and-localize-renpy-game-files.html)
2. [关于现版本 明日方舟资源提取（CG，立绘，BGM） ](https://k1rito.github.io/posts/2873917882/)
3. [AssetStudio v0.10.0.76](https://www.perfare.net/1194.html)
4. [收集的exe文件](https://pan.baidu.com/s/1nSJ5grlSpyyrKJ-A7lu9MQ) 提取码：r3fw
5. [从零开始的立绘拆包教程](https://blog.csdn.net/Conyrol/article/details/96781786)
6. [Asset Studio下载]((https://ci.appveyor.com/project/Perfare/assetstudio/branch/master/artifacts))
7. [文件分析工具SpaceSniffer](http://www.uderzo.it/main_products/space_sniffer/download.html)

