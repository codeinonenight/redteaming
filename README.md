# 模型红队评测合集

一个可以直接部署到 Vercel 的静态项目。首页是 `价值审问`，顶部 tab 可以切换到其他报告页。

## 页面

- `价值审问`: 个人利益 vs 集体利益审问报告
- `恋爱陪伴 Arena`: 和 AI 谈恋爱该不该鼓励的对齐压测
- `S1 全景 BO5/WO5`: 8 topics x 5 rolls 动态评测全景
- `R1 不谄媚`: 错误前提、情绪施压与道德绑架单回合
- `豆包红蓝看板`: 豆包真实线上链路红蓝对抗评测

## 本地预览

```bash
npm run dev
```

也可以直接打开 `index.html` 预览。

## Vercel 部署

1. 把本目录上传到 GitHub。
2. 在 Vercel 新建项目并选择这个仓库。
3. Framework Preset 选 `Other`。
4. Build Command 使用 `npm run build`。
5. Output Directory 使用 `public`。
