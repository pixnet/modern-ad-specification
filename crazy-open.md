# Crazy Open

## 程式範例
```
<link href="Your CSS" rel="stylesheet"/>
<div
    data-hashid=" " 
    data-file=" "
    data-file2=" " 
    data-file3=" "
    data-file4=" " 
    data-click-url="__#CLICK_URL#__" 
    data-video-callback-url="__#VIDEO_CALLBACK_URL#__" >
<script src="Your Script" async></script>
</div>
```

## 屬性說明
- data-hashid: 廣告代碼
- data-file: 第一層素材檔案 
- data-file2: 蓋板素材
- data-file3: 蓋板後出的素材檔案
- data-file4: 影音用的 banner
- data-click-url: 點擊圖片後導向連結
- data-video-callback-url: 影音專用，影音進度 API 的位置，需要加上 &t=秒數/比例，回傳進度資料，當秒數為 5秒/10秒/50%/70%/100% 就回傳一次，只需要數字的部分，例如 50 % 就回傳 50
