# 组织部文档中心

## 如何贡献

### 步骤 1：克隆仓库并创建分支

```bash
git clone git@github.com:Organization-Department/Documents.git
git checkout -b your-branch-name
```

### 步骤 2：添加或修改文档

在 `docs/` 目录下创建或编辑 `.md` 文件：

- **部门介绍**：放在 `docs/introduction/` 目录下
- **工作日志**：放在 `docs/logs/` 目录下

在 `mkdocs.yml 中配置文件路径`

### 步骤 3：提交更改

```bash
git add docs/your-file.md
git commit -m "添加/更新: 文件说明"
git push
```

### 步骤 4：提交 PR

在 GitHub 上提交 Pull Request，等待审核合并即可。

