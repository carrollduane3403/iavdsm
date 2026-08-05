恒耀主管官网【Q-——333307——】恒耀主管官网【 辋芷《888yx●vip》 】
恒耀主管官网【Q-——333307——】恒耀主管官网【 辋芷《888yx●vip》 】

 从0到1搭建个人技术博客：GitHub Pages + Hexo 完整指南

> 还在为写技术文章没有合适平台发愁？手把手教你用 GitHub Pages 免费搭建专属博客，零成本、高自定义、SEO友好，一次配置终身受益。

 为什么选择 GitHub Pages 托管博客？

很多开发者选择在掘金、CSDN 等技术社区发文，但个人博客的独立性和品牌感是第三方平台无法替代的。GitHub Pages 提供免费静态托管，配合 Hexo 框架，可以轻松实现：

- 完全掌控：无广告、无审核、数据归属自己
- SEO优化：自定义域名 + 独立收录权重，利于搜索引擎抓取
- 版本管理：文章即代码，天然支持 git 协作与回滚

 三步完成博客搭建

 第一步：创建 GitHub 仓库

登录 GitHub，新建仓库，命名为 `你的用户名.github.io`。注意：仓库名必须与用户名完全一致，否则无法启用 Pages 服务。在 Settings → Pages 中，将 Source 设置为 `main` 分支，保存即可看到博客默认地址。

 第二步：本地安装 Hexo 环境

确保电脑已安装 Node.js 和 Git，打开终端执行：

```bash
npm install -g hexo-cli
hexo init my-blog
cd my-blog
npm install
hexo server
```

浏览器访问 `localhost:4000` 即可预览默认主题。将主题文件夹替换为 Next、Fluid 等热门主题，修改 `_config.yml` 中的站点标题、关键词、描述，这些字段直接影响搜索引擎收录效果。

 第三步：部署到 GitHub

安装部署插件并一键推送：

```bash
npm install hexo-deployer-git --save
hexo clean && hexo generate && hexo deploy
```

推送成功后，访问 `你的用户名.github.io` 查看线上效果。建议在百度站长平台提交站点，并生成 sitemap.xml 加快收录。

 小红书式互动引导

你目前是在用第三方平台写作，还是已经搭建了个人站？评论区聊聊你遇到的坑，比如主题配置报错、自定义域名解析失败等——我会挑选高频问题专门写一期排错指南。

 进阶优化建议

完成基础搭建后，可以进一步研究：
- 自定义域名：购买便宜域名后，在仓库 Settings 中添加 CNAME 记录
- 图片懒加载：hexo-lazyload-image 插件提升页面速度
- 百度SEO适配：安装 hexo-generator-baidu-sitemap 并主动推送链接

搭建成本不到1小时，但长期带来的独立流量价值远超投入。如果觉得这篇教程有用，点赞收藏转发给需要的朋友，后续会更新主题美化系列。

相关推荐：

https://github.com/robinsonjoseph6/akekff/blob/main/Th%E1%BB%83%20thao%20%E2%9A%BD%EF%B8%8F%EF%BC%9A%E6%81%92%E8%80%80app_%E6%8C%96%E8%97%A4%E6%BD%98%E5%9F%94%E5%A0%B5numnt.md

<img src="https://i.postimg.cc/nr9NhNLr/hengyao-00005.png" />

相关推荐：

https://github.com/robinsonjoseph6/akekff/commit/014db7d32a13a10d839f65200d6360a84f51606c

<img src="https://i.postimg.cc/766pp58P/hengyao-00001.png" />
相关推荐：

https://github.com/duraneric9105/ouckrz/blob/main/C%E1%BB%91c%20Games%20%F0%9F%A5%8A%EF%BC%9A%E6%81%92%E8%80%80%E5%A8%B1%E4%B9%90%E6%B3%A8%E5%86%8C_%E6%95%96%E6%8C%87%E5%BC%A5%E6%9C%B4%E4%B9%93igagt.md

<img src="https://i.postimg.cc/rmmvvDX9/hengyao-00002.png" />
相关推荐：

https://github.com/duraneric9105/ouckrz/commit/bbd7ec085577d70b9b207513e800bc16a33311b2

<img src="https://i.postimg.cc/SQXK9s22/hengyao-00008.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
