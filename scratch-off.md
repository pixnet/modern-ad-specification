# Scratch-off
## 程式範例
```
<div
    data-hashid=""
    data-click-url=""
    data-file=""
    data-file2=""
    data-videofile=""
    data-videofile-poster=""
    data-video-callback-url=""
    data-video-align=""
>
<!-- Your script -->
</div>
```

## 屬性說明
 - data-hashid: 廣告代碼
 - click-url: 點擊圖片後導向連結
 - file: 第一層 素材檔案，.png / .jpg / .gif / .html / .htm 請依據副檔名來判斷呈現的方式，其中 .html/.htm 以 iframe 方式載入
 - file2: 第二層 素材檔案，同第一層素材說明
 - videofile 第二層影片素材檔案
 - videofile-poster: 影音專用，影片截圖 URL（如果沒傳就不設定）
 - video-callback-url: 影音專用，影音進度 API 的位置，需要加上 &t=秒數/比例，回傳進度資料，當秒數為 5秒/10秒/50%/70%/100% 就回傳一次，只需要數字的部分，例如 50 % 就回傳 50
 - video-align: 影片擺放位置（請依UI設計擺放）
   - left：靠左、靠上、靠左上
   - center：置中
   - right：靠右、靠下、靠右下
