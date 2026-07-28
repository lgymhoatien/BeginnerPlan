# L GYM · Beginner Plan

Site: https://lgymhoatien.github.io/BeginnerPlan/

## Cấu trúc (up nguyên folder này lên repo GitHub Pages)

```
github-BeginnerPlan/
├── index.html              # App chính
├── manifest.webmanifest    # PWA — tên app, icon, mở fullscreen
├── sw.js                   # Service Worker — cache + hỗ trợ "Cài app"
├── .nojekyll               # Cho GitHub Pages phục vụ file tĩnh đúng
├── icons/
│   ├── icon-192.png        # Icon màn hình chính (iOS / Android)
│   └── icon-512.png        # Icon PWA lớn
└── README.md
```

## Cách up lên GitHub

1. Mở repo `BeginnerPlan` (hoặc repo đang dùng cho GitHub Pages).
2. **Xóa / thay** các file cũ bằng đúng nội dung folder này (giữ cấu trúc như trên).
3. Commit + Push lên nhánh mà Pages đang dùng (thường là `main` / `gh-pages`).
4. Đợi 1–2 phút, mở lại: https://lgymhoatien.github.io/BeginnerPlan/
5. Hard refresh trên điện thoại (hoặc xóa cache site) rồi thử **Thêm vào màn hình chính**.

## Không cần up

- `lich-tap-ppl.html` (bản dev — đã sync sang `index.html`)
- `site/` (API backend Cloudflare — không dùng cho Pages tĩnh này)
- file `_fix_*.py`, `ev_push.json`, bản Copy…
