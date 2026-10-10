# bjtime — 北京时间对照网页

北京时间（UTC+8）与设备时间对照单页应用：

- 多端自适应（手机/平板/桌面）
- 日 / 夜间模式切换（记忆偏好）
- 精确到秒，每秒自动刷新
- 同时显示设备本地时间与其时区
- 自动计算并显示设备与北京的时差
- 支持手动输入设备与北京/石家庄的校正差异

## 本地预览

直接用浏览器打开 `index.html` 即可。

## 部署（GitHub Pages）

本仓库已配置 GitHub Actions 工作流（`.github/workflows/deploy.yml`），
推送到 `main` 分支即自动部署。

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/<你的用户名>/bjtime.git
git push -u origin main
```

在仓库 **Settings → Pages** 中将 Source 设为 **GitHub Actions**，
站点地址为 `https://<你的用户名>.github.io/bjtime/`。
