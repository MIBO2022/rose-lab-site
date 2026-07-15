# Rose Lab 網站成品

這份資料夾已經完成網站基本架構，你不需要從零寫程式。

## 第一次在電腦預覽
1. 安裝 Node.js LTS。
2. 用 VS Code 開啟此資料夾。
3. 在「終端機」依序輸入：
   npm install
   npm run dev
4. 打開終端機顯示的網址。

## 上線前只需要改 3 個地方
1. `astro.config.mjs`：把 `site` 改成你的正式網址。
2. `src/pages/about.astro`：改成你與女兒的真實介紹。
3. `src/content/blog/`：把範例文章中的提示文字換成真實內容。

## 新增文章
複製 `src/content/blog/tutorjr-10-lessons.md`，改檔名、標題、日期與內文即可。

## Cloudflare Pages 設定
- Build command：`npm run build`
- Build output directory：`dist`
- Node.js：20 或以上

## 注意
不要把孩子姓名、學校、住址、固定行程或可辨識個資放到公開網站。
