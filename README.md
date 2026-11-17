# FAIRWAY EV · 高尔夫球车宣传网站

- **[打开网站](https://senicks.github.io/fairway-ev/)**
- **[中文整体规划与图片来源](https://senicks.github.io/fairway-ev/plan.html)**

通过 GitHub Pages 公开部署。网站与源码均可直接查看。

## 自己维护网站

打开需要修改的文件，点击铅笔编辑，保存并提交到默认分支后，GitHub Pages 会自动重新发布。一般需要等待几分钟，可在 Actions 查看部署状态。

- `index.html`：英文文案、栏目与页面结构。
- `style.css`：颜色、字体与手机端样式。
- `app.js`：车型弹窗、场景切换与咨询表交互。
- `plan.html`：中文规划页。
- `assets/`：图片和图标。替换同名图片即可更新素材。
- `.nojekyll`：使用普通静态文件直接发布。

可在 Settings → Pages 查看部署地址与发布来源。图片、样式和脚本采用相对路径，支持当前项目站点地址。

## 本地预览

```sh
python3 -m http.server 4173
```

打开 http://localhost:4173 。不需要安装依赖或构建。

## 内容说明

FAIRWAY EV 是演示品牌。图库图片用于参考，不代表实际产品、客户或品牌背书。图片出处见网站页脚 Photo credits 和中文规划页。

咨询表只在浏览器内生成可下载需求文件，不向销售发送信息。正式使用需补充真实品牌、车型、参数和联系方式。

演示版保留 noindex；公众可通过链接访问，但暂不开放搜索收录。

## 其他副本

- [Gitee 源码副本](https://gitee.com/limingshang/fairway-ev)
- [Sites 展示副本](https://fairway-ev-showcase-1117.ai-rd.chatgpt.site)

在 GitHub 修改会自动更新 GitHub Pages，但不会自动同步 Gitee 和 Sites。
