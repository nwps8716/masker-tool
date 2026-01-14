# Masker Tool 🛡️

**Masker Tool** 是一個輕量級的 CLI 工具，專為開發者設計。它可以自動偵測並遮蔽程式碼中的敏感資料（如 IPv4、IPv6、API Keys 等），讓你能夠放心地將程式碼分享給 AI 工具（如 ChatGPT、Claude）進行諮詢，而不用擔心資安外洩。

---

## ✨ 功能特色

* **自動遮蔽**：支援 IPv4、IPv6、及 `sk-` 開頭的 API Keys。
* **密碼過濾**：自動偵測並隱藏 `password: "..."` 格式的字串。
* **剪貼簿整合**：支援 `-c` 參數，一鍵淨化剪貼簿內容並自動回寫。
* **輕量無依賴**：基於 Shell Script 與 Perl，在 macOS 與 Linux 環境下皆能穩定執行。

---

## 🚀 安裝方式 (macOS)

透過 Homebrew 快速安裝：

```bash
# 1. 加入 Tap 倉庫 (請將 your-github-id 換成你的 GitHub 帳號)
brew tap your-github-id/tap

# 2. 安裝工具
brew install masker
