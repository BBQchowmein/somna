# SOMNA

一个伪装成助眠品牌的滚动恐怖网站。

直接用现代浏览器打开 `index.html`，无需构建，也无需服务器。

- 慢慢往下滚。页面会随着滚动逐渐改变，最后三分之一是另一种东西。
- 声音默认关闭。右下角的 **声音 关** 会开启合成环境声、心跳和最后那一下；建议戴耳机。
- 最后一屏的 **离开** 会重置整个体验。

## 内容提示

这是一件恐怖作品，包含闪光、跳吓；开启声音后还有合成音效。访问者开启系统的“减少动态效果”时，会跳过全屏跳吓。

## 部署成网址

最快的方式：打开 [Netlify Drop](https://app.netlify.com/drop)，把整个 `somna` 文件夹（或 `somna-site.zip`）拖进去，等它生成一个 `https://xxx.netlify.app` 链接。注册/登录后可以改站点名并长期保留。

也可以把 `index.html` 和 `assets/hannya.jpg` 一起传到 GitHub 仓库根目录，然后在仓库的 Settings → Pages 里选择 `main` 分支和 `/ (root)`，得到 `https://用户名.github.io/仓库名/`。更新时重新上传或重新拖一次文件夹即可。

不要只传 `index.html`，同级的 `assets/hannya.jpg` 必须一起传，否则最后的惊吓会没有面具。

## 素材署名

最后跳吓中的般若面具照片由 **Jl FilpoC** 拍摄，采用 **CC BY-SA 4.0** 授权，来自 [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Hannya,_British_Museum.jpg)。图片经过裁剪和调色。页脚也包含署名。

其余部分——版式、文案、苍白面孔的绘制与动画、颗粒、合成音效——均为本项目原创。
