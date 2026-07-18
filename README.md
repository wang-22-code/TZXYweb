# 泰州学院宣传网页

这是一个无构建依赖的单文件静态宣传页，入口文件是 `index.html`。CSS 和 JS 已经内联，部署时只需要上传这一个文件。

## 本地预览

直接双击 `index.html` 即可预览。也可以在目录中启动任意静态服务器：

```powershell
python -m http.server 8080
```

然后访问 `http://localhost:8080`。

## 部署

把 `index.html` 上传到静态托管空间根目录即可。

适用平台：Nginx、Apache、GitHub Pages、Netlify、Vercel、Cloudflare Pages、学校服务器静态目录等。

页面引用了泰州学院官网图片资源，部署环境需要能访问 `https://www.tzu.edu.cn`。

## 数据来源

- 泰州学院官网《学校简介》，2026 年 2 月版：https://www.tzu.edu.cn/8/list.htm
- 泰州学院官网“校园风光”栏目：https://www.tzu.edu.cn/12/list.htm
