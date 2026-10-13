[README.md](https://github.com/user-attachments/files/33377144/README.md)
# 心流柔術 Xinliu BJJ

**柔術心智圖 ＋ 流程圖 ＝ 心流柔術。** 名稱也對應「心流」：全神貫注、沉浸忘我的狀態，就像比賽中一步接一步的攻防。

這是一個 Gi 巴西柔術的互動戰術圖：從畫面中央的「比賽開始」出發，每一步都會看到 2–3 個附條件說明的下一步，選好後才長出下一格，一路延伸到降伏，規劃出自己的比賽 Game Plan。

**線上使用：<https://ck-x-x.github.io/xinliu-bjj/>**

![心流柔術畫面]<img width="1902" height="986" alt="image" src="https://github.com/user-attachments/assets/ad5ba382-f8c0-48cb-9a9b-2273cb3980b0" />
<img width="1917" height="976" alt="image" src="https://github.com/user-attachments/assets/fb5aeecc-a448-4800-a7cb-1e5c4138b66a" />
<img width="1915" height="980" alt="image" src="https://github.com/user-attachments/assets/3fd5e8e3-ffca-4d52-ae0b-88d46c311350" />




## 主要功能

- **我的路徑**：由中心向外長出路徑，可同時保留多條路徑、從任一格分岔，抵達降伏後選擇保留、隱藏或刪除。
- **技術總覽**：86 項技術依比賽流程分成 7 個家族（站立與摔技、防禦、破勢、過防禦、壓制、防守脫逃、降伏），點家族展開技術列表。
- **教學影片**：每一格都有 ▶ 按鈕，開啟資訊面板，附一支經確認的 YouTube 教學影片、說明，以及可接的下一步與可從哪裡來。
- **禁止技術**：依五個賽事組織（JJIF、IBJJF、SJJIF、AJP、Grappling Industries）與色帶，查詢成人 Gi 組別的禁止與開放技術，每項附官方條文與頁碼。

## 怎麼開始

1. 打開上方網址（桌面瀏覽器效果最好，手機也可以瀏覽）。
2. 點中央閃動的「比賽開始」。
3. 選一張黃框卡片，路徑就會往外長一格；點 ▶ 看教學影片。
4. 任何時候點左上角「心流柔術」LOGO 回到比賽開始。

不需安裝、不需登入。整個網站只有一個 `index.html`，下載後直接雙擊也能在本機使用；只有點影片或官方規則連結時才會連到外部網站。

## 目前限制

- 路徑只存在瀏覽器記憶體中，重新整理後會清空（保存、匯出／匯入、新增與編輯技術規劃在下一版）。
- 禁止技術只收錄成人 Gi 組別；官方文件沒有明確結論的技術不收錄。規則會改版，比賽前請以官方最新規則為準。

## 製作方式

課程作業「用 Vibe Coding 做出一個互動網頁」。以 React 19、React Flow（`@xyflow/react`）開發，用 Vite 與 `vite-plugin-singlefile` 建置成單一 `index.html`，所有程式、資料與圖片都內嵌在檔案裡。

完整功能、驗收方式與設計決策見 [規格書](SPEC規格書%20v1.13.md)。
