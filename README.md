# Happy Anniversary 💕

Thiệp kỷ niệm 6 năm (26.10.2020 – 26.10.2026), tông hồng, chủ đề mèo. Một file `index.html` tĩnh, không cần build.

## Sửa nội dung
Mở `index.html`, tìm khối `Nội dung (sửa ở đây)` trong thẻ `<script>`:
- `START`: ngày bắt đầu yêu nhau (tháng tính từ 0, nên tháng 10 là `9`)
- `MESSAGE`: lời chúc

Tiêu đề, ngày tháng và chữ ký nằm trong phần HTML `<main id="card">`.

## Deploy
```bash
npx vercel login
npx vercel --prod
```
Hoặc push lên GitHub rồi Import repo trên vercel.com (Framework: Other, không cần build command).
