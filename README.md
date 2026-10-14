# yangxinke.top

DeepSeek 余额桌面宠物的官方下载页。

- 站点：<https://yangxinke.top/>
- 页面：`index.html`
- 安装包：`download/DeepSeekPet-Setup-v1.0.0.exe`
- 便携版：`download/DeepSeekPet-Portable-v1.0.0.zip`

## 这个仓库是什么

一个纯静态的软件下载落地页，没有任何构建步骤、没有任何依赖。
`CNAME` 文件里的 `yangxinke.top` 告诉 GitHub Pages 用哪个自定义域名提供服务。

## 更新安装包

1. 把新的 exe 放进 `download/`，文件名里的版本号一起改
2. 改 `index.html` 里对应的下载链接和「约 XX MB」文案
3. 提交推送即可

## 本地预览

```bat
python -m http.server 8000
```

然后打开 <http://127.0.0.1:8000/>。
