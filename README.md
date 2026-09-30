# AI Study Mode

Windows 家長控制 / 自主學習模式工具。

> **目前狀態：Beta 測試版**
>
> 這個 repository 僅提供公開下載與 Beta 問題回報，**不包含原始碼**。

## 下載

最新測試版本：**v16_fix4_beta5**

請使用本 repository 右側的 **Releases** 下載 Windows 版本。  
若目前尚未看到 Release，代表最新安裝包正在準備發布。

## 主要功能

- 指定 Windows 應用程式限制
- YouTube / Roblox / Discord / TikTok / Twitch 等網站限制
- 每週獨立排程，支援跨午夜
- 家長密碼保護
- 休息提醒
- Hybrid Time：本機時鐘 + 背景可信時間驗證
- 設定自動保存、備份與重新讀取驗證
- Crash 後 hosts 規則清理
- Windows 登入自動啟動
- 單一執行個體保護

## 系統需求

- Windows 10 / Windows 11
- x64
- 需要系統管理員權限，以便套用網站限制與部分系統設定

## 第一次執行

1. 從 **Releases** 下載最新版本。
2. 解壓縮後執行 `AI_Study_Mode.exe`。
3. Windows 可能顯示 SmartScreen「不明的發行者」警告；目前 Beta 尚未使用正式 Code Signing。
4. 建立家長密碼。
5. 進入「家長進階設定」設定程式、網站與排程。

## 本機資料位置

設定：

`C:\ProgramData\AI_Study_Mode\config.json`

Log：

`C:\ProgramData\AI_Study_Mode\logs\ai_study_mode.log`

## Beta 問題回報

若遇到問題，可在本 repository 建立 Issue，並提供：

- Windows 版本
- AI Study Mode 版本
- 問題發生步驟
- 是否能穩定重現
- 必要時附上 Log（請先確認其中沒有你不想公開的資訊）

## Privacy

目前版本採 Local-first 設計。家長設定與程式資料儲存在本機。

## Source Code

此公開 repository **不提供程式原始碼**；開發用 source repository 保持 Private。
