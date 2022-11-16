# SEO-Search Engine Optimization (搜尋引擎最佳化)
參考: https://zh.wikipedia.org/wiki/%E6%90%9C%E5%B0%8B%E5%BC%95%E6%93%8E%E6%9C%80%E4%BD%B3%E5%8C%96

### 為什麼要做 SEO? SEO 的優點?

1.SEO 帶來的流量質素相對高     
2.因 SEO 走進來的訪客不會覺得是被廣告吸入而來，相對防禦心較低，轉換率 (Conversion) 會比較高   
  理論上，只有用戶體驗好的網站才有可能排在前列位置。做好 SEO 即是改善了網站的用戶體驗   
3.對一個品牌來說，更多的出現在搜尋者的結果中會令搜尋者對品牌的印像更深    
4.搜尋排名第1 可以更易的告訴搜尋者你就是行業中的一哥    
5.SEO 做得好的話，廣告費可以大減  

### 那些網站適合做SEO?

1.平台類型網站   
2.電商   
3.媒體類型網站   
4.解決別人問題的商品或服務類型網站

### (0) 觀察搜尋結果類型
1.搜尋結果出現的類型來去做   
 如果是文字則處理文字部分   
 如果是圖片則處理圖片部分  
 如果是影片則處理影片部分   

### (1) 選擇關鍵字
 
可使用Google Keyword Planner進行調查    
https://ads.google.com/home/tools/keyword-planner/   
https://www.ringoli.net/wrong_keywords_for_seo/   

### (2) 網站內容結構
很多人選擇了關鍵字以後便會立刻製作內容，   
但別忘了 Google 也要看懂你的內容才算數。

### (3) SEO 網站優化 – Title(標題)

1) 一個長標題 + 一個長描述佔了版面 3 分之 1   
2) 版面大，佢「唔小心」入左黎的機會也比較大   
3) 一般來說 長標題 + 一個長描述 排名會較高   

### (4) SEO 網站優化 – 內容字數

建議圍繞每個關鍵字的文章最少都要有1000字以上。   
不少客戶的網站文字內容比較單薄，導致很多時都要做很多功夫才可以推高排名，  
有時甚至外部工作都沒有任何作用。雖則說現在是圖像主導，  
但搜尋引擎還未能完全像人類般了解圖像，  
所以真的要多加一點內容。  
很多研究顯示，內容越長，排名越高   

### (5) SEO 網站優化 – H設定
參考:https://wp-valley.com/html-headings

### (6) SEO 網站優化 – 連結結構

1. url 的總長度越短越好。   

### (7) 搜尋引擎設定

1.安裝 Google Search Console
參考:https://www.ringoli.net/%e7%94%a8google-search-console%e6%8f%90%e9%ab%98%e6%8e%92%e5%90%8d/

### (8) SEO 優化 – 外部連結
有外部連結對排名有非常正面的作用。

### (9) SEO 優化 – 網站速度
1.GZIP 壓縮令圖片載入速度更快
2.js檔案壓縮

### (10) SEO 優化 – 設計部份
Google 對於用戶體驗的關注越來越高，   
在 Google Analytics 的量度指標不難發現量度訪客行徑的指標。   
當然，這很大部份跟網站結構及設計有關，而當中涉及不少 CSS 知識。   

---

#  Meta tag設定
### 1.title   
是一個網頁的標題，會在瀏覽器的分頁以及搜尋結果顯示。這是一個重要的標籤，讓搜尋引擎和用戶了解網頁的內容。     
```
  <title>よしのん的網站教室 | 集合科技新聞、網站制作、SEO、社交媒體經營的文章</title>
```
### 2.description   
description 雖然都有字數限制，但彈性就大得多，會視乎關鍵字而改變長度。    
如 description 的字眼與搜尋字眼吻合，就會以另一種顏色突顯。因此，description 的內容亦值得花時間研究以提高點擊率。   
```
<meta name="description"  content="不少人都會在網誌（blog）上加入 AdSense 廣告以賺取額外收入，但到底 AdSense 收入可以達到甚麼水平？這筆收入是不是十分可觀？其實對一般網誌而言，AdSense 的收入只是聊勝於無，如要依賴 AdSense 收入過日子，網站必須極具規模。" />
```
### 3.canonical  
基於多種原因，一個網頁可能會多種網址，為了避免內容重複導致搜尋引擎懲罰，  
每個網頁都應加入 canonical 網址，讓搜尋引擎識別不同網址但網頁內容相同的唯一「標準」網址。  

