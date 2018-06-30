# Serial-port-debugging-assistant
**PyQt5 写的 GUI 串口调试助手**  
> 下载 exe 可执行文件直接看最后

## GUI 展示

![](https://github.com/Oslomayor/Markdown-Imglib/blob/master/Imgs/PyQt5-SerialPort.png?raw=true)

## 文件说明

跟代码有关的有3个文件  

1. SerialPort.ui

   可以看到 它是 ui 后缀，此文件是 Qt Designer 设计的图形界面文件

2. Ui_SerialPort.py

   把 ui 文件转换成 Python 代码，得到 Ui_SerialPort.py ，此文件被后面的逻辑文件调用

3. Call_Ui_SerialPort.py

   这个是逻辑文件，业务逻辑的处理都写在这里面  

整个的项目文件流程:  
先设计完成界面 -> 得到 ui 文件 -> 再把 ui 文件转换为 Python 界面代码 -> 逻辑文件调用界面代码 -> 完成业务逻辑 -> Pyinstaller 打包成 exe 发布

## 环境依赖

1. Python 3.6 (Python 解释器, 运行 Python 必备)
2. Qt Designer (用于设计界面，生成 ui 文件)
3. Eric 6 (将 ui 文件转换为 Python 代码并开发逻辑文件)

点击查看 [PyQt5 安装配置](https://github.com/Oslomayor/Hey-PyQt5)

## 最终文件
Windows 版本 exe 可执行文件 [下载](https://github.com/Oslomayor/PyQt5-Serial-Port/releases/download/V1.0/PyQt5-SerialPort.zip)


## 微信公众号

​                                                              扫码关注 CrazyEngineer

![](https://github.com/Oslomayor/Markdown-Imglib/blob/master/Imgs/CrazyEngineer.jpg?raw=true)

