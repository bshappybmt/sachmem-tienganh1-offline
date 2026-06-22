# 📚 Tiếng Anh 1 - Global Success (Offline Viewer)

Trải nghiệm học tiếng Anh lớp 1 **offline như online** — toàn bộ nội dung từ sachmem.net được đóng gói trong một trang web tĩnh, mở được trực tiếp bằng trình duyệt.

## 🚀 Cách dùng

### Online
Truy cập: **https://bshappybmt.github.io/sachmem-tienganh1-offline/**

### Offline
1. Clone repo này về máy
2. Mở file `index.html` bằng Chrome/Edge/Firefox
3. Không cần internet, không cần cài thêm gì

## 📂 Cấu trúc

```
sachmem_tienganh1/
├── index.html         ← Web app chính (83KB SPA)
├── exercises.json     ← Metadata 190 bài tập
├── book_metadata.json ← Cấu trúc sách gốc
├── audio/             ← 530 file MP3 (69MB) — tất cả bài nghe
├── images/            ← 507 file PNG — hình minh họa bài tập
└── README.md
```

## ✨ Tính năng

- **Điều hướng cây** — Unit → Lesson → Exercise
- **Audio player** — nghe trực tiếp từng file
- **Image gallery** — xem ảnh, click phóng to
- **Tìm kiếm** — gõ tên bài là ra ngay
- **Bài trước/bài tiếp** — chuyển nhanh giữa các bài
- **Nhớ vị trí** — lần sau mở lại vẫn ở bài cũ (localStorage)
- **Responsive** — xem trên điện thoại thoải mái

## 📊 Nội dung

- **24 đơn vị học**: 16 Units + 4 Fun time + 4 Review
- **190 bài tập** đầy đủ
- **530 audio files** — phát âm, bài hát, bài nghe
- **507 images** — minh họa cho từng bài tập

## 🛠️ Technical

- Vanilla JS SPA (zero dependencies)
- Data embedded trực tiếp trong HTML (không fetch)
- Audio/Images served từ GitHub repos
- GitHub Pages deployment

## Nguồn

Dữ liệu được tải từ [sachmem.net](https://sachmem.net) — nền tảng sách giáo khoa điện tử của Nhà xuất bản Giáo dục Việt Nam.
