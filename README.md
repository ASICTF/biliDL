# biliDL

biliDL_0.2为测试版本，极大提升下载速度，但网络差也更容易坏页。

增加多线程下载、优化处理方式、页码补零
<br/>
程式会自动创建downloads文件夹，付费内容可在购买登录后下载

运行后根据提示操作 例如漫画章节页url如下：

https://manga.bilibili.com/mc28386/526774

则mc号为28386 章节号为526774
<br/>
如要下载的内容中包含付费章节，则需输入SESSDATA，请按以下方式获取SESSDATA

1.在浏览器中登录biliibli漫画，并购买好相应的章节

2.找到Cookie中的SESSDATA，复制其内容。

【主站与漫画站SESSDATA一致，若漫画站无法找到，请于主站寻找】
【退出后重新登录SESSDATA会变动，请按上述说明更新】
【网络不稳定时，请单话下载防止坏页】
<br/>
如图所示![image.png](https://i.loli.net/2020/10/26/RBhmXZdl9jJC7pw.png)

源码：https://github.com/LaMP57/BilibiliMangaDownload

图片解析部分来自 https://github.com/flaribbit/bilibili-manga-spider
