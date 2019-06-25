# Side Sticker

## 程式範例
```
<link href="Your CSS" rel="stylesheet"/>
<div
    data-hashid=""
    data-click-url="__#CLICK_URL#__" 
    data-video-callback-url="__#VIDEO_CALLBACK_URL#__" 
    data-file=""
    data-file2=""
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
