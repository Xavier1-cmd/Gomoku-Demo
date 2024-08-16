# Gomoku-Demo 五子棋小遊戲[專案練習]

### 參考教程：
  - [小山的 C# 教學-第46課-五子棋小遊戲(七)-簡單勝利判斷](https://slmtsite.blogspot.com/2018/01/c-46.html)

### YouTube：
  1. [Part1](https://youtu.be/kL1KG-bitG4?si=oqM-GRIFdmf5DECb)
  2. [Part2](https://youtu.be/_0ZC7TJUBCQ?si=frWtLWoB9qsYtC4v)
  3. [Part3](https://youtu.be/2VzO76N74ao?si=0fJE2TTLItnWUXme)
  4. [Part4](https://youtu.be/apQrPURLYZU?si=ARHr0PF8U5yhMv9a)
  5. [Part5](https://youtu.be/yzljXSB6Urw?si=_5Noohu263j9DUfe)
  6. [Part6](https://youtu.be/hZx9p9EgI5g?si=E35AyEYpI4snZt5D)
  7. [Part7](https://youtu.be/LSg15Q54TeI?si=cJ46MJOnIyjT0_zm)

## 製作重點
  - 檢查勝利的方式 - 只要檢查最後下的那顆棋子的八個方向是否有五顆棋子連成一直線
  - 在測試程式時，若發生錯誤，可以把滑鼠移到變數上。此時就會顯示該變數的值為多少。
  - 注意在 if 內有多個條件時，若程式發現只要檢查前面的條件就足夠，後面的條件就不會被執行。


## 練習
  - 嘗試解決最後棋子下在五顆連線的中間，而不是邊邊時無法判斷勝利的 bug
  - 嘗試實作重新啟動遊戲的功能
  - 在有人快勝利時提出警告訊息
  - 想出一個方法讓白色自動下子 (例如：最簡單的作法，隨便找個讓白色隨機亂下)
