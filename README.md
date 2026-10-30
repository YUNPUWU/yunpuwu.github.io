# yunpuwu.github.io

Yunpu Wu 的个人博客：<https://yunpuwu.github.io>

使用 [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy) 主题，推送到 `main` 分支后由 GitHub Actions 自动构建发布（约 1–2 分钟）。

## 分类

每篇文章选一个主分类，写法必须和下表完全一致（大小写、空格、`&`）。可以在后面加一个子分类，例如 `[AI Agents, LangGraph]`。

| 分类（front matter 里的写法） | 中文 |
| --- | --- |
| `Machine Learning & NLP` | 机器学习和自然语言处理 |
| `AI Agents` | AI 智能体 |
| `Python` | Python |
| `AI & Business` | AI 和商业 |
| `Quant` | 量化 |

这 5 个分类定义在 `_data/categories.yml`，会按顺序一直显示在网站的 Categories 页面上，还没有文章的显示为 0 posts。要增加、删除或改名分类，就改这个文件。

## 目录

| 路径 | 用途 |
| --- | --- |
| `_posts/` | 已发布的文章，文件名 `YYYY-MM-DD-英文短标题.md` |
| `_drafts/` | 草稿，不会发布；`post-template.md` 是新文章模板 |
| `assets/img/posts/` | 文章配图 |
| `_tabs/about.md` | About 页面 |
| `_config.yml` | 网站设置（标题、副标题、头像、时区） |
| `_data/categories.yml` | Categories 页面上固定显示的分类及顺序 |
| `_data/contact.yml` | 侧边栏底部的联系图标 |
| `_layouts/categories.html` | 自定义的 Categories 页面（一般不用改） |

## 发一篇新文章

1. 复制 `_drafts/post-template.md` 的内容。
2. 在 `_posts/` 新建 `YYYY-MM-DD-英文短标题.md`，粘贴并修改标题、日期、分类、标签和正文。
3. 提交（Commit）。日期不要写成未来时间，否则这篇不会发布。
