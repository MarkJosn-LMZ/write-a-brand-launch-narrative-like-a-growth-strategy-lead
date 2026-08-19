# PetiLoop 展会 Deck 品牌规范

来源：`https://www.petiloop.com/` 的 2026-08-19 实际页面样式与计算后样式。

```css
:root {
  --bg: oklch(0.985 0.002 250);
  --surface: oklch(1 0 0);
  --fg: oklch(0.20 0.01 270);
  --muted: oklch(0.56 0.01 270);
  --border: oklch(0.93 0.004 250);
  --accent: oklch(0.657858 0.230920 17.074);

  --display-font: "Airbnb Cereal VF", "PingFang SC", "Hiragino Sans GB", "Microsoft YaHei", sans-serif;
  --body-font: "Geist Variable", "PingFang SC", "Hiragino Sans GB", "Microsoft YaHei", sans-serif;
  --mono-font: "JetBrains Mono", "SF Mono", Menlo, Monaco, Consolas, monospace;
}
```

视觉语言：近白底色与纯白内容面并置，深灰文字保持强对比；明亮红色只用于关键行动或结论；标题粗而直接、正文克制；大幅真实工作场景照片承担主要情绪表达；信息模块以细边线、8–12px 圆角和大留白组织，不使用重阴影或装饰性渐变。

- 首屏采用“大幅横向摄影 + 左下信息面板”的单一主视觉，人物与宠物处于真实工作环境。
- 标题使用 700 权重的现代无衬线中文，句子短、换行明确；正文控制在 2–3 行。
- 页面主要靠留白与细分隔线建立层级，卡片边界低对比，避免密集组件感。
- 红色强调色一屏最多出现两次，只用于主行动、重点结论或页码锚点。
- 产品信息使用简短英文系列名、中文能力名和真实场景描述的三层结构。
