# 任務佇列 (Task Queue)

---

## 🔴 高優先 - 需要立即處理

*(暫時沒有)*

---

## 🟠 中優先 - 計劃中

### Task #007: Firebase 設定家庭記帳 App
**狀態:** ✅ **已完成！** 
**完成日期:** 2026-04-22
**URL:** https://family-accounting-app-v2.vercel.app

---

### P2 #2: 大學合作電郵草稿（已移至 ARCHIVE）
**狀態:** 🗄️ 已封存（逾期 12 日）
**截止日期:** 2026-04-10
**位置:** `tasks/ARCHIVE/email-university-cooperation-DRAFT.md`

---

### P2 #3: 專利律師 FTO 查詢草稿（已移至 ARCHIVE）
**狀態:** 🗄️ 已封存（逾期 12 日）
**截止日期:** 2026-04-10
**位置:** `tasks/ARCHIVE/email-patent-fto-DRAFT.md`

---

## 🔵 長期待辦 - 以後再做

### P3 #004: 團隊優化項目
**狀態:** 🔵 進行中
**建立日期:** 2026-04-22
**位置:** `TEAM_MEMORY.md`

**待優化項目：**
| 項目 | 狀態 | 備註 |
|------|------|------|
| Remotion 版本統一 | ✅ 已完成（4.0.448） | 2026-04-22 |
| 任務追蹤機制 | ✅ 已建立 | 每天 09:00 站會 |
| 任務逾期跟進 | 🔄 待完善 | 需要自動催進機制 |
| STEMI 視頻流程 | 🔄 待繼續 | 準備完成，等待製作 |
| Brave Search 限流 | ⚠️ 待解決 | 建議升级或减少頻率 |

**最後更新:** 2026-04-22 09:25

---

### P3 #003: sa 女兒中文科學習計劃
**狀態:** 🔵 草稿完成，待安排執行
**建立日期:** 2026-04-11
**最後更新:** 2026-04-12
**位置:** `shared/artifacts/learning-plan-sa-p1-chinese-DRAFT.md`

**建議下一步:**
- [ ] 與 sa 溝通，了解學習偏好
- [ ] 借閱 SFCS 圖書館書籍
- [ ] 建立每日學習時間表

---

## 🟡 低優先 - 閒時處理

### 🎬 Mindray SV650 呼吸機教育視頻
**狀態:** 🔄 Team 準備中
**建立日期:** 2026-04-23
**位置:** `sv650-education-video/`

**分配中:**
- 🔨 Design Manager — 視覺規範
- 🔨 Researcher — 臨床資料
- 🔨 Remotion Developer — 代碼結構

**視頻目標:** 5-10分鐘教學視頻，幫助同事學習 SV650

**素材:** 4張屏幕截圖已保存

---

### 🎬 STEMI 醫學教育視頻
**狀態:** 🔵 準備完成，待繼續製作
**建立日期:** 2026-04-22
**位置:** `/Users/sacompig/.openclaw/workspace/stemi-education-video/`

**已完成:**
- ✅ Design Manager 視覺規範
- ✅ Researcher 臨床資料
- ✅ Remotion Developer 代碼結構

**待做:**
- [ ] 繼續視頻製作（你話我知點整）

---

### Duty Roster 優化 #5: ICS 格式改進
**狀態:** ✅ 完成（#13, commit 26f0345）
**建立日期:** 2026-04-23
**位置:** `duty-roster-ics/`

**已完成:**
- [x] VEVENT DTSTART/DTEND 改用 `VALUE=DATE-TIME` +08:00

---

### Duty Roster 優化 #6: 打印排版優化
**狀態:** ✅ 完成（#12, commit cc07aab）
**建立日期:** 2026-04-23
**位置:** `duty-roster-ics/`

**已完成:**
- [x] 更適合紙張的排版設計（@page landscape, 更好的字體/間距）

---

### Duty Roster 優化 #7: ICS 預覽顯示修復
**狀態:** ✅ 完成（commit 3de6fb2）
**建立日期:** 2026-04-24
**優先:** 🔴 高
**位置:** `duty-roster-ics/`

**問題:** 點擊「預覽更期」後，iCalendar 內容在 JS 產生但冇 render 到可見 DOM
**已完成:**
- [x] 將 generateICS 的輸出顯示喺 previewArea 的 pre/textarea 內

### Duty Roster 優化 #8: AN Shift 雙時段顯示
**狀態:** ✅ 完成（commit a5c390b）
**建立日期:** 2026-04-24
**優先:** 🟠 中
**位置:** `duty-roster-ics/`

**問題:** AN 實際係 07:00-14:00 + 21:00-23:59 兩段，但 Ward View 只顯示一個 badge
**已完成:**
- [x] Ward View AN badge 加時段提示文字「1+2」

