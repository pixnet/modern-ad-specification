# Slider
## 程式範例
```
<div
    data-hashid=""
    data-file=""
    data-click-url=""
    data-video-callback-url=""
>
<!-- Your script -->
</div>
```

## 屬性說明
 - data-hashid: 廣告代碼
 - data-file: 素材檔案，多個檔案 URL，會以空白符號分隔，請以副檔名來區分呈現方式，包含 .jpg .png .gif .bmp .htm .html .mp4 .webm .wmv .mov .mpq .mpeg，其中如果是影片檔案，需要以 data-video-callback-ur 的 API 回傳影音進度，URL 有可能包含 query string ，例如 a.jpg?v=2，檔名的順序依據想呈現的順序排列
 - data-click-url: 點擊圖片/HTML後導向連結
 - data-video-callback-url: 影音專用，影音進度 API 的位置，需要加上 &t=秒數/比例，回傳進度資料，當秒數為 5秒/10秒/50%/70%/100% 就回傳一次，只需要數字的部分，例如 50 % 就回傳 50
