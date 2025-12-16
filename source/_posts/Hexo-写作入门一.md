---
title: Hexo 写作入门一
date: 2025-11-30 17:44:27
tags:
  - Hexo
---

Hexo 文章更新流程

1. 新建文章

```yaml
hexo new "文章标题"
```

作用：新建一个文章文件，并指定文章标题

作用: 在 source/\_posts/ 目录下创建一个新的文章文件

2. 修改文章内容
   在 source/\_posts/ 目录下找到对应的文章文件
   使用文本编辑器打开并修改内容
   保存文件

3. 清理旧缓存

```yaml
hexo clean
```

作用: 删除之前生成的静态文件和缓存，确保重新生成时不会有旧数据残留

4. 生成静态文件

```yaml
hexo generate
#或简写为
hexo g
```

作用: 生成静态文件，将修改后的文章内容转换为 HTML 文件

5. 本地预览

```yaml
hexo server
#或简写为
hexo s
```

作用: 启动本地服务器，在浏览器中预览修改后的文章效果

6. 部署到 GitHub Pages

```yaml
hexo deploy
#或简写为
hexo d
```

作用: 将生成的静态文件部署到 GitHub Pages 上，使修改后的文章内容生效

补充:
也可以一次性执行三个命令

```yaml
hexo clean && hexo generate && hexo server
```

或

```yaml
hexo clean
hexo generate
hexo server
```
