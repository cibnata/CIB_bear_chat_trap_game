# 刑事Bear：聊天陷阱搜查線

這是整理後的專案版本：HTML 只保留程式與文字，圖片已移到 `assets/`，CSV 原始案例資料放在 `data/`。

## 專案結構

```text
anti_fraud_game_project/
├── index.html
├── assets/
│   ├── logo.png
│   ├── bear-mascot.png
│   └── avatars/
│       ├── player-female.png
│       ├── player-male.png
│       └── avatar-*.png
├── data/
│   └── case_summary_list.csv
└── ASSET_MANIFEST.md
```

## 使用方式

直接開啟 `index.html` 即可執行遊戲。若要部署到 GitHub Pages 或 Vercel，請整個資料夾一起上傳，保留 `assets/` 與 `data/` 的相對路徑。

## 注意

`data/case_summary_list.csv` 是原始案例資料庫，檔案較大。如果只是部署給玩家玩遊戲，且不需要前端讀取 CSV，可以暫時不放上線；若要保留生成資料來源，可放在專案資料夾或倉庫中。
