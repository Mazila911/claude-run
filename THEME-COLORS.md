# Claude Run 浅色主题颜色方案

## 核心语义变量映射

基于当前深色主题中使用的 zinc 色系，映射到浅色方案：

| 语义变量 | 深色 (当前) | 浅色 (新增) | 用途 |
|----------|------------|------------|------|
| `--bg-page` | `#09090b` (zinc-950) | `#ffffff` (white) | 页面主背景 |
| `--bg-surface` | `#18181b` (zinc-900) | `#f4f4f5` (zinc-100) | 卡片/面板背景 |
| `--bg-surface-hover` | `#27272a` (zinc-800) | `#e4e4e7` (zinc-200) | 悬停态 |
| `--bg-elevated` | `#18181b` (zinc-900/80) | `#fafafa` (zinc-50) | 代码块/输入框 |
| `--bg-selected` | `rgba(6,182,212,0.3)` (cyan-700/30) | `rgba(6,182,212,0.15)` (cyan-100) | 选中项 |
| `--border-default` | `rgba(63,63,70,0.6)` (zinc-800/60) | `rgba(228,228,231,1)` (zinc-200) | 默认边框 |
| `--border-subtle` | `rgba(63,63,70,0.4)` (zinc-800/40) | `rgba(244,244,245,1)` (zinc-100) | 列表分割线 |
| `--border-strong` | `rgba(63,63,70,0.5)` (zinc-700/50) | `rgba(212,212,216,1)` (zinc-300) | 强调边框 |

| 语义变量 | 深色 (当前) | 浅色 (新增) | 用途 |
|----------|------------|------------|------|
| `--text-primary` | `#fafafa` (zinc-50) | `#18181b` (zinc-900) | 主文字 |
| `--text-secondary` | `#a1a1aa` (zinc-400) | `#52525b` (zinc-600) | 次要文字 |
| `--text-tertiary` | `#71717a` (zinc-500) | `#71717a` (zinc-500) | 辅助文字 |
| `--text-muted` | `#52525b` (zinc-600) | `#a1a1aa` (zinc-400) | 弱化文字 |
| `--text-heading` | `#e4e4e7` (zinc-200) | `#27272a` (zinc-800) | 标题 |
| `--text-body` | `#d4d4d8` (zinc-300) | `#3f3f46` (zinc-700) | 正文 |

## 功能色（深浅主题共用或微调）

| 颜色用途 | 深色 | 浅色 | 说明 |
|----------|------|------|------|
| User 气泡 | `blue-600/80` | `blue-500` | 用户消息 |
| User 气泡文字 | `blue-100` | `white` | |
| Assistant 气泡 | `cyan-700/50` | `cyan-50` (极浅青) | 助手消息 |
| Assistant 气泡文字 | `zinc-100` | `zinc-800` | |
| 链接 | `cyan-400` | `cyan-600` | |
| 代码 inline | `zinc-800/80 bg, cyan-300 text` | `zinc-100 bg, cyan-700 text` | |
| 代码块 | `zinc-900 bg, zinc-300 text` | `zinc-50 bg, zinc-800 text` | |
| Thinking 标签 | `amber-500/10 bg, amber-400 text` | `amber-50 bg, amber-600 text` | |
| Tool 按钮 | `slate-500/10 bg, slate-300 text` | `slate-100 bg, slate-600 text` | |
| 成功 result | `teal-500/10 bg, teal-400 text` | `teal-50 bg, teal-600 text` | |
| 错误 result | `rose-500/10 bg, rose-400 text` | `rose-50 bg, rose-600 text` | |
| Diff + 行 | `emerald-900/20 bg, emerald-300 text` | `emerald-50 bg, emerald-700 text` | |
| Diff - 行 | `rose-900/20 bg, rose-300 text` | `rose-50 bg, rose-700 text` | |
| ScrollToBottom | `zinc-200/90 bg, zinc-900 text` | `zinc-800 bg, zinc-50 text` | 反转 |

## 滚动条

| 属性 | 深色 | 浅色 |
|------|------|------|
| thumb | `#27272a` | `#d4d4d8` |
| thumb hover | `#3f3f46` | `#a1a1aa` |
| track | transparent | transparent |

## select option

| 属性 | 深色 | 浅色 |
|------|------|------|
| background | `#18181b` | `#ffffff` |
| color | `#e4e4e7` | `#27272a` |
