# 學習星球

國小低年級互動教材入口：https://abulaboy.github.io/kids-planet/

## 注音星球
- [康軒首冊版](https://abulaboy.github.io/kids-planet/zhuyin/)：`zhuyin/index.html`
- [一般版](https://abulaboy.github.io/kids-planet/zhuyin/general/)：`zhuyin/general/index.html`
- 舊網址 `/general/` 會自動轉到新位置。
- 錄音在 `audio/`（教育部真人注音錄音 CC BY 4.0、語音合成），兩個注音頁共用。

## 英文星球
- [英文星球](https://abulaboy.github.io/kids-planet/english/)：`english/index.html`
- ABC 字母、生活單字（顏色、數字、動物、水果、身體）、聽音選圖。
- 發音用瀏覽器內建語音（speechSynthesis），不需要錄音檔。
- [課本短母音](https://abulaboy.github.io/kids-planet/english/phonics2/)：`english/phonics2/index.html`，學校自然發音第 2 冊（短母音）Unit 1–8 的單字與常見字例句。玩法：單字卡、聽聽看、拼拼看（缺字母）、句子（填常見字）。單字資料在檔案開頭的 `UNITS`，圖片用表情符號，不放課本掃描圖。

## 拆解星球
- [七星瓢蟲](https://abulaboy.github.io/kids-planet/teardown/)：`teardown/index.html`
- 給幼稚園大班、小一的 3D 拆解頁。簡單幾何體組成的七星瓢蟲，可轉動、縮放、拆開再合起來，點部位會顯示注音和說明，並用瀏覽器 zh-TW 語音朗讀。含 5 題點選問答。
- 注音字形是 Noto Sans TC 子集（`teardown/fonts/`，SIL OFL）。

## 新增一個區
1. 建一個資料夾放 `index.html`（例如 `math/`）。
2. 在根目錄 `index.html` 加一個 `<section class="area">` 區塊和卡片。
3. 頁面左上角放「🪐 星球」按鈕連回 `../`。
