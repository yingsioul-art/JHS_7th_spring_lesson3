# 部署到 GitHub Pages — L3「How Do You Celebrate the New Year?」學習系統

## 一次性設定

1. **建立 Repository**
   - github.com → New repository
   - Name: `english-class`（只用英文）
   - Public + Add README

2. **上傳檔案**
   - Add file → Upload files
   - 拖入 `./output/` 裡的所有 `.html` 檔案
   - Commit changes

3. **啟用 Pages**
   - Settings → Pages → Branch: `main` / `(root)` → Save
   - 等 1-2 分鐘

4. **取得網址**
   - `https://<username>.github.io/english-class/`

## 給學生的訊息（複製貼上）

```
📚 英文學習系統 — L3 How Do You Celebrate the New Year?

🔗 網址：https://<username>.github.io/english-class/

📱 學習順序：
1. 📚 課程學習（單字卡 / 對話 / 課文）
2. 🪜 Bloom 六層次練習
3. 🗣️ 對話應用練習（與外國人對話的實戰）
4. 🔴 段考模式刷題
5. 🔵 會考模式刷題
6. 🧪 綜合診斷 → 看弱點報告

⚠️ 不要用無痕模式（無法儲存進度）
```

## 故障排除

| 症狀 | 解法 |
|------|------|
| 404 | 確認 index.html 在 root |
| 連結壞掉 | 用相對路徑 |
| 改了沒更新 | Ctrl+Shift+R 強制重新整理 |
