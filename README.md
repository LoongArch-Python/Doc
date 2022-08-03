## 所支持的架构
LoongArch平台
## loongson 社区网站
[龙芯社区网站](http://www.loongnix.cn/zh/)
## python 生态相关链接
[python 用户手册](http://docs.loongnix.cn/python/python.html)  
[python 仓库](https://pypi.loongnix.cn/loongson/pypi)
## 龙芯 python 如何仓库配置
```
loongson@loongson-pc:~$ mkdir -p ~/.pip  
loongson@loongson-pc:~$ touch ~/.pip/pip.conf  
loongson@loongson-pc:~$ cat ~/.pip/pip.conf  
[global]  
timeout = 60  
index-url = https://pypi.loongnix.cn/loongson/pypi  
extra-index-url = https://pypi.org/simple  
[install]  
trusted-host =   
    pypi.loongnix.cn  
    pypi.org  
```
****
<font color="Blue">本站点维护的软件包，主要是提供相关软件包的patch文件，不会随着上游版本发布进行更新。</font>
****
无论你是开发者或者用户，当你在 LoongArch 平台上执行 `pip3 install numpy`时，出现以下错误`#error Unknown CPU, please report this to numpy maintainers with
`那么你需要配置龙芯 python 仓库。
龙芯 python 仓库中包含大量的 wheel 二进制软件包，可以大大节省你下载和编译的时间。
仓库正以递归的方式不断的完善和增加，如您有需求欢迎在 issue 中留言，可要求我们在龙芯 python 仓库中添加指定的软件包或者软件包版本，我们也可以协助您完成构建或者开发过程中遇到的问题。
