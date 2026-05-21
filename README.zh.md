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
| `awesome-repo-builder` | 创建面向特定主题的 awesome-list 仓库脚手架，包括精炼的 README、贡献规则、代理说明、URL 校验、许可证与可复用模板。 | 从主题、分类体系、收录标准和可选的种子条目出发，快速搭建一个可维护的精选资源目录。 |
| `image-to-text-pdf` | 将完成版位图图片转换为图片型 PDF，并额外嵌入可选中、可复制、可搜索的文字层，同时生成可视化检查版。 | 在保留文生图海报、视觉简历或图片优先版式原貌的同时，避免用 PPT、HTML 或 LaTeX 重新排版带来的脆弱性。 |
| `semantic-scholar-library-feed` | 面向用户的 Semantic Scholar 账号读取 Research Feed、查看私有 Library 文件夹、向文件夹添加论文，并根据 arXiv ID 等标识解析论文记录。 | 浏览或导出 feed 结果、查看已保存论文、比较文件夹内容、更新某个 library folder，以及把稳定标识映射到 Semantic Scholar 论文记录。 |
| `skill-market-publisher` | 为本地 skill 准备、校验并发布到公共 skill 市场、目录与注册表，结合已验证自动化流程与人工提交流程打包。 | 规划多市场发布、生成各市场 payload、核验当前提交入口、向已支持目标执行发布，以及为仍需浏览器提交的市场生成操作说明。 |
| `url-citation-search` | 通过反向搜索 URL 变体、标题、slug 与镜像页面，并在 PDF 或 HTML 中核实参考文献，查找引用某个给定网址的正式论文和预印本。 | 查询哪些论文引用了一篇博客、文档页、项目页、演示页，或其他常规引文数据库不易覆盖的网页内容。 |
