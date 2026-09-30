# AI Study Mode

Windows 家長控制 / 自主學習模式工具。

> **目前狀態：Beta 測試版**
>
> 這個 repository 僅提供公開下載版本，不包含原始碼。

## 最新版本

**v16_fix4_beta5**

請到右側 **Releases** 下載最新的 Windows EXE。

## 功能

- 指定 Windows 應用程式限制
- YouTube / Roblox / Discord / TikTok / Twitch 等網站限制
- 每週獨立排程，支援跨午夜
- 家長密碼保護
- 休息提醒
- Hybrid Time：本機時鐘 + 背景可信時間驗證
- 設定自動保存與備份
- Crash 後 hosts 規則清理
- Windows 登入自動啟動
- 單一執行個體保護

## 系統需求

- Windows 10 / Windows 11
- x64
- 需要系統管理員權限，以便套用網站限制與部分系統設定

## 第一次執行

1. 下載 Release 中的 EXE。
2. 執行程式。
3. Windows 可能顯示 SmartScreen「不明的發行者」警告，因目前 Beta 尚未使用正式 Code Signing。
4. 建立家長密碼。
5. 進入「家長進階設定」設定程式、網站與排程。

## 資料位置

設定：

`C:\ProgramData\AI_Study_Mode\config.json`

Log：

`C:\ProgramData\AI_Study_Mode\logs\ai_study_mode.log`

## Beta 問題回報

若遇到問題，請保留 Log 並在此 repository 建立 Issue，描述：

- Windows 版本
- AI Study Mode 版本
- 問題發生步驟
- 是否能重現
- 必要時附上 Log（請先確認其中沒有你不想公開的資訊）

## Privacy

目前版本採 Local-first 設計。家長設定與使用資料儲存在本機。

## Source Code

此公開 repository **不包含程式原始碼**，僅用於公開下載與 Beta 問題回報。
