# 常用命令

### 新建一篇博文

```
hexo new  博客标题
```

### 本地预览

```
hexo cl; hexo s
```

### 清除缓存

```
hexo clean
```

### 推送至Git仓库

```
hexo cl; hexo g; hexo d
```

### 更新追番数据

```
hexo bangumi -u
```

### 更新追剧数据

```
hexo cinema -u
```

### 删除数据命令

```
hexo bangumi -d
```

```
hexo cinema -d
```

# serv00清理服务器

### 强制终止所有进程

```
pkill -kill -u 用户名
```

### 俢改根目录权限

```
chmod -R 755 ~/*
```

### 俢改隐藏文件目录权限

```
chmod -R 755 ~/.*
```

### 删除非隐藏文件和文件夹

```
rm -rf ~/*
```

### 删除所有隐藏文件和目录

```
rm -rf ~/.*
```