### Duty Roster 優化 #9: 月份導航同步
**狀態:** ✅ 已移除功能（commit c0c0eba）
**建立日期:** 2026-04-24
**優先:** 🟡 低
**位置:** `duty-roster-ics/`

**問題:** Header 月份箭嘴改 currentDate，但 Ward View 用 currentWardDate，兩者冇關聯
**解決方案:** 已移除 header 重複的月份箭嘴，保留 Ward View 內的導航

### Duty Roster 優化 #10: 日期 URL 分享功能
**狀態:** ✅ 完成（commit a5c390b）
**建立日期:** 2026-04-24
**優先:** 🟡 低
**位置:** `duty-roster-ics/`
**已完成:**
- [x] 加入 #date=YYYY-MM-DD hash，支援 URL 分享特定日期
- [x] Ward View 切換時自動更新 URL

### Duty Roster 優化 #16: 打印視圖剪貼板功能
**狀態:** ✅ 完成（commit b58795e）
**建立日期:** 2026-04-24
**優先:** 🟡 低
**位置:** `duty-roster-ics/`
**已完成:**
- [x] 加「複製到剪貼板」一鍵功能（copyPrintTable()）

### Duty Roster 優化 #17: Ward View 記住上次日期
**狀態:** ✅ 完成（commit 9f37df4）
**建立日期:** 2026-04-24
**優先:** 🟡 低
**位置:** `duty-roster-ics/`
**已完成:**
- [x] 用 localStorage 記住 currentWardDate（dutyRoster_lastWardDate）
- [x] 打開時自動 restore

### Duty Roster 優化 #18: 搜索功能改進
**狀態:** ✅ 完成（commit f6fdb85）
**建立日期:** 2026-04-24
**優先:** 🟡 低
**位置:** `duty-roster-ics/`
**已完成:**
- [x] 加日期快速跳轉（今日、下週按鈕）
- [x] 支援按班次關鍵字搜索（AN、A5 等）

### Duty Roster 優化 #19: 空數據提示改進
**狀態:** ✅ 完成（commit 2fbd59a）
**建立日期:** 2026-04-24
**優先:** 🟡 低
**位置:** `duty-roster-ics/`
**已完成:**
- [x] 顯示「請選擇 X 月至 Y 月」引導文字
- [x] 推薦有數據的日期範圍

### Duty Roster 優化 #20: PWA 離線數據自動更新
**狀態:** ✅ 完成（commit ad104cb）
**建立日期:** 2026-04-24
**優先:** 🟢 閒時
**位置:** `duty-roster-ics/`
**已完成:**
- [x] GitHub Actions workflow 定期 fetch 最新 data.js
- [x] Service Worker 自動更新日曆數據

### Duty Roster 優化 #11: 代碼重構
**狀態:** ⚠️ 已 Revert（commit 0c9b867 — 導致頁面break）
**建立日期:** 2026-04-24
**優先:** 🟢 閒時
**位置:** `duty-roster-ics/`

**問題:** 所有代碼喺 index.html，難維護
**狀態:** 嘗試拆分 JS 到 js/app.js、CSS 到 css/styles.css，但導致頁面無法運作，已 revert。未來如要重構需要更謹慎的測試。

---

## ✅ 已完成

### Task #006: 家庭記帳 HTML 原型
- GitHub: https://github.com/yayasasapig/family-accounting-app
- 部署: https://yayasasapig.github.io/family-accounting-app/

### Task #005: 家庭記帳 App 語音輸入功能
- Web Speech API 已加入 add.html

### Task #004: 家庭記帳 App 建議分析
- Research + Inventor 分析完成

### Task #007: Firebase 家庭記帳 App
- ✅ **已完成！** https://family-accounting-app-v2.vercel.app

### Agent Team Persona Cards
- ✅ 13個 Agent 完成
- GitHub: https://github.com/yayasasapig/yayafu-agent-team

### Remotion Skill 安裝
- ✅ 來自官方 https://github.com/remotion-dev/skills
- ✅ 34個 rules

---

## 📋 任務更新記錄

| 日期 | 任務 | 更新內容 |
|------|------|----------|
| 2026-04-22 | Task #007 | ✅ Firebase App 已部署至 Vercel |
| 2026-04-22 | STEMI 視頻 | ✅ 準備工作完成 |
| 2026-04-22 | P2 #2/#3 | ⚠️ 逾期 12 日，待確認 |

---

---

## 15:04 HKT — Health Check + Heartbeat

- ✅ tasks/QUEUE.md 存在
- ✅ shared/artifacts 可寫
- ✅ 無 Orphaned Tasks
- 📋 佇列空閒，STEMI 視頻準備就緒

*最後更新：2026-04-24 15:57 HKT*