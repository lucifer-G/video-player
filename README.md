# 影视播放器

一个纯静态 HTML 视频播放器，支持搜索、多线路切换、下载，可直接部署到 GitHub Pages。

## 功能

- 浏览 14万+ 影视资源（电影/电视剧/动漫/综艺）
- 按分类筛选
- 搜索影片
- 多线路切换（同一影片不同视频源）
- 选集播放
- 下载单集或整条线路
- 支持 m3u8/mp4 播放
- 移动端适配
- 可自定义 API 源

## 部署

### GitHub Pages (推荐)

1. 新建 GitHub 仓库（如 `video`）
2. 上传 `index.html`
3. Settings → Pages → Source: `main` → Save
4. 访问 `https://你的用户名.github.io/video`

### 本地运行

直接双击 `index.html` 用浏览器打开。

## 自定义 API

点击右上角 ⚙，输入你的 maccms API 地址：

```
https://你的域名/api.php/provide/vod/
```

## 数据源

默认使用公开的影视资源 API，数据来自网络。
