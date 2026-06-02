# GitHub Pages Upload Notes

这个 `docs/` 文件夹已经整理成可直接发布的 GitHub Pages 静态网页。

推荐发布方式：

1. 把整个项目上传到 GitHub 仓库。
2. 进入仓库的 `Settings` -> `Pages`。
3. 在 `Build and deployment` 中选择 `Deploy from a branch`。
4. Branch 选择 `main`，Folder 选择 `/docs`。
5. 保存后等待 GitHub Pages 部署完成。

主要文件：

- `index.html`: 项目主页。
- `styles.css`: 页面样式。
- `assets/figures/`: 从论文 PDF 图转换出的高分辨率 PNG 图，以及 depth-map comparison 图。
- `assets/datasets/`: 数据集展示图片。
- `assets/paper/survey.pdf`: 论文 PDF。
- `assets/paper/citation.bib`: 项目页 BibTeX。
