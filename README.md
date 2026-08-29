# 🌐 SUBTITLE GLOSSARY HUB (COMMUNITY DRIVEN)
> **Kho Lưu Trữ & Đóng Góp Mở Cho Bảng Thuật Ngữ, Phong Cách Dịch Thuật & Cạm Bẫy Lỗi Subtitle**

---

## 🏛️ Cấu Trúc Đóng Góp (Repository Architecture)

```text
subtitle-glossary-hub/
├── genres/                                # 1. Quy tắc & Phong cách theo THỂ LOẠI PHIM
│   ├── mecha-robot/                       # Anime Mecha / Siêu Robot (Wataru, Gundam...)
│   ├── detective-mystery/                 # Trinh thám / Hình sự (Kindaichi, Conan, Monster...)
│   ├── medical-drama/                     # Y khoa / Phẫu thuật (Black Jack...)
│   ├── xianxia-wuxia-historical/          # Cổ trang / Tiên hiệp (Phong Thần, Tây Hành Kỷ...)
│   └── slice-of-life-folklore/            # Đời thường / Huyền bí (Mushishi, Mononoke...)
│
├── franchises/                            # 2. Đóng góp theo TỪNG PHIM CỤ THỂ
│   ├── Black_Jack_{tvdb-78864}/           # TV Series
│   ├── Black_Jack_The_Movie_1996_{tmdb-54378}/ # Movie
│   └── ...
│
└── INDEX.json                             # Chỉ mục tự động hỗ trợ tra cứu theo TVDB/TMDb ID
```

---

## 🤝 Cách Đóng Góp (Contributing Guidelines)

1. **Đóng góp bộ phim mới:**
   * Tạo thư mục trong `franchises/<Tên_Phim>_{tvdb-ID hoặc tmdb-ID}/`
   * Bổ sung `glossary.json` và `ERRORS_AND_PITFALLS.md` (nhật ký các lỗi cần tránh).
2. **Đóng góp thuật ngữ thể loại:**
   * Cập nhật vào thư mục `genres/<the_loai>/common_terms.json` hoặc `rules.md`.
3. **Mở Pull Request:**
   * Gửi PR để được merge tự động vào kho cộng đồng chung!
