# Iris Yuan · 个人作品集 (Portfolio)

跨境出海 × AI 电商 · 平台方（AliExpress / 得物）× 品牌方（SHEIN / 花西子）双视角

在线浏览：**https://irisyuan0926-blip.github.io/iris-portfolio/**

## 这个站点是什么

一个单文件双语作品集（`index.html`），面向**跨境供给策略 / 电商运营 / AI 赋能电商增长**方向的求职展示。

内容结构：

| 区块 | 说明 |
|---|---|
| Hero | 一句话定位 + 4 个关键指标 + 简历下载 |
| 奖项条 | ACC 黑客松、FDE AI 创作营、国际青年营、AI×纺织高研班 |
| 01 关于我 | 3 张核心竞争力卡 + 能力标签 + 职业路径时间线 + 教育背景 |
| 02 工作经历 | 4 段正式经历 + 1 段实习，卡片展开可见完整指标与打法 |
| 03 实操项目 | ①AI 电商提效「电商搞钱参谋」②出海策略探索（中东 GTM）③AI 落地应用（香木雅舍内容提效 demo） |
| 04 联系 | 邮箱 / 电话（同微信）/ LinkedIn |

## 技术说明

- 纯静态：一个 `index.html` + `assets/`，无构建步骤，双击即可本地预览
- 中英双语：右上角 EN / 中文 切换，`localStorage` 记忆选择
- 字体已本地化（`assets/fonts/`），不依赖 Google Fonts，国内访问不会掉字形
- 图片来源均为项目实拍/产品截图，已压缩到 1200–1600px 宽

## 目录

```
index.html          站点本体
resume.pdf          简历（首页「下载简历」）
assets/             项目图、头像、简历、字体
   fonts/           Sora / Lora（woff2，latin 子集）
```

## 本地修改

```bash
git clone https://github.com/irisyuan0926-blip/iris-portfolio.git
cd iris-portfolio
open index.html      # 直接改，刷新看效果
```

改完提交：

```bash
git add -A && git commit -m "update content" && git push
```

推送后 GitHub Pages 会自动重建，约 1 分钟后生效。

## 更新简历

替换 `resume.pdf` 即可，文件名保持不变，首页按钮会指向新文件。
