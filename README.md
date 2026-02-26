# 第一次部署

#hexo fluid主题
创建新文章的方法

  方法 1：使用 Hexo 命令（推荐）

  在项目根目录下运行：

   cd D:\Documents\github\ly.github.io
   npx hexo new "文章标题"

  这会在 source/_posts/ 目录下自动创建一个新的 Markdown 文件，模板会包含基本的 Front
  Matter（标题、日期等）。

  方法 2：手动创建文件

  直接在 D:\Documents\github\ly.github.io\source\_posts\ 目录下创建一个新的 .md
  文件，文件格式如下：

   ---
   title: 文章标题
   date: 2026-02-26 20:00:00
   tags: 标签1, 标签2
   categories: 分类
   cover:  # 可选：封面图片URL
   ---
   这里是文章正文内容

  发布步骤

  创建文章后：

   # 生成静态文件
   npx hexo generate

   # 本地预览（可选）
   npx hexo server

   # 部署到 GitHub Pages
   npx hexo deploy

✦ 