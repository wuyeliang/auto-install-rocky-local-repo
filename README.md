
制作源步骤：

创建目录

```
mkdir /opt/CentOS7.5-Mini-Rocky
```

下载rpm包

```
yum install  `cat rpm-list `    --downloadonly  --downloaddir=/opt/CentOS7.5-Mini-Rocky
```


安装createrepo

```
yum install -y createrepo
```


生成源


```
createrepo /opt/CentOS7.5-Mini-Rocky
```


