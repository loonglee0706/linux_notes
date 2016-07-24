###tar
**压缩: tar -jcv -f filename.tar.bz2 被压缩文件或目录**
**查询: tar -jtv -f filename.tar.bz2**
**解压缩: tar -jxv -f filename.tar.bz2 -C 欲解压缩的目录**

```
-j bzip2的支持进行压缩/解压缩
-z gzip的支持进行压缩/解压缩
-p 保留备份数据原来的权限与属性，常用于备份(-c)重要的配置文件
```

```
仅解开单一文件
tar -jcv -f filename.tar.bz2 待解开文件名
```

```
打包目录 排除目录下某些文件
tar -jcv -f filename.tar.bz2 --exclude=排除的文件名
```

```
备份比某个时刻还要新的文件
tar -jcv -f filename.tar.bz2 \
> --newer-mtime="2008/09/29" 待备份文件
```
