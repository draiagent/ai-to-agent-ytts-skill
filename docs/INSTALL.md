# 安裝與 GitHub 發表

## 上傳 GitHub

1. 解壓縮 `ai-to-agent-ytts-skill.zip`。
2. 在 GitHub 建立名稱為 `ai-to-agent-ytts-skill` 的專案。
3. 將解壓縮資料夾內的檔案與子資料夾上傳至專案根目錄；根目錄應直接看到 `README.md`。
4. 確認 `skills/ytts-skill/SKILL.md`、介面設定與相關資源均已上傳。
5. 發表前檢查 LICENSE 是否符合您的分享意圖。此套件預設保留所有權利。

本套件只準備發表檔案，不代表已建立 GitHub 專案或公開發布。

## 安裝技能

將 `skills/ytts-skill` 完整資料夾匯入目標 Agent 平台的技能管理功能，或交由該平台的技能安裝器安裝。安裝入口與支援方式以目標環境為準；不要將整個 GitHub 專案根目錄當成技能資料夾。

若平台不支援技能安裝，可將 `SKILL.md` 的工作規則作為任務指令，並另行提供可讀取的來源。這不等於安裝，也不增加工具能力。

## 第一次驗收

提供 `examples/sample-input.srt` 並呼叫 `ytts-skill`。檢查結果是否保留全部語句、轉為繁體中文、只有一個標題、沒有摘要，且文末署名正確。標題不必和示例完全相同。
