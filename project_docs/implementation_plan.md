# 实施计划：AI IM 解析器与数据结构化

## 局部小目标
[cite_start]实现第一个功能模块：利用 OpenAI API 自动解析项目资料 (IM) PDF，并将其结构化数据写入 Google Sheets 的 `Listings` 母表 [cite: 103, 108]。

## 关键路径
1. [cite_start]**数据建模**：在 Google Sheets 中定义 `Listings` 和 `Buyers` 的字段架构（Schema） [cite: 86, 108]。
2. [cite_start]**Codespaces 调优**：确保 `service_account.json` 在云端环境可被 Python 脚本调用 [cite: 75, 81]。
3. [cite_start]**Webhook 联调**：利用 Codespaces 的 **Port Forwarding** 功能开启公网 HTTPS URL，对接 Twilio WhatsApp Sandbox [cite: 67, 72]。
4. [cite_start]**AI 逻辑实现**：编写 Prompt 引导 GPT-4 解析 PDF 文本并输出 JSON 格式 [cite: 89, 103]。