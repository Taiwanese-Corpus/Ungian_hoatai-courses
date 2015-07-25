# 華台語文對譯
這個專案是備份楊允言老師在臺中教育大學所開的華台語文對譯課程資料，資料來源分別為：

* [2012](https://sites.google.com/site/2012shoatai/)
* [2013](https://sites.google.com/site/2013shoatai/)
* [2014](https://sites.google.com/site/2014shoatai/)

## 網頁結構
使用前請先向允言老師申請權限。

以2013的為例，目錄有：
```
https://sites.google.com/site/2013shoatai/system/app/pages/admin/pagelisting
https://sites.google.com/site/2013shoatai/system/app/pages/admin/pagelisting?offset=50
```
每50篇一頁。會列出每篇文章以及文章修改版本數，其中文章修改版本的目錄網址為：
```
https://sites.google.com/site/2013shoatai/system/app/pages/admin/revisions?wuid=wuid:gx:2a767f60ece1eebe
https://sites.google.com/site/2013shoatai/system/app/pages/admin/revisions?wuid=wuid:gx:2a767f60ece1eebe&offset=10
```
其中`wuid=wuid:gx:2a767f60ece1eebe`即是文章編碼

若要取得特定版本的文章內容，網址只要加上`rev1`參數，格式如下：
```
https://sites.google.com/site/2013shoatai/system/app/pages/admin/compare?wuid=wuid:gx:2a767f60ece1eebe&rev1=19
```
