# WDA Builder

自动构建 WebDriverAgent IPA 的 GitHub Actions 工作流。

## 使用方法

1. 在 GitHub 上创建一个新仓库（如 `wda-builder`）
2. 把 `.github/workflows/build-wda.yml` 推送上去
3. 在 GitHub 仓库页面 → Actions → Build WebDriverAgent IPA → Run workflow
4. 等待构建完成（约 5-10 分钟）
5. 下载 Artifacts 中的 `WebDriverAgent-IPA`
