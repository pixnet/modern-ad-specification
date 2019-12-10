# Side Sticker

## 程式範例
```
<link href="Your CSS" rel="stylesheet"/>
<div
    data-hashid=""
    data-click-url="__#CLICK_URL#__" 
    data-video-click-url="__#VIDEO_CLICK_URL#__"
    data-video-callback-url="__#VIDEO_CALLBACK_URL#__" 
    data-videofile-poster=""
    data-file=""
    data-file2=""
    data-videofile=""
>
<!-- Your script -->
</div>

```

## 屬性說明
- data-hashid: 廣告代碼
- data-click-url: 點擊圖片後導向連結
- data-video-callback-url: 影音專用，影音進度 API 的位置，需要加上 &t=秒數/比例，回傳進度資料，當秒數為 5秒/10秒/50%/70%/100% 就回傳一次，只需要數字的部分，例如 50 % 就回傳 50
- data-file: Side image 素材檔案(.png)
- data-file2: Banner 素材檔案，會有圖像、HTML/.zip 檔
- data-video-click-url: 影音專用，影音點擊
- data-videofile-poster: 影音專用，影片截圖 URL（如果沒傳就不設定）
- data-videofile: 影音專用，影音素材
