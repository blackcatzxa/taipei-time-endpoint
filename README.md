# Taipei Time Endpoint

每 5 分鐘自動更新一次 `now.json`，提供當前 **台北時間 (Asia/Taipei)** 與時間戳記。

- 原始 JSON：`now.json`
- Raw URL（給外部讀取）：`https://raw.githubusercontent.com/<USER>/<REPO>/main/now.json`

## 欄位說明
- `source`: "GitHub Actions (cron)"（產生來源）
- `timezone`: "Asia/Taipei"
- `taipei_iso`: ISO-8601 格式的台北時間（含 UTC+08:00 偏移）
- `unix`: 秒級 UNIX 時戳
- `generated_utc`: 產生當下的 UTC 時間
- `generated_taipei`: 產生當下的台北時間
- `version`: 結構版本
