# pdf2word

60行代码实现多线程PDF转Word。
美中不足：需要自行整理文字格式。这个版本代码无法识别图片内容。

## 使用方法

* clone或下载项目到本地
```python
git clone git@github.com:simpleapples/pdf2word.git
```

* 进入项目目录，建立虚拟环境，并安装依赖

```python
cd pdf2word
pyvenv venv
source venv/bin/active
pip install -r requirements.txt
```

* 修改config.cfg文件，指定存放pdf和word文件的文件夹，以及同时工作的进程数
* 执行```python main.py```

**欢迎Star**

## Python私房菜

![](http://ww1.sinaimg.cn/large/6ae0adaely1foxc0cfkjsj2076076aac.jpg)

## License

采用 MIT 开源许可证
