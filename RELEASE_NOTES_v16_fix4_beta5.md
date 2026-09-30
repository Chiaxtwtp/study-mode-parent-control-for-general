# v16_fix4_beta5

## Beta 5

### 修正
- 修正「儲存並關閉」只儲存但不關閉家長設定視窗的問題。
- 程式啟動時即使正位於排程時段，也先停留在主畫面，不會立即自動 START。
- 啟動當下的排程時段可由使用者手動開始；下一個排程時段仍可正常自動生效。

### 既有 Beta Foundation
- 家長設定持久化與完整磁碟驗證。
- 網站、程式、排程、休息提醒與自動啟動設定保存。
- Atomic config save + backup recovery。
- Hybrid Time 防系統時間異常。
- hosts crash recovery。
- Single-instance protection。
- Windows 登入自動啟動。
- Rotating log。

## 測試重點
1. 第一次建立密碼後重新開啟，密碼設定應保留。
2. 修改網站、程式與排程後重新開啟，設定應保留。
3. 家長設定右上角 X →「是：儲存並關閉」應真正關閉設定視窗。
4. 在排程時段內重新啟動程式，主畫面應先保持停止。
5. 手動 START / STOP 應正常。
