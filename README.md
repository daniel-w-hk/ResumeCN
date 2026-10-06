# 王明康个人简历｜内地求职版

网站：https://daniel-w-hk.github.io/ResumeCN/

纯简体中文，不区分求职方向；求职意向为供应链、运营与商业分析。不展示个人所在地。

## 维护

- 网站文案：`content/`；无需维护其他语言目录。
- 页面样式：`src/app/globals.css`。
- 单页简历源码：`resume/Mingkang-Wang-CV-CN.tex`。
- 网站下载文件：`public/downloads/Mingkang-Wang-CV-CN.pdf`。
- Excel 练习：`public/downloads/Excel-Salary-Analysis.xlsx`。
- 页面路径：`/ResumeCN/`，由 `site-variant.json` 控制。

本地安装依赖后运行 `npm run dev`，默认访问 `http://localhost:3000/ResumeCN/`。上传 main 分支后会自动部署 GitHub Pages。

更新简历时，在编辑器中编译 XeLaTeX 源码，并将生成 PDF 替换到下载目录。保留姓名、联系方式与真实教育背景，不在个人资料中填写所在地。
