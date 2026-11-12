# WMWWZS.github.io

个人站点的**根域名入口**，只做一件事：把 `https://wmwwzs.github.io/` 自动跳转到真正的个人主页：

**https://wmwwzs.github.io/learning-journey/**

## 为什么需要这个仓库

GitHub Pages 有两种站点：

| 类型 | 地址 | 对应仓库 |
| :-- | :-- | :-- |
| 用户站点 | `https://wmwwzs.github.io/` | 本仓库 `<用户名>.github.io` |
| 项目站点 | `https://wmwwzs.github.io/learning-journey/` | `learning-journey` |

之前根域名那个仓库被删了，导致直接输 `wmwwzs.github.io` 会 404。这个仓库就是补回根域名，做一次 301/跳转。

## 文件说明

- `index.html`：火山主题跳转页（1 秒后自动跳转，带手动链接兜底）
- `.nojekyll`：关闭 Jekyll 处理，加快部署

## 部署

仓库名必须是 `WMWWZS.github.io`，Pages 来源选 `main` 分支根目录（`/`）。
