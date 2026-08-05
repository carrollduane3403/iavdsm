众腾官网下载【Q-——333307——】众腾官网下载【 辋芷《888yx●vip》 】
众腾官网下载【Q-——333307——】众腾官网下载【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整指南（2025最新）

> 还在为服务器费用发愁？想拥有一个完全属于自己的技术博客？本教程手把手教你用 GitHub Pages 免费搭建高性能博客，百度收录友好，SEO 天然优势，让内容被更多人看到。

 为什么选择 GitHub Pages？

- 零成本永久托管：无需购买服务器，绑定域名即可访问
- 全球 CDN 加速：加载速度远超传统虚拟主机
- Git 版本控制：文章修改历史一目了然，协作更轻松
- 百度收录优化：自动生成 sitemap，配合 SEO 配置快速收录

 搭建四步走

 第一步：创建 GitHub 仓库（名称必须为 username.github.io）

登录 GitHub 新建仓库，仓库名填写 `你的用户名.github.io`，选择 Public 并勾选 Add a README file。这一步是为了开启 Pages 服务的基础。

 第二步：本地环境安装（Node.js + Git）

前往 Node.js 官网下载 LTS 版本，一路默认安装。Git 安装完成后，右键文件夹选择 `Git Bash Here`，依次输入以下命令验证：

```bash
node -v && npm -v && git --version
```

 第三步：Hexo 博客初始化（含百度SEO配置）

```bash
npm install hexo-cli -g
hexo init my-blog && cd my-blog
npm install
hexo s
```

访问 `http://localhost:4000` 看到默认页面，说明成功。接着安装百度收录必备插件：

```bash
npm install hexo-generator-sitemap --save
```

在 `_config.yml` 中追加：

```yaml
sitemap:
  path: sitemap.xml
```

 第四步：部署脚本配置（一键发布）

修改 `_config.yml` 底部 deploy 参数，安装部署工具后：

```bash
npm install hexo-deployer-git --save
hexo clean && hexo g && hexo d
```

 推送百度收录（实测有效）

1. 访问 [百度站长平台](https://ziyuan.baidu.com) 验证站点（推荐文件验证）
2. 添加 `sitemap.xml` 路径，等待自动爬取
3. 每天提交 `https://你的域名/` 首页链接，三天内可见收录

 互动引导

你在搭建过程中遇到最卡壳的环节是哪一个？ 欢迎在评论区留言，我会在当天逐一回复帮你排查问题。

如果这篇文章帮到了你，点赞收藏不迷路，持续更新「百度收录优化」系列教程。

相关推荐：


<img src="https://i.postimg.cc/GmJjX0dw/zhongteng-00003.png" />

相关推荐：


<img src="https://i.postimg.cc/bwHRmX8M/zhongteng-00001.png" />
相关推荐：


<img src="https://i.postimg.cc/J7Dc9HM1/zhongteng-00015.png" />
相关推荐：


<img src="https://i.postimg.cc/k5JvZjg3/zhongteng-00013.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
