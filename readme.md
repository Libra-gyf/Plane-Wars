### pygame简介
##### pygame的安装
- python --version  查看安装的Python版本，
- pip --version  查看安装的pip版本，
    - Python 2.7.9 + 或 Python 3.4+ 以上版本都自带 pip 工具。
- 升级pip命令： python -m pip install --upgrade pip 
- 打开命令行窗口输入 python -m pip install --user pygame，然后回车。
##### pycharm 配置第三方库
- 通过路径【File】→【Settings】→【Project】→【Project Interpreter】进行配置
##### pygame 的使用
 - 第一步是把 pygame 导入到 Python 程序中，
    - import pygame
    - 然后需要引入 pygame 中所有常量
    - from pygame.locals import *
    - 在经过初始化以后，就可以正常的使用pygame