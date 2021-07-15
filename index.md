---
layout: default
---
<iframe frameborder="no" border="0" marginwidth="0" marginheight="0" width=330 height=86 src="//music.163.com/outchain/player?type=2&id=1387581250&auto=1&height=66"></iframe>

这是关于zld学习python中pygame的记录

# text 1
## num1
第一天，学习了有关于pygame的pip配置
### 配置

1.使用 win+r 开始运行
2.输入cmd
3.输入 pip install pygame 配置pygame
### 基础
导入所需的模块
import pygame, sys
导入所有pygame.locals里的变量（比如下面大写的QUIT变量）
from pygame.locals import *

初始化pygame
pygame.init()

设置窗口的大小，单位为像素
screen = pygame.display.set_mode((500, 400))

设置窗口标题
pygame.display.set_caption('Hello World')

程序主循环
while True:

    获取事件
    for event in pygame.event.get():
        判断事件是否为退出事件
        if event.type == QUIT:
            退出pygame
            pygame.quit()
            退出系统
            sys.exit()

     绘制屏幕内容

    pygame.display.update()



### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>zld</dd>
<dt>Born</dt>
<dd>2002</dd>
<dt>Birthplace</dt>
<dd>china</dd>
<dt>Color</dt>
<dd>blue</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
