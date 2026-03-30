# Milk Skills Library | Gemini CLI 技能庫

這是一個專為 Gemini CLI 設計的技能庫清單，整合了系統內建技能以及來自各個專案的自訂技能。這些技能能夠擴展 AI 代理的功能，使其能夠處理從軟體開發、系統運維到個人生產力管理的各種任務。

## 目錄 (Table of Contents)

- [核心開發 (Core Development)](#核心開發-core-development)
- [雲端與運維 (Cloud & DevOps)](#雲端與運維-cloud--devops)
- [生產力與工具 (Productivity & Tools)](#生產力與工具-productivity--tools)
- [通訊與社交 (Communication & Social)](#通訊與社交-communication--social)
- [AI 與知識管理 (AI & Knowledge Management)](#ai-與知識管理-ai--knowledge-management)
- [多媒體與硬體控制 (Multimedia & Hardware)](#多媒體與硬體控制-multimedia--hardware)

---

## 核心開發 (Core Development)

| 技能名稱 (Skill) | 說明 (Description) |
| :--- | :--- |
| **api-design** | REST API 設計原則，涵蓋資源命名、錯誤處理、版本控制與分頁。 / REST API design principles, covering resource naming, error handling, versioning, and pagination. |
| **backend-testing** | 後端 API 測試，包含單元測試與整合測試。 / Backend API testing with unit tests and integration tests. |
| **code-review** | .NET Web API 程式碼審查清單，涵蓋安全、效能、設計與測試。 / Code review checklist for .NET web APIs, covering security, performance, design, and testing. |
| **dev-standards** | 強制執行高品質開發標準，包含單元測試與組件安全性。 / Enforce high-quality development standards including Unit Tests and Component Security. |
| **dotnet-release-management** | 管理 .NET 發佈生命週期，包含 NBGV 版本控制、SemVer、變更日誌與分支管理。 / Managing .NET release lifecycle, including NBGV versioning, SemVer, changelogs, and branching. |
| **fastapi** | 使用 FastAPI 進行 REST API 與 WebSocket 開發，強調安全性、效能與非同步模式。 / REST API and WebSocket development with FastAPI emphasizing security, performance, and async patterns. |
| **net-conventions** | .NET 編碼規範與 C# 最佳實踐。 / .NET coding conventions and C# best practices. |
| **postgresql-optimization** | PostgreSQL 開發助手，專注於 JSONB 操作、進階資料類型與效能優化。 / PostgreSQL-specific development assistant focusing on advanced data types and optimization. |
| **python-project-structure** | Python 專案架構組織、模組設計與公共 API 定義。 / Python project organization, module architecture, and public API design. |
| **test-driven-development** | 使用紅燈-綠燈-重構週期，在實作功能前先編寫測試。 / Write tests before implementing code using Red-Green-Refactor cycle. |
| **web-design-guidelines** | 審查 UI 程式碼是否符合 Web 介面準則，包含可存取性與設計審計。 / Review UI code for Web Interface Guidelines compliance and accessibility. |

## 雲端與運維 (Cloud & DevOps)

| 技能名稱 (Skill) | 說明 (Description) |
| :--- | :--- |
| **ansible-coder** | 編寫用於伺服器配置的 Ansible Playbooks，處理系統強化與自動化任務。 / Writing Ansible playbooks for server configuration and automation. |
| **aws-cost-finops** | AWS 成本優化與 FinOps 工作流，尋找閒置資源並分析節省機會。 / AWS cost optimization and FinOps workflows to find unused resources and analyze savings. |
| **devops** | 部署至 Cloudflare、Docker、GCP 與 Kubernetes，涵蓋 CI/CD 與 GitOps。 / Deploy to Cloudflare, Docker, GCP, and Kubernetes; covering CI/CD and GitOps. |
| **docker** | 將應用程式包裝為 Docker 容器，確保開發、測試與生產環境的一致性。 / Docker containerization for packaging applications for environment consistency. |
| **docker-compose-gen** | 掃描專案並自動生成 docker-compose.yml 檔案。 / Generate docker-compose.yml by scanning your project. |
| **docker-to-k8s-manifests** | 從 Docker 配置自動生成優化的 Kubernetes 部署清單。 / Automatically generate optimized Kubernetes deployment manifests from Docker. |
| **kubernetes** | Kubernetes 與 DevOps 專家，處理基礎設施即程式碼與雲端原生模式。 / Expert in Kubernetes and DevOps with infrastructure-as-code patterns. |
| **kubernetes-ops** | 部署與管理 Kubernetes 工作負載，包含資源故障排除與生產模式實作。 / Deploy and manage Kubernetes workloads and troubleshoot resources. |
| **healthcheck** | OpenClaw 部署的主機安全強化與風險配置審查。 / Host security hardening and risk-tolerance configuration for OpenClaw. |

## 生產力與工具 (Productivity & Tools)

| 技能名稱 (Skill) | 說明 (Description) |
| :--- | :--- |
| **1password** | 設定並使用 1Password CLI (op) 來管理祕密與登入資訊。 / Set up and use 1Password CLI (op) to manage secrets and logins. |
| **apple-notes** | 透過 macOS 上的 CLI 管理 Apple Notes（新增、編輯、搜尋與導出）。 / Manage Apple Notes via CLI on macOS (create, edit, search, and export). |
| **apple-reminders** | 透過 CLI 管理 Apple 提醒事項，支援列表與日期篩選。 / Manage Apple Reminders via CLI, supporting lists and date filters. |
| **bear-notes** | 透過 grizzly CLI 建立、搜尋與管理 Bear 筆記。 / Create, search, and manage Bear notes via grizzly CLI. |
| **notion** | 使用 Notion API 管理頁面、資料庫與區塊。 / Notion API for managing pages, databases, and blocks. |
| **obsidian** | 自動化處理 Obsidian 庫中的純 Markdown 筆記。 / Work with Obsidian vaults and automate via CLI. |
| **trello** | 透過 Trello REST API 管理看板、列表與卡片。 / Manage Trello boards, lists, and cards via Trello API. |
| **things-mac** | 透過 CLI 在 macOS 上管理 Things 3 待辦事項。 / Manage Things 3 via CLI on macOS. |
| **tmux** | 遠端控制 tmux 工作階段，發送按鍵並抓取輸出。 / Remote-control tmux sessions and scrape pane output. |
| **weather** | 獲取當前天氣預報，無需 API Key。 / Get current weather and forecasts via wttr.in. |

## 通訊與社交 (Communication & Social)

| 技能名稱 (Skill) | 說明 (Description) |
| :--- | :--- |
| **discord** | 透過訊息工具進行 Discord 操作。 / Discord ops via the message tool. |
| **slack** | 從 OpenClaw 控制 Slack，包含回應訊息與釘選項目。 / Control Slack from OpenClaw, including reacting and pinning. |
| **whatsapp (wacli)** | 發送 WhatsApp 訊息或搜尋/同步歷史紀錄。 / Send WhatsApp messages or sync history via wacli. |
| **bluebubbles** | 透過 BlueBubbles 整合發送與管理 iMessage。 / Send or manage iMessages via BlueBubbles integration. |
| **himalaya** | 透過 CLI 管理電子郵件 (IMAP/SMTP)，支援多帳號。 / CLI to manage emails via IMAP/SMTP from the terminal. |
| **xurl** | 使用 X (Twitter) API 進行推文、回覆與媒體上傳。 / CLI tool for making authenticated requests to the X (Twitter) API. |

## AI 與知識管理 (AI & Knowledge Management)
| 技能名稱 (Skill) | 說明 (Description) |
| :--- | :--- |
| **understand** | 分析程式碼庫以生成互動式知識圖譜，理解架構與關係。 / Analyze codebase to produce a knowledge graph for understanding architecture. |
| **understand-chat** | 基於知識圖譜對程式碼庫進行提問。 / Ask questions about a codebase using a knowledge graph. |
| **understand-diff** | 分析 Git Diff 或 PR 以理解變更影響與風險。 / Analyze git diffs or PRs to understand changes and risks. |
| **skill-creator** | 建立、編輯、改進或審核 AI 代理技能。 / Create, edit, improve, or audit AgentSkills. |
| **gemini** | 用於單次問答、總結與生成的 Gemini CLI 工具。 / Gemini CLI for one-shot Q&A, summaries, and generation. |
| **summarize** | 從 URL、Podcast 或本地檔案中提取文字或總結。 / Summarize or extract text/transcripts from URLs or files. |

## 多媒體與硬體控制 (Multimedia & Hardware)

| 技能名稱 (Skill) | 說明 (Description) |
| :--- | :--- |
| **openai-whisper** | 使用本地 Whisper 進行語音轉文字（無需 API Key）。 / Local speech-to-text with the Whisper CLI (offline). |
| **openhue** | 透過 CLI 控制 Philips Hue 燈光與場景。 / Control Philips Hue lights and scenes via CLI. |
| **sonoscli** | 控制 Sonos 揚聲器（搜尋、狀態、播放與音量）。 / Control Sonos speakers (status, playback, and volume). |
| **spotify-player** | 終端機版 Spotify 播放器與搜尋。 / Terminal Spotify playback and search. |
| **video-frames** | 使用 ffmpeg 從影片中提取影格或短片。 / Extract frames or short clips from videos using ffmpeg. |
| **diagram-gen** | 從程式碼自動生成 Mermaid 架構圖。 / Generate Mermaid diagrams from your codebase. |

---

## 如何使用 (How to Use)

這些技能可以直接被 Gemini CLI 或 OpenClaw 代理調用。如果您想在本地安裝某個技能，可以使用 ind-skills 或手動將資料夾加入您的技能路徑中。

---
最後更新日期: 2026-03-30
