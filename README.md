# ckeditor5-editor-insertImgs

功能:
插入圖片自動轉base64，且圖片資訊會存入
editor.insertImgs [{ name, ext, mime, base64str }]
（base64str 是 <img src="image/jpeg;base64,yyyyy"> 的 yyy 部分）

若刪除插入的圖片，圖片資訊也會自動從 editor.insertImgs 刪除
