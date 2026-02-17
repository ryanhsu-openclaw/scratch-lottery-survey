# 過年刮刮樂戰績調查

靜態問卷網站，用來收集大家過年買刮刮樂的金額、實際中獎金額，幫你算出：
- 這次過年你是「財神」還是「贊助商」
- 大約贏過多少比例的其他填答者

網站網址（GitHub Pages）：

👉 https://ryanhsu-openclaw.github.io/scratch-lottery-survey/

## 技術架構

- 純前端：HTML + CSS + 原生 JavaScript
- 後端資料收集：預計透過 Google Apps Script + Google Sheets
- 部署：GitHub Pages，純靜態，不需要任何 Python / Node 後端

## 待辦

- [ ] 將刮刮樂類型選項改為依照台彩官方遊戲名稱
- [ ] 串接 Google Apps Script 寫入 Google Sheets
- [ ] 用 Sheets 統計分布，改掉現在的模擬百分位
