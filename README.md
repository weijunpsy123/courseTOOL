# 课程达成度计算器

海南师范大学心理学院 刘韦君

这是一个可直接部署到 GitHub Pages 的本地网页工具。

## 使用

打开 `index.html` 即可使用。

## GitHub Pages 部署

1. 新建一个 GitHub 仓库。
2. 将本目录中的所有文件上传到仓库根目录。
3. 在仓库页面进入 `Settings` → `Pages`。
4. `Build and deployment` 选择 `Deploy from a branch`。
5. Branch 选择 `main`，目录选择 `/root`。
6. 保存后等待 GitHub 生成访问链接。

## 文件说明

- `index.html`：网页主文件
- `course-models.js` / `course-models.json`：课程达成度示例数据
- `lib/jszip.min.js`：Excel 导出依赖
