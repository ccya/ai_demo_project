# 未完成任务清单

## 优先级：高 (阻塞性任务)
* [cite_start][x] **Twilio 激活**：完成 Twilio 账号注册并激活 WhatsApp Sandbox [cite: 34]。
* [cite_start][x] **ngrok 配置**：获取 Auth Token 并执行 `ngrok config add-authtoken` [cite: 36]。
* [cite_start][x] **Google Cloud 授权**：创建 Service Account，下载 `service_account.json` 并将其 Email 添加至目标 Sheet 的编辑器 [cite: 23, 29]。
* [cite_start][ ] **Google Sheets 初始化**：根据 Edugrow 需求建立 `Buyers` 和 `Listings` 表格 [cite: 86, 108]。
* [cite_start][ ] **Codespaces Webhook**：启动 `app.py` 并通过 Codespaces Ports 设置 Public 权限，获取公网地址 [cite: 67, 72]。
* [cite_start][ ] **Twilio 对接**：将生成的公网 URL 填入 Twilio Sandbox 配置 [cite: 59, 64]。

## 优先级：中 (功能开发)
* [cite_start][ ] **AI 解析器代码**：编写利用 `gspread` 和 `openai` 实现 PDF 解析并写入表格的脚本 [cite: 89, 108]。
* [cite_start][ ] **NDA 自动化逻辑**：集成 DocuSign API 实现自动发送签署请求 [cite: 87, 102]。
* [cite_start][ ] **Webhook 开发**：编写 `app.py` 接收 Twilio POST 请求 [cite: 27]。
* [cite_start][ ] **Sheets 对接**：实现 `sheet.append_row` 逻辑将消息写入表格 [cite: 27]。

## 优先级：低 (系统扩展)
* [cite_start][ ] **Matching Engine**：编写买家与项目的评分匹配算法 [cite: 91, 107]。
* [cite_start][ ] **WhatsApp 序列**：在 Twilio 中配置自动跟进工作流 [cite: 92, 104]。
* [ ] **AI 集成**：接入 OpenAI API 进行意图识别。
* [ ] **DocuSign 对接**：根据逻辑触发合同发送。