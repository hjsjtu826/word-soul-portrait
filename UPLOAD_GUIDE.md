# 上传到GitHub的步骤

## 方法一：手动上传（推荐）

1. 在GitHub上创建新仓库：https://github.com/new
   - 仓库名：`word-soul-portrait`
   - 描述：`词魂肖像 - 给英文单词一张脸 | Word Soul Portrait - Give every word a soul`
   - 选择 Public
   - 不要勾选 "Add a README file"（我们已经有了）

2. 创建后，在本地仓库目录执行：

```bash
cd "/Users/jinghu/Library/Mobile Documents/com~apple~CloudDocs/self/DO市百家/AI高效办公/skills/word-soul-portrait-github"

git remote add origin https://github.com/hjsjtu826/word-soul-portrait.git
git branch -M main
git push -u origin main
```

## 方法二：GitHub Desktop

1. 打开 GitHub Desktop
2. File → Add Local Repository
3. 选择目录：`/Users/jinghu/Library/Mobile Documents/com~apple~CloudDocs/self/DO市百家/AI高效办公/skills/word-soul-portrait-github`
4. Publish repository

## 方法三：直接上传文件

1. 在GitHub上创建新仓库
2. 选择 "uploading an existing file"
3. 拖拽以下文件上传：
   - README.md
   - SKILL.md
   - examples/ 目录下的4张图片
   - scripts/ 目录下的4个脚本
   - references/ 目录下的2个文档
