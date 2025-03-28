# Suiyuan Studio | Top Global Team

## Overview

本项目是遂愿工作室的官方网站，旨在展示全球顶尖导师团队，提供免费咨询服务，帮助学生实现学业突破。网站设计简洁、响应式，并包含以下主要模块：

- **Navigation Bar**：展示工作室 logo 与品牌口号，并提供“导师团队”和“免费咨询”的链接。
- **Cover Section**：使用精美封面图展示整体风格。
- **Tutors**：动态展示教师卡片，点击卡片可展开详细信息。
- **Footer**：分为四个区域，分别展示工作室 logo、了解我们、联系我们以及关注我们（微信、小红书二维码）信息。

## Features

- **Responsive Design**：基于 Bootstrap 5 构建，适配各种设备（桌面、平板、手机）。
- **Dynamic Content Loading**：教师信息通过 JSON 数据动态加载，支持点击展开/收起详细信息。
- **Interactive Footer**：关注我们部分支持鼠标悬停显示二维码，提供直观的社交媒体入口。
- **Free Hosting**：项目使用 GitHub Pages 部署，免费对外展示。

## Usage Instructions

1. **本地预览**
   - 克隆仓库：
     ```bash
     git clone https://github.com/Psz111/Suiyuan-site.git
     ```
   - 进入项目目录后，直接用浏览器打开 `index.html` 文件预览网站。
   - 或使用本地服务器（例如 VS Code 的 Live Server 插件）以便于调试。

2. **修改与定制**
   - **教师信息**：编辑 `data/teachers.json` 更新教师数据。
   - **图片资源**：替换 `assets/images` 目录下的图片，以符合你的品牌需求。
   - **样式调整**：根据需求修改 `css/style.css` 中的样式，例如颜色、间距、动画效果等。

3. **部署**
   - 将仓库设为公共，并使用 GitHub Pages 进行部署。具体步骤：
     1. 在 GitHub 仓库页面点击 **Settings**。
     2. 在侧边栏选择 **Pages**。
     3. 选择发布分支（通常是 `main` 或 `master`）和根目录，然后保存。
     4. 等待几分钟后，访问 `https://yourusername.github.io/your-repository` 查看在线网站。
   - 如需使用自定义域名，请参考 GitHub Pages 文档配置 DNS。

## To-Do List

- [ ] 优化教师卡片动画和展开/收起效果
- [ ] 添加更多详细内容页面（例如教师详细介绍/工作室介绍）
- [ ] 优化图片尺寸及加载速度
- [ ] 优化背景栏
- [ ] 多设备多浏览器测试与兼容性调整

## License

本项目采用 [MIT License](LICENSE)。

## Contact

如有任何问题或建议，请通过以下方式联系我们：
- **邮箱**: Suiyuan.education@gmail.com
- **电话**: +86 18760413248
