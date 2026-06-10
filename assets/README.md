# assets｜網站圖片資料夾

## hero-photo.jpg（Hero 主視覺背景照片）

請將去年公民參與活動的現場照片放入本資料夾，檔名固定為 **`hero-photo.jpg`**。

### 照片要求

- 寬度 **1920px** 即可，不需更大
- 檔案大小請壓縮至 **300KB 以下**（推薦免費工具：https://squoosh.app）
- 建議另存一份 WebP 格式（`hero-photo.webp`），之後可在 index.html 用 `<picture>` 或 CSS `image-set()` 提供 fallback，進一步加速載入

### 注意

- 照片尚未放入前，Hero 區會自動顯示原本的深藍底色（fallback），版面不受影響
- 照片放入後需重新 `git add` → `commit` → `push` 才會出現在線上網站
