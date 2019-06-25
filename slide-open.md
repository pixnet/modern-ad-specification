# Slide Open

## 程式範例
```
<script>
var curScriptElement = document.currentScript;
curScriptElement.parentNode.style.width = 'auto';
curScriptElement.parentNode.style.height = 'auto';
</script>

<link rel="stylesheet" type="text/css" href="Your CSS">
<div
data-hashid=""
data-type=""
data-file=""
data-vediofile=""
data-click-url="__#CLICK_URL#__"
data-video-align=""
data-video-callback-url="__#VIDEO_CALLBACK_URL#__"
>
<script src="Your Script" async></script>
</div>
```

## 屬性說明
- data-hashid: 廣告代碼
- data-type: 素材類型有下列的幾種
  - video：影音＋背景圖
  - image：圖像
- data-click-url: 點擊圖片後導向連結
- data-file: 圖片檔案
- data-videofile: 影音專用，影片 URL
- data-video-callback-url: 影音專用，影音進度 API 的位置，需要加上 &t=秒數/比例，回傳進度資料，當秒數為 5秒/10秒/50%/70%/100% 就回傳一次，只需要數字的部分，例如 50 % 就回傳 50
- data-video-align: 影片擺放位置（請依UI設計擺放）
  - top: 靠上
  - bottom: 靠下
