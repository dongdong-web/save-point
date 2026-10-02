# SAVE POINT · 存档点

个人 Life OS 首页。纯静态、无后端，可直接部署到 GitHub Pages。

## 部署
1. 新建公开仓库 `save-point`
2. 上传本压缩包内的全部文件到仓库根目录
3. Settings → Pages → Deploy from a branch
4. Branch 选择 `main`，目录选择 `/ (root)`
5. 等待 Pages 地址生成

## iPad
用 Safari 打开 GitHub Pages 地址 → 分享 → 添加到主屏幕。
之后从主屏幕进入，会以接近独立 App 的方式运行。

## 当前入口
- PB: https://dongdong-web.github.io/PB/
- 走遍哈尔滨: https://dongdong-web.github.io/citymap/
- 人生是一场 Galgame: https://dongdong-web.github.io/life-is-galgame/

## 数据
SAVE POINT 自己的“今日痕迹”和一句话记录使用 localStorage。
页面内可导出 JSON 存档，建议定期保存到 iCloud Drive。
注意：由于三个子项目位于不同 GitHub Pages 路径，浏览器安全边界下，工作台第一版不会直接读取它们各自的 localStorage。
