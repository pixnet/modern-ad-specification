# Backdrop

## 程式範例
```
<div
    data-type=""
    data-click-url=""
    data-file=""
    data-videofile=""
    data-videofile-poster=""
    data-video-callback-url=""
    data-video-align=""
>
<!-- Your script -->    
</div>
```

## 屬性說明
- data-type: 素材類型有下列的幾種
  - video：影音＋背景圖
  - image：圖像

- data-click-url: 點擊圖片後導向連結
- data-file: 圖片檔案
- data-videofile: 影音專用，影片 URL

- data-videofile-poster: 影音專用，影片截圖URL（如果沒傳就不設定）
- data-video-callback-url: 影音專用，影音進度 API 的位置，需要加上 &t=秒數/比例，回傳進度資料，當秒數為 5秒/10秒/50%/70%/100% 就回傳一次，只需要數字的部分，例如 50 % 就回傳 50
- data-video-align: 影片擺放位置（請依UI設計擺放）
  - left：靠左、靠上、靠左上
  - center：置中
  - right：靠右、靠下或靠右下
