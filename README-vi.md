::: {align="center"}
`<img src="nanobot_logo.png" alt="nanobot" width="500">`{=html}
```{=html}
<h1>
```
nanobot: Trợ lý AI cá nhân siêu nhẹ
```{=html}
</h1>
```
```{=html}
<p>
```
`<a href="https://pypi.org/project/nanobot-ai/">`{=html}`<img src="https://img.shields.io/pypi/v/nanobot-ai" alt="PyPI">`{=html}`</a>`{=html}
`<a href="https://pepy.tech/project/nanobot-ai">`{=html}`<img src="https://static.pepy.tech/badge/nanobot-ai" alt="Downloads">`{=html}`</a>`{=html}
`<img src="https://img.shields.io/badge/python-≥3.11-blue" alt="Python">`{=html}
`<img src="https://img.shields.io/badge/license-MIT-green" alt="License">`{=html}
`<a href="./COMMUNICATION.md">`{=html}`<img src="https://img.shields.io/badge/Feishu-Group-E9DBFC?style=flat&logo=feishu&logoColor=white" alt="Feishu">`{=html}`</a>`{=html}
`<a href="./COMMUNICATION.md">`{=html}`<img src="https://img.shields.io/badge/WeChat-Group-C5EAB4?style=flat&logo=wechat&logoColor=white" alt="WeChat">`{=html}`</a>`{=html}
`<a href="https://discord.gg/MnCvHqpUGB">`{=html}`<img src="https://img.shields.io/badge/Discord-Community-5865F2?style=flat&logo=discord&logoColor=white" alt="Discord">`{=html}`</a>`{=html}
```{=html}
</p>
```
:::

