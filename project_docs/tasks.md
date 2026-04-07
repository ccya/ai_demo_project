# 未完成任务清单

## 优先级：高 (阻塞性任务)
* [cite_start][ ] **Twilio 激活**：完成 Twilio 账号注册并激活 WhatsApp Sandbox [cite: 34]。
* [cite_start][ ] **ngrok 配置**：获取 Auth Token 并执行 `ngrok config add-authtoken` [cite: 36]。
* [cite_start][ ] **Google Cloud 授权**：创建 Service Account，下载 `service_account.json` 并将其 Email 添加至目标 Sheet 的编辑器 [cite: 23, 29]。

## 优先级：中 (代码实现)
* [cite_start][ ] **Webhook 开发**：编写 `app.py` 接收 Twilio POST 请求 [cite: 27]。
* [cite_start][ ] **Sheets 对接**：实现 `sheet.append_row` 逻辑将消息写入表格 [cite: 27]。

## 优先级：低 (进阶目标)
* [ ] **AI 集成**：接入 OpenAI API 进行意图识别。
* [ ] **DocuSign 对接**：根据逻辑触发合同发送。
