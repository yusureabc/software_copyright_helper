#### 软著源代码辅助工具
指定目录 + 文件后缀，快速生成 docx 文件，批量变现利器！

#### 环境相关
开发环境：Ubuntu 16.04　Python 3.5.2

代码用了这个 python 包，需要安装一下，因为我开发机有 py2，所以 pip 的命令是 pip3
`pip3 install python-docx`

#### 使用命令
```
python3 helper.py /mnt/hgfs/www/test/java java,php 开发者工具平台_源代码
```

#### Params 说明
```
/mnt/hgfs/www/test/java    您的代码目录
java,php    您需要抽取的文件后缀，如果只需一个后缀只写 java 多个后缀请用 , 拼接
开发者工具平台_源代码    您要生成的 word 文件名，生成之后是这样 开发者工具平台_源代码.docx，  与代码在同一目录下
```