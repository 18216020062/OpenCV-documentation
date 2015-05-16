OpenCV文档
==============
使用OpenCV过程中需要查看函数用法，当你不能访问[opencv官网文档](http://docs.opencv.org/index.html)时，可以下载本项目，部署在本地进行查看。

## 下载

点击页面右侧**Download Zip**下载，或：
```bash
git clone https://github.com/zchrissirhcz/freezing-octo-adventure.git
```

## 本地部署

最便捷的方式是用Python开启一个简易HTTP服务器：你需要安装Python。

转到文档根目录，比如doc_genBySphinx/目录，在cmd或bash中输入：
```bash
python -m SimpleHTTPServer 9090
```
然后在浏览器中打开localhost:9090使用文档

## 文档说明

doc_genBySphinx目录是sphinx风格的文档（从opencv-3.0.0beta版用sphinx生成）

doc_genByDoxygen目录是doxygen风格的文档（从opencv-3.0.0rc1版用doxygen生成）

