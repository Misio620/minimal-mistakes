---
layout: single
title: "API 練習與 Postman 筆記"
date: 2025-03-09 10:00:00 +0800
categories: [學習筆記]
tags: [API, Postman, 自動化測試]
excerpt: "記錄用 Postman 學習 API 的操作步驟與常見錯誤排查。"
---

為了熟悉 API，我用 Postman 建立了一系列請求範本，從 CRUD 動作到授權測試都涵蓋：

- 以環境變數管理 base URL、token，避免在多個請求中重複修改。
- 用 collection 內的測試腳本確認回應格式與狀態碼，確保穩定性。
- 針對常見錯誤（如授權失效、欄位缺漏）建立排查清單，縮短 debugging 時間。

持續累積這些筆記，讓我在導入新 API 或對接第三方服務時更有把握。
