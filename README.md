# 恩典島 Grace Island

60 則兒童聖經故事蓋成的 3D 玩具小城。14 座六角形故事島按聖經順序排成螺旋，木橋相連，終點是中央的「新天新地」。

網站創作：**@ritakao**

## 功能

- **3D 互動島嶼**：拖曳旋轉、滾輪或雙指縮放，點建築閱讀故事
- **和合本金句**：每則故事配一節經文，可複製、可連到上下文
- **注音切換**：標題、摘要、金句可顯示注音，設定會記在瀏覽器
- **人物索引**：37 位聖經人物，點選後在島上標出他們的故事
- **聖經時間軸**：依年代排列 60 則故事，可自動播放
- **耶穌再來與新天新地**：時間軸最後一站，同一頁先講耶穌再來（駕雲降臨、天使環繞、號角響起、聖徒被提四個畫面，以溫暖平和的光呈現），再講新天新地
- **恩典線**：連起新舊約前後呼應的故事
- **即時天空**：天色跟著台北時間從清晨變到夜晚
- **搜尋**：可搜故事標題、摘要、經文內容

## 使用方式

整個網站只有一個 `index.html`，不需要建置。

- 本機：直接用瀏覽器打開 `index.html`
- GitHub Pages：Settings → Pages → Source 選 `Deploy from a branch`，Branch 選 `main` / `root`，存檔後約一分鐘即可在 `https://<帳號>.github.io/<專案名>/` 瀏覽

## 資料來源與授權

- 故事標題、經文段落與 PDF 連結：[兒童聖經故事 Bible for Children](https://bibleforchildren.org/languages/chinese_traditional/stories.php)。其材料限非商業用途免費使用；如作公開或商業用途，請先向對方確認授權。
- 和合本經文（繁體，公版）：取自 [scrollmapper/bible_databases](https://github.com/scrollmapper/bible_databases)。
- 故事摘要、人物介紹為本專案自行撰寫。
- 年代為傳統估算，部分年代學界看法不一。
- 注音由程式產生並人工校正常見多音字，人名地名讀音如有出入歡迎回報。
- 使用 [three.js](https://threejs.org/) r128（MIT）、Google Fonts 霞鶩文楷 TC 與 Noto Sans TC（SIL OFL）。
