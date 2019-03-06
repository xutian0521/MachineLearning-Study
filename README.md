## 机器学习-的学习项目

#### vscode windows开发环境搭建
1. 安装微软出的官网Python插件：Python
2. 安装Python官网的sdk： https://www.python.org/downloads/release/python-372/

3. 设置Python一些环境变量
``` ini
Path:
D:\Program Files (x86)\Python\Python37-32 //python 安装路径
D:\Program Files (x86)\Python\Python37-32\Scripts //pip 等脚本安装路径

```
>配置好环境变量 执行`python -V` 检查是否安装正确
``` bash
python ##进入Python命令行
exit() ##退出Python命令行
```
4. 配置vscode 
1. `ctrl+shift+p` , 输入`Python: select interpreter`, 选择你安装的Python的SDK路径 .vscode/settings.json =>`"python.pythonPath": "D:\\Program Files (x86)\\Python\\Python37-32\\python.exe"`
2. 安装ptvsd模块 (调试模板) cmd 输入命令安装： `pip install ptvsd` 
>**这里注意pip 可执行文件在`D:\Program Files (x86)\Python\Python37-32\Scripts` 目录下,需要配置环境变量, 还有安装命令在cmd里执行, 不要在python 执行**

#### 调试
1. 选着vscode 默认初始配置：`Python: Current File (External Terminal)`

#### 参考资料
1. VSCode搭建Python环境及远程调试方法 ：https://blog.csdn.net/zzzzllll2006/article/details/83014940
