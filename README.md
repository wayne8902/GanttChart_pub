# 甘特圖專案管理

離線 Windows 桌面程式，供專案與任務進度管理，並以甘特圖檢視時程。

## 下載

請至 [Releases](../../releases) 下載最新版本的 `GanttChart-vX.X.X.zip`。

## 安裝與執行

1. 下載 zip 並解壓縮
2. 進入 `GanttChart` 資料夾
3. 雙擊 `GanttChart.exe` 啟動

**無需安裝 Python，無需連網。**

## 系統需求

- Windows 10 或以上

## 基本使用

- **專案**：新增、編輯、刪除、切換專案
- **任務**：新增、編輯任務名稱、日期與進度（0～100%）
- **甘特圖**：日／週／月刻度切換，可橫向捲動
- **匯出**：工具列「匯出甘特圖」可儲存 PNG
- **儲存**：編輯後請按「儲存變更」，資料才會寫入檔案

## 資料存放位置

程式會在 `GanttChart.exe` 同層自動建立 `gantt_sys` 資料夾：

| 檔案 | 說明 |
|------|------|
| `sample-data.json` | 專案與任務資料 |
| `ui-settings.json` | 介面設定（如淺色／深色） |
| `about.toml` | 關於資訊 |
| `guide.toml` | 使用指南 |

請定期備份 `gantt_sys` 資料夾。

## 注意事項

- 請勿只複From複製 `GanttChart.exe`，需保留整個 `GanttChart` 資料夾
- 更新版本時，可先備份舊版 `gantt_sys` 再覆蓋程式檔
- 本程式為離線使用，資料僅存於本機

## 版本

目前最新版本請見 [Releases](../../releases) 頁面。
