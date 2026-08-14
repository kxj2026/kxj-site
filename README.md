# kxj-site

Ying Tang Hong Investment 公司官网（纯静态 HTML/CSS）。通过 GitHub Actions 自动部署到 Azure Static Web Apps（KXJ）。

## 部署
- 推送 `main` 分支即触发 `.github/workflows/azure-static-web-apps.yml` 自动构建并发布到 Azure。
- 所需的部署令牌以仓库 Secret `AZURE_STATIC_WEB_APPS_API_TOKEN` 形式提供。

## 本地预览
```bash
python -m http.server 8080
# 浏览器打开 http://127.0.0.1:8080/
```