```
<link rel="canonical" href="https://ysnweb.net/2019/12/web-monetisation/google-adsense-how-much-income/" />
```

### 4.charset
指定瀏覽器展示網頁時的採用的字元編碼，雖然與 SEO 無關，但亦是必要的標籤。現時，   
大部分的網頁都採用 UTF-8，但某些時候會採用其他編碼，如 GBK 等。  
```
<meta charset="UTF-8"> 
```

### 5.viewport
搜尋引擎偏好支援流動裝置的網頁，其中又以回應式網頁設計（Responsive Web Design）最為可取。   
如要網頁在各裝置中正確呈現，就必須有正確的 viewport 設定  
```
<meta name="viewport" content="width=device-width, initial-scale=1"> 
```
### 6.robot
搜尋引擎會透過爬蟲程式（crawler/ spider）讀取網頁資訊，然後為網頁索引。  
一般而言，如果網頁沒有設定 robot 的話，就會接受所有搜尋引擎索引，在搜尋結果出現。   
除非網頁不宜在搜尋引擎中展示，否則毋須使用 robot 標籤。  

然而，Google 已表明 robot 只供參考，並不一定跟從，即使網頁已加入以上標籤，仍有機會在搜尋結果中呈現。  

```
<meta name="robots" content="noindex,nofollow">
```

index vs noindex   

當你不希望搜尋引擎索引此頁面，就填上noindex，若希望正常索引便填上index  

follow vs nofollow   

至於follow這個值是指，若你希望搜尋引擎在檢索此頁面時，不進一步的去檢索該頁面所連出去的連結，你就填上nofollow的值。這個功能通常會用在社群論壇或是網站討論版，是為了防止有人在你的頁面上亂貼連結來意圖增加他的SEO 反向連結及排名，使用nofollow的話搜尋引擎的檢索會在該頁面停止，不繼續往其他連結前進，固可以防止亂貼連結的事情發生。   

### 7.hreflang
如果網頁設有多種語言，就需要 hreflang 來提示搜尋引擎展示正確的網頁給不同地區的訪客。  
```
<link rel="alternate" href="http://example.com" hreflang="en-us" /> 
```

### 8.og
og （Open Graph）並非用於 SEO 中，   
但對網頁於 Facebook、LINE 等社交媒體正確地呈現有莫大幫助，   
其中 og:title、og:description、og:image 至為重要，  
分別決定了網頁於社交媒體分享時顯示的標體、形容和縮圖。  

Facebook、Plurk、LINE example
```
<meta property="og:type" content="article" />
<meta property="og:title" content="Google AdSense 可以帶來多少「被動收入」？（附記錄）" />
<meta property="og:description" content="不少人都會在網誌（blog）上加入 AdSense 廣告以賺取額外收入，但到底 AdSense 收入可以達到甚麼水平？這筆收入是不是十分可觀？其實對一般網誌而言，AdSense 的收入只是聊勝於無，如要依賴 AdSense 收入過日子，網站必須極具規模。" />
<meta property="og:url" content="https://ysnweb.net/2019/12/web-monetisation/google-adsense-how-much-income/" />
<meta property="og:site_name" content="よしのん的網站教室" />
<meta property="og:image" content="https://i0.wp.com/ysnweb.net/wp-content/uploads/2019/09/adsense.jpeg?fit=900%2C450&ssl=1" />
```
Twitter example

```
<meta name="twitter:card" content="summary" />
<meta name="twitter:title" content="Google AdSense 可以帶來多少「被動收入」？（附記錄）" />
<meta name="twitter:description" content="不少人都會在網誌（blog）上加入 AdSense 廣告以賺取額外收入，但到底 AdSense 收入可以達到甚麼水平？這筆收入是不是十分可觀？其實對一般網誌而言，AdSense 的收入只是聊勝於無，如要依賴 AdSense 收入過日子，網站必須極具規模。" />
<meta name="twitter:image" content="https://i0.wp.com/ysnweb.net/wp-content/uploads/2019/09/adsense.jpeg?fit=900%2C450&ssl=1" />
```

### 9.keywords
這本來是讓搜尋引擎了解網頁關鍵字的標籤，但由於遭到濫用，  
Google 早在 2009 就不再理會。縱使大家仍然可以使用，但不會有實質幫助。  
事實上，細心留意位居前列的網頁背後的 HTML，亦可見已沒有 keywords。  
```
<meta name="keywords" content="HTML,CSS,XML,JavaScript">
```
