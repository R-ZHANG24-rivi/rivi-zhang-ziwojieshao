# RIVI ZHANG · NEW PLAYER JOINED

腾讯新闻小游戏板块 · 新人自我介绍网页。

> 主题：像素风新人角色档案 / 新队友载入页面
> 视觉参考：[gt-mechanik.com](https://gt-mechanik.com/)（白底 + 亮粉 + 亮绿 + 荧光黄）

## 预览

页面已通过 GitHub Pages 部署：
`https://r-zhang24-rivi.github.io/rivi-zhang-profile/`

## 本地运行

单文件 HTML，不依赖任何框架或外网资源。直接双击 `index.html` 即可打开，或启动本地静态服务器：

```bash
python3 -m http.server 8000
# 打开 http://localhost:8000
```

## 目录结构

```
.
├── index.html          # 单文件 HTML/CSS/JS 全部内联
├── images/             # 配图资源
│   ├── 自我介绍配图01.jpg
│   ├── 情绪合成器*.png
│   ├── 递归星辰*.png
│   ├── 手绘*.png
│   └── 唱歌/阿卡/滑雪/攀岩/潜水/算卦.jpg
└── README.md
```

## 页面结构

1. **00 Start Screen** – 角色载入 + 大标题打字机
2. **01 Character Profile** – 角色档案
3. **02 Learning Path** – 成长路线（江大 → 清美）
4. **03 Previous Maps** – 已探索地图（字节 / 阿里）
5. **04 Project Gallery** – 作品简介 + 早期插画存档
6. **05 Status Panel** – 技能雷达图
7. **06 Footprints** – 我的足迹（中国地图 + 国外标签）
8. **07 Inventory** – 背包与兴趣爱好
9. **08 Team Invite** – 组队邀请

每个板块卡片可 **点击进入详情弹层**，详情中展示完整图集。

## 修改指南

- 配色：见 `index.html` 开头 `:root` 变量
- 文案：直接搜索对应中文修改
- 雷达图数据：搜 `radarData`
- 详情页图片：搜 `MODAL_DATA`，修改对应板块 `imgs` 数组
