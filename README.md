# 96syh.github.io

GitHub Pages 博客仓库。当前配置看起来基于 Gmeek/GitHub Issues 博客模式：通过仓库配置和 issues 内容生成静态博客页面。

## 当前内容

```text
.
├── .github/             # GitHub Actions 或博客生成相关配置
├── backup/              # 备份目录
├── docs/                # 生成后的静态页面
├── blogBase.json        # 博客基础数据
├── config.json          # 博客配置
└── README.md
```

## 配置文件

`config.json` 当前包含博客标题、副标题、头像和 Gmeek 版本配置：

```json
{
  "title": "Blog Title",
  "subTitle": "Blog description",
  "avatarUrl": "https://github.githubassets.com/favicons/favicon.svg",
  "GMEEK_VERSION": "last"
}
```

## 使用建议

- 修改 `config.json` 中的标题、副标题和头像地址。
- 如果使用 issues 写文章，保持 issue 标题、标签和正文格式稳定。
- 推送前检查 `docs/` 中生成页面是否符合预期。

## 当前状态

仓库已具备 GitHub Pages 博客的基础结构，但内容还比较少。后续可以补充个人介绍、项目索引和技术文章。

