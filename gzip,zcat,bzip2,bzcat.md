###gzip 压缩文件

```
**gzip [-cdtv#] 文件名**

-c 将压缩的数据输出到屏幕上,可通过数据流重定向来处理
-d 解压缩的参数
-t 用来检验一个压缩文件的一致性，看看文件有无错误
-v 显示出原文件/压缩文件的压缩比等信息
-# 压缩等级,-1最快，压缩比最差，-9最慢，最好默认是-6

解压缩:
gzip -d filename

压缩并保留原来的文件,设置压缩等级为9级:
gzip -9 -c filename > filename.gz
```

###zcat 读取压缩文件

```
**zcat filename**
**on mac os: zcat < filename**
```

###bzip2

```
bzip2 [-cdkzv#] 文件名

-c 将压缩中产生的数据输出到屏幕上
-d 解压缩的参数
-k 保留原文件，不删除原始文件
-z 压缩参数
-v 显示出原文件/压缩文件的压缩比等信息
-# 压缩等级,-1最快，压缩比最差，-9最慢，最好默认是-6

解压缩:
bzip2 -d filename.bz2

压缩并保留原来的文件,设置压缩等级为9级:
bzip2 -9 -c filename > filename.bz2
```

###bzcat 读取bzip2压缩的内容

```
**bzcat filename**
```



