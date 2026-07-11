# Kiwi AIGC 互動程式作品集

這是一組可發布到 GitHub Pages 的 HTML5 互動作品集，包含 AIGC 譜面生成、音訊分析、AI 編譜沙盒與多個遊戲化互動範例。

本版本彙整：

- 9 個 Kiwi 原始互動作品
- 7 個 HTML5 Canvas 遊戲
- 共 16 個作品
- 1 個範例音樂檔

## 發布版整理重點

- 根目錄已建立 `index.html` 完整入口頁。
- 所有作品整理到 `apps/` 底下，並使用英文資料夾名稱，避免 GitHub Pages 中文路徑造成 404。
- 排除 Windows 捷徑檔 `osu!(lazer).lnk`。
- 保留範例音樂檔於 `assets/audio/phigros-distorted-fate-sakuzyo-official.mp3`。
- 音樂相關工具頁已加入右下角「範例音樂檔：下載 MP3」連結。
- 匯出 `.osu` 時的預設音訊檔名已改為 `phigros-distorted-fate-sakuzyo-official.mp3`。
- 所有 HTML 皆以 UTF-8 檢查，首頁無亂碼。

## AIGC 譜面生成與音訊工具

| 作品 | 路徑 |
|---|---|
| AIGC 自動譜師測試系統 | `apps/aigc-auto-mapping-agent/` |
| AIGC 隨機多變性編譜沙盒 | `apps/ai-random-mapper/` |
| AI 聽音辨識自動編譜工作台 | `apps/audio-ai-mapper/` |
| AIGC Auto-Mapping 互動工作台 | `apps/interactive-mapping-workbench/` |
| AIGC 譜面生成與測試沙盒 | `apps/osu-ai-sandbox/` |

## 遊戲化互動範例

| 作品 | 路徑 |
|---|---|
| 治癒系多肉植物溫室 | `apps/zen-succulent-greenhouse/` |
| 午餐爭奪戰：福利社衝鋒 | `apps/cafeteria-dash-agent/` |
| 歐帕小精靈的期末大作戰 | `apps/all-pass-sprite-agent/` |
| 太空探險者 | `apps/space-adventurer-shooter/` |
| 星際防線 | `apps/01-starfleet-defense/` |
| 心光泡泡 | `apps/02-heart-bubbles/` |
| 智慧校園導覽員 | `apps/03-smart-campus-guide/` |
| 知識星球探險 | `apps/04-knowledge-planet-rag/` |
| 夢想畫布 | `apps/05-dream-canvas/` |
| 星光音樂盒 | `apps/06-starlight-music-box/` |
| 彩虹節奏島 | `apps/07-rainbow-rhythm-island/` |

## 發布到 GitHub Pages

1. 將本資料夾內容推送到 GitHub repository。
2. 到 repository 的 `Settings`。
3. 開啟 `Pages`。
4. Source 選 `Deploy from a branch`。
5. Branch 選 `main`，Folder 選 `/root`。
6. 儲存後等待部署完成。
