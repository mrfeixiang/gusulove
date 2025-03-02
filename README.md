# Gusu Love Story - 姑苏爱情故事

这是一个以立达中学为背景的互动故事游戏。玩家将通过选择不同的选项，与角色 Sue 互动，探索友情、学术合作或感情线索，逐步解锁多样的剧情分支和结局。游戏设计了丰富的分支剧情、特殊事件以及成就系统，带来沉浸式的体验。

[立即游玩 Gusu Love Story](https://mrfeixiang.github.io/gusulovestory/) 👈 *游戏链接*

## 游戏特性

- 🌟 多重分支剧情，随玩家的选择展开不同故事
- 👭 与 Sue 的多样互动，发展独特的角色关系
- 🎯 多样的结局，每一个选择都会影响你的故事走向
- 🏫 以立达中学为背景，充满校园生活气息

## 游戏玩法

1. 阅读故事文本
2. 从提供的选项中选择一个
3. 根据你的选择，故事将沿不同方向发展
4. 尝试探索所有可能的结局！

## 可能的关系发展

- **学术伙伴**：共同学习，一起参加竞赛
- **知己**：分享内心想法，讨论未来梦想
- **暗恋**：发展更深层次的感情

## 本地运行

如果您想在本地运行游戏：

1. 克隆此仓库
   ```
   git clone https://github.com/yourusername/lidalove.git
   ```

2. 打开 `index.html` 文件即可开始游戏

## 技术栈

- HTML5
- CSS3
- JavaScript (原生)

## 如何贡献

欢迎提交 issue 或 pull request，一起完善这个故事！您可以：

1. 添加新的故事分支
2. 丰富现有的结局
3. 改进用户界面
4. 修复 bug

## 未来计划

- [ ] 添加更多分支剧情
- [ ] 增加背景音乐
- [ ] 添加角色立绘
- [ ] 实现存档系统

## 许可证

本项目采用 [MIT 许可证](https://opensource.org/licenses/MIT) 开源。

---

Made with ❤️ by [Your Name](https://github.com/yourusername)

# 在GitHub Pages上设置姑苏爱情故事

## 步骤 1: 组织您的仓库

您的仓库应该有以下结构:
```
gusulovestory/
├── index.html
├── game.js
├── README.md
```

所有三个文件都已在您的仓库中，这很完美。

## 步骤 2: 创建 GitHub Pages 站点

1. 前往您的GitHub仓库
2. 点击"Settings"标签
3. 滚动到"GitHub Pages"部分（或在左侧菜单栏中点击"Pages"）
4. 在"Source"下，选择"Deploy from a branch"
5. 选择"main branch"（或者如果您使用的是"master"分支）
6. 点击"Save"

GitHub现在会提供一个网址，您的网站将在那里发布（URL为`https://mrfeixiang.github.io/gusulove/`）。

## 步骤 3: 检查您的网站

- 等待几分钟让GitHub部署您的网站
- 访问提供的URL以确保一切正常工作
- 测试您的游戏功能

## 步骤 4: 自定义域名（可选）

如果您想使用自定义域名:
1. 在GitHub Pages设置中输入您的自定义域名
2. 在您的域名提供商处设置适当的DNS记录
3. 在您的仓库中添加一个包含您域名的CNAME文件

## 疑难解答

如果您的网站没有出现:
- 确保index.html在根目录中
- 检查是否在GitHub Pages设置中选择了正确的分支
- 等待几分钟，因为GitHub Pages部署可能需要一些时间
- 检查您的仓库设置中GitHub Pages部分是否有任何错误

如果您的游戏不起作用:
- 打开浏览器开发者工具(F12)检查JavaScript错误
- 确保game.js文件的路径正确
- 验证所有文件名与代码中的引用匹配
