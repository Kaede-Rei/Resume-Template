# Markdown Resume 模版

基于 Markdown 格式的简历模板，配备优化的 Typora PDF 导出主题

## ✨ 特点

- 采用 Markdown 格式，便于编辑和版本管理
- 提供优化的 PDF 导出主题，适合打印和电子分发
- 包含完整的简历结构模板
- 支持自定义样式和内容

## 📁 项目结构

```
.
├── resume.md                               # 简历模板文件
├── README.md                               # 项目说明文档
└── typora-theme/                           # Typora 主题文件
    ├── phycat-pdf.css                      # PDF 导出主题（主文件）
    └── phycat-pdf/                         # 主题资源文件夹
        ├── LXGWWenKai-Regular.ttf          # 字体文件
        ├── Cascadia-Code-Regular.ttf       # 字体文件
        └── phycat.pdf.css                  # PDF 导出主题（资源文件）
```

## 🚀 快速开始

### 1. 安装主题

找到 Typora 的主题文件夹：

- Windows：`C:\Users\你的用户名\AppData\Roaming\Typora\themes`
- macOS：`~/Library/Application Support/abnerworks.Typora/themes`
- Linux：`~/.config/Typora/themes`

也可以在 Typora 中通过 `文件` → `偏好设置` → `外观` → `打开主题文件夹` 访问

将 `typora-theme` 文件夹中的 `phycat-pdf.css` 文件和 `phycat-pdf/` 文件夹复制到 Typora 主题文件夹中，然后重启 Typora

### 2. 编辑简历

使用 Typora 打开 `resume.md`，根据模板结构填写个人信息、技术栈、项目经历等内容；在编辑时选择 `Phycat Pdf` 主题（`主题` 菜单 → `Phycat Pdf`）

### 3. 导出 PDF

完成编辑后，点击 `文件` → `导出` → `PDF`，选择保存位置即可生成 PDF 格式的简历文件（导出偏好设置中页面大小为 A4）

## 📝 简历模板说明

模板包含以下部分：

- 个人信息：姓名、联系方式、教育背景等基本信息
- 技术栈：编程语言、框架、工具等技术能力
- 项目经历：项目背景、职责和核心工作内容
- 综合特质：个人特点和优势

可根据实际需要调整模块内容

## 🎨 主题说明

本项目使用的 PDF 导出主题基于 [Phycat 主题](https://github.com/sumruler/typora-theme-phycat) 进行了优化，主要改进包括：

- 优化 PDF 导出时的页面布局
- 调整字体大小和行距
- 改善打印效果
- 提高不同设备上的显示一致性

## 💡 使用说明

- 照片：将个人照片放在与 `resume.md` 同级目录，并在简历中引用
- 图标：模板使用 Emoji 图标，可根据需要替换或删除
- 内容长度：建议简历控制在 1-2 页内
- 链接：可添加 GitHub、博客等外部链接

## 🔧 自定义样式

如需自定义主题样式，可用文本编辑器打开 `phycat-pdf.css` 或 `phycat-pdf/phycat.pdf.css`，修改 CSS 样式（如颜色、字体、间距等），保存后在 Typora 中重新加载主题

## 📄 许可证

本项目采用 MIT License，详见 [LICENSE](./LICENSE)

由于本项目包含基于上游主题的修改内容，分发和再发布时请保留许可证与版权声明

## ⚠️ 免责声明

本项目按“现状”提供，不对求职结果、排版在所有环境中的一致性或第三方软件行为作担保

## 🙏 致谢

主题基于 [sumruler](https://github.com/sumruler) 的 Phycat 主题修改
