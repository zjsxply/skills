# Skills 仓库

这是一个面向任意兼容 Skill 机制代理的自定义 skills 仓库。

英文说明见 [README.md](README.md)。

## 安装方式

本仓库可通过官方 `npx skills` CLI 安装。

先查看仓库中有哪些 skill：

```bash
npx skills add zjsxply/skills --list
```

安装本仓库里的 skill：

```bash
npx skills add zjsxply/skills --skill semantic-scholar-library-feed
```

如果你想把它安装到全局作用域：

```bash
npx skills add zjsxply/skills --skill semantic-scholar-library-feed -g -y
```

说明：

- 默认安装到当前项目作用域。
- 使用 `-g` 可安装到全局作用域。

## 当前仓库中的 Skills

| Skill | 功能 | 适用场景 |
| --- | --- | --- |
| `semantic-scholar-library-feed` | 面向用户的 Semantic Scholar 账号读取 Research Feed、查看私有 Library 文件夹、向文件夹添加论文，并根据 arXiv ID 等标识解析论文记录。 | 浏览或导出 feed 结果、查看已保存论文、比较文件夹内容、更新某个 library folder，以及把稳定标识映射到 Semantic Scholar 论文记录。 |
| `url-citation-search` | 通过反向搜索 URL 变体、标题、slug 与镜像页面，并在 PDF 或 HTML 中核实参考文献，查找引用某个给定网址的正式论文和预印本。 | 查询哪些论文引用了一篇博客、文档页、项目页、演示页，或其他常规引文数据库不易覆盖的网页内容。 |
