# OpenAI GitHub Actions

## 简介
此项目通过 GitHub Actions 集成了 OpenAI API，可以自动触发并调用 OpenAI 的服务。

## 配置步骤
1. **获取 OpenAI API 密钥**：
   - 登录 [OpenAI 平台](https://platform.openai.com/)。
   - 在账户设置中生成一个新的 API 密钥。

2. **配置 GitHub Secrets**：
   - 进入 GitHub 仓库的 `Settings` > `Secrets and variables` > `Actions`。
   - 添加一个名为 `OPENAI_API_KEY` 的 Secret，值为您的 OpenAI API 密钥。

3. **运行工作流**：
   - 在 `Actions` 页面找到 `OpenAI API Integration` 工作流。
   - 点击 `Run workflow` 按钮触发运行。

## 文件说明
- `.github/workflows/main.yml`：GitHub Actions 工作流配置文件。
- `README.md`：项目的自述文件。

## 注意
请勿将 API 密钥直接公开到代码中，确保其存储在 GitHub Secrets 中以保护敏感信息。
