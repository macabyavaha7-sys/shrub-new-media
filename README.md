# 灌木新媒体官网

静态官网项目，面向 GitHub Pages 部署。

## 结构

- `index.html`：官网首页。
- `assets/logo/`：灌木 logo。
- `assets/videos/`：9:16 竖屏案例视频。
- `assets/covers/`：从视频自动截取的预览封面。
- `docs/`：方案资料。

## 文案规则

后续官网文案遵循 `docs/copy-rules.md`。尤其避免“不是 A 是 B”“不是 A 而是 B”“不止于 A”的反向定义句式。

## 发布

仓库开启 GitHub Pages 后，选择：

- Source: Deploy from a branch
- Branch: `main`
- Folder: `/root`

默认访问地址：

```text
https://macabyavaha7-sys.github.io/shrub-new-media/
```

## 更新

替换视频时保持文件名不变，页面会自动读取同名视频。新增案例时，在 `index.html` 的案例区增加一张 `case-card`。
