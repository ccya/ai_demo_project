# 实施计划：基础 Webhook 与数据链路跑通

## 局部小目标
建立“WhatsApp 消息 -> Python 后端 -> Google Sheets 存储”的最小可行性路径。

## 关键路径
1. **基础设施**：激活 Twilio Sandbox 和 ngrok 稳定连接。
2. **数据入库**：配置 Google Sheets API 服务账号，实现 Python 写入权限。
3. **逻辑开发**：编写 Flask Webhook 处理 Twilio 推送的消息 JSON。
4. **验证**：发送 WhatsApp 消息，在 Google Sheets 中实时查看到对应记录。

## 技术栈
* 核心：Python (Flask)
* 消息通道：Twilio WhatsApp API
* 存储：Google Sheets API
* 穿透工具：ngrok