🐈 **nanobot** là một trợ lý AI cá nhân **siêu nhẹ** được lấy cảm hứng
từ [OpenClaw](https://github.com/openclaw/openclaw)

⚡️ Cung cấp chức năng agent cốt lõi chỉ với **\~4.000** dòng code ---
**nhỏ hơn 99%** so với hơn 430k dòng của Clawdbot.

📏 Số dòng code theo thời gian thực: **3.966 dòng** (chạy
`bash core_agent_lines.sh` để kiểm tra bất cứ lúc nào)

## 📢 Tin tức

-   **2026-02-24** 🚀 Phát hành **v0.1.4.post2** --- bản phát hành tập
    trung vào độ tin cậy với heartbeat được thiết kế lại, tối ưu cache
    prompt và tăng cường độ ổn định provider & channel. Xem [release
    notes](https://github.com/HKUDS/nanobot/releases/tag/v0.1.4.post2)
    để biết chi tiết.
-   **2026-02-23** 🔧 Heartbeat virtual tool-call, tối ưu cache prompt,
    sửa lỗi Slack mrkdwn.
-   **2026-02-22** 🛡️ Cách ly thread Slack, sửa lỗi typing Discord, cải
    thiện độ tin cậy agent.
-   **2026-02-21** 🎉 Phát hành **v0.1.4.post1** --- provider mới, hỗ
    trợ media trên nhiều channel, và cải thiện lớn về độ ổn định. Xem
    [release
    notes](https://github.com/HKUDS/nanobot/releases/tag/v0.1.4.post1)
    để biết chi tiết.
-   **2026-02-20** 🐦 Feishu hiện nhận file đa phương tiện từ người
    dùng. Bộ nhớ hoạt động đáng tin cậy hơn bên trong.
-   **2026-02-19** ✨ Slack hiện gửi file, Discord chia nhỏ tin nhắn
    dài, và subagent hoạt động trong chế độ CLI.
-   **2026-02-18** ⚡️ nanobot hiện hỗ trợ VolcEngine, MCP custom auth
    headers, và Anthropic prompt caching.
-   **2026-02-17** 🎉 Phát hành **v0.1.4** --- hỗ trợ MCP, streaming
    tiến trình, provider mới, và nhiều cải tiến channel. Xem [release
    notes](https://github.com/HKUDS/nanobot/releases/tag/v0.1.4) để biết
    chi tiết.
-   **2026-02-16** 🦞 nanobot hiện tích hợp skill
    [ClawHub](https://clawhub.ai) --- tìm kiếm và cài đặt skill agent
    công khai.
-   **2026-02-15** 🔑 nanobot hiện hỗ trợ provider OpenAI Codex với đăng
    nhập OAuth.
-   **2026-02-14** 🔌 nanobot hiện hỗ trợ MCP! Xem [phần
    MCP](#mcp-model-context-protocol) để biết chi tiết.
-   **2026-02-13** 🎉 Phát hành **v0.1.3.post7** --- bao gồm tăng cường
    bảo mật và nhiều cải tiến. **Vui lòng nâng cấp lên phiên bản mới
    nhất để khắc phục các vấn đề bảo mật**. Xem [release
    notes](https://github.com/HKUDS/nanobot/releases/tag/v0.1.3.post7)
    để biết thêm chi tiết.
-   **2026-02-12** 🧠 Hệ thống bộ nhớ được thiết kế lại --- ít code hơn,
    đáng tin cậy hơn. Tham gia [thảo
    luận](https://github.com/HKUDS/nanobot/discussions/566)!
-   **2026-02-11** ✨ Cải thiện trải nghiệm CLI và thêm hỗ trợ MiniMax!

## Key Features of nanobot:

🪶 **Siêu nhẹ**: Chỉ \~4.000 dòng code agent cốt lõi --- nhỏ hơn 99% so
với Clawdbot.

🔬 **Sẵn sàng cho nghiên cứu**: Code sạch, dễ đọc, dễ hiểu, dễ chỉnh sửa
và mở rộng.

⚡️ **Cực nhanh**: Dấu chân nhỏ giúp khởi động nhanh hơn, sử dụng ít tài
nguyên hơn, và lặp nhanh hơn.

💎 **Dễ sử dụng**: Triển khai chỉ với một cú nhấp và sẵn sàng sử dụng.

## 🏗️ Kiến trúc

```{=html}
<p align="center">
```
`<img src="nanobot_arch.png" alt="nanobot architecture" width="800">`{=html}
```{=html}
</p>
```
## ✨ Tính năng

```{=html}
<table align="center">
```
```{=html}
<tr align="center">
```
```{=html}
<th>
```
```{=html}
<p align="center">
```
📈 Phân tích thị trường thời gian thực 24/7
```{=html}
</p>
```
```{=html}
</th>
```
```{=html}
<th>
```
```{=html}
<p align="center">
```
🚀 Kỹ sư phần mềm Full‑Stack
```{=html}
</p>
```
```{=html}
</th>
```
```{=html}
<th>
```
```{=html}
<p align="center">
```
📅 Trình quản lý thói quen hàng ngày thông minh
```{=html}
</p>
```
```{=html}
</th>
```
```{=html}
<th>
```
```{=html}
<p align="center">
```
📚 Trợ lý kiến thức cá nhân
```{=html}
</p>
```
```{=html}
</th>
```
```{=html}
</tr>
```
```{=html}
<tr>
```
```{=html}
<td align="center">
```
```{=html}
<p align="center">
```
`<img src="case/search.gif" width="180" height="400">`{=html}
```{=html}
</p>
```
```{=html}
</td>
```
```{=html}
<td align="center">
```
```{=html}
<p align="center">
```
`<img src="case/code.gif" width="180" height="400">`{=html}
```{=html}
</p>
```
```{=html}
</td>
```
```{=html}
<td align="center">
```
```{=html}
<p align="center">
```
`<img src="case/scedule.gif" width="180" height="400">`{=html}
```{=html}
</p>
```
```{=html}
</td>
```
```{=html}
<td align="center">
```
```{=html}
<p align="center">
```
`<img src="case/memory.gif" width="180" height="400">`{=html}
```{=html}
</p>
```
```{=html}
</td>
```
```{=html}
</tr>
```
```{=html}
<tr>
```
```{=html}
<td align="center">
```
Khám phá • Insight • Xu hướng
```{=html}
</td>
```
```{=html}
<td align="center">
```
Phát triển • Triển khai • Mở rộng
```{=html}
</td>
```
```{=html}
<td align="center">
```
Lên lịch • Tự động hóa • Tổ chức
```{=html}
</td>
```
```{=html}
<td align="center">
```
Học tập • Bộ nhớ • Lý luận
```{=html}
</td>
```
```{=html}
</tr>
```
```{=html}
</table>
```
## 📦 Cài đặt

**Cài đặt từ source** (tính năng mới nhất, khuyến nghị cho phát triển)

``` bash
git clone https://github.com/HKUDS/nanobot.git
cd nanobot
pip install -e .
```

**Cài đặt với [uv](https://github.com/astral-sh/uv)** (ổn định, nhanh)

``` bash
uv tool install nanobot-ai
```

**Cài đặt từ PyPI** (ổn định)

``` bash
pip install nanobot-ai
```

## 🚀 Bắt đầu nhanh

> \[!TIP\] Đặt API key của bạn trong `~/.nanobot/config.json`. Lấy API
> key: [OpenRouter](https://openrouter.ai/keys) (Toàn cầu) · [Brave
> Search](https://brave.com/search/api/) (tùy chọn, cho tìm kiếm web)

**1. Khởi tạo**

``` bash
nanobot onboard
```

**2. Cấu hình** (`~/.nanobot/config.json`)

Thêm hoặc hợp nhất **hai phần** này vào config của bạn.

*Đặt API key của bạn*:

``` json
{
  "providers": {
    "openrouter": {
      "apiKey": "sk-or-v1-xxx"
    }
  }
}
```

*Đặt model của bạn*:

``` json
{
  "agents": {
    "defaults": {
      "model": "anthropic/claude-opus-4-5"
    }
  }
}
```

**3. Chat**

``` bash
nanobot agent
```

Vậy là xong! Bạn đã có một trợ lý AI hoạt động trong 2 phút.
