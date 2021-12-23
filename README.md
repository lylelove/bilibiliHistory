# 爬取哔哩哔哩历史——基于selenium、pyecharts库

![bilibiliHistory](https://socialify.git.ci/lylelove/bilibiliHistory/image?description=1&language=1&name=1&owner=1&theme=Light)

### 使用

1.下载bilibiliHistory.py

1.配置依赖

2.填写数据

3.运行等待

#### 1.下载bilibiliHistory.py

#### 2.配置依赖

- selenium
- [pyecharts](https://github.com/pyecharts/pyecharts)

a.安装python

win10及以上使用组合键win+r调出运行，打开cmd，在控制台输入```python3```直接在微软商店安装即可。

安装完成后通过输入```python3 -v```查看是否安装正常。

b.安装pip

下载地址：https://pypi.python.org/pypi/pip

一般python都集成了pip，可以在cmd中键入```pip```进行验证。

c.安装selenium

通过```pip install selenium```安装

d.下载浏览器驱动

下载链接：https://www.selenium.dev/downloads/

本人使用的是chrome浏览器，chrome浏览器也可以用这个地址下载：http://chromedriver.storage.googleapis.com/index.html。接下来以chrome浏览器为例。

下载驱动后将驱动（chromedriver.exe）放到Chrome的安装路径下，例如 C:\Program Files (x86)\Google\Chrome\Application  ，然后把改路径加入到环境变量Path中。我的电脑->属性->高级系统设置->环境变量--System变量Path增加 ;C:\Program Files (x86)\Google\Chrome\Application

e.查看是否安装成功

在cmd键入```python3```,之后键入```from selenium import webdriver```,未报错即为安装成功。

f.安装[pyecharts](https://github.com/pyecharts/pyecharts)

#### 扫码使用

运行py文件后扫码后等待片刻。

#### 效果

![](https://s2.loli.net/2021/12/23/czI1YkyeMxrN9F2.png)
