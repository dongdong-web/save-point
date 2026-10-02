# 存档点 · SAVE POINT v1.0

一个项目，承接原来的三个个人 H5：

## 1. 行动 PB
- 新建 / 编辑 / 删除挑战
- 计时型：越快越好、越久越好
- 次数型：越多越好
- 自动计算个人最佳 PB
- 历史成绩、单条删除
- 节律月历与按日记录
- 防止同时开启多个计时

## 2. 探索 · 走遍哈尔滨
- 随机抽取尚未探索街道
- Leaflet + OpenStreetMap 路线显示
- 高德查看
- 打卡 / 取消打卡
- 已走、剩余、已打卡道路总长度
- 街道图鉴与实时搜索
- 记录新打卡时间，进入统一时间线

## 3. 剧情 · 人生是一场 Galgame
- 新建、编辑、删除
- 事件 / 选择 / 结局 / 攻略 / 标签
- 全文搜索
- 全部 / 未完待续 / 已有结局筛选
- 标签筛选

## 4. SAVE POINT
- 人生纪日
- 本月存档轨迹
- 最近存档
- 快速手记
- PB / 探索 / 剧情统一时间线
- 全站 JSON 一键导出与恢复
- 旧 PB / citymap / life-is-galgame localStorage 自动迁移
- 支持导入旧项目 JSON
- PWA / iPad 主屏幕基础支持

## 必须复制的路网文件
原 `citymap/data/harbin-roads.json` 文件较大，没有打进压缩包。
请复制到新项目：

`data/harbin-roads.json`

如果不复制，代码也会尝试从原 citymap GitHub Pages 读取，但独立部署建议复制。

## 数据 key
新版统一使用：
`savePoint.unified.v2`

旧 key 仍会读取：
- `pb-race-data`
- `everyStreetHarbin.v1`
- `life-galgame-v1`

## 部署
把压缩包全部文件上传到一个 GitHub Pages 仓库根目录即可。
