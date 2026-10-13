# 國小寫字簿

國小一到六年級國語寫字練習網頁（可切換康軒、翰林、南一版，1 到 6 年級上下學期），可加到手機主畫面使用。

- 筆順資料：教育部「常用國字標準字體筆順學習網」（教育部版權，僅供個人學習，不得用於商業用途）
- 讀音錄音：[audio-cmn](https://github.com/hugolpz/audio-cmn)（CC BY-SA）
- 筆順動畫：[Hanzi Writer](https://github.com/chanind/hanzi-writer)（MIT）

- 進入網頁需輸入密碼（前端驗證，只能擋一般使用者，不是真正的存取控制）
- 各版本課名與生字（含認讀字）取自教育部教育百科「生字詞彙表」（國家教育研究院，114 學年度），請以課本為準
- 密碼連續錯 5 次會暫停 10 分鐘（僅前端，不是真正的存取控制）

## 版權與來源

完整的資料來源、作者與授權請見 [credits.html](credits.html)。Arphic Public License 全文見 [licenses/ARPHICPL.txt](licenses/ARPHICPL.txt)。
本專案與康軒、翰林、南一無關，非官方；如有侵權疑慮請到 Issues 留言，將儘速處理。

## 關於加密

筆順、課表與程式主體以密碼加密後存放於本 repo（`app.enc`、`c/*.enc`），讀音錄音（`a/`、`w/`，CC BY-SA）維持公開。本 repo 不含明文資料與建置工具。
