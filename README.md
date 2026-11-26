# Bách khoa TP.HCM — LaTeX Report Template

Template LaTeX dùng để viết báo cáo học thuật bằng tiếng Việt cho Trường Đại học Bách khoa, ĐHQG-HCM. Các thiết lập dàn trang, bìa, màu sắc và header/footer được giữ trong `style/`; thông tin từng báo cáo được quản lý riêng trong `metadata/metadata.tex`.

## Cấu trúc

```text
.
├── AGENTS.md
├── main.tex
├── metadata/metadata.tex
├── style/
│   ├── config.tex
│   ├── cover_page.tex
│   └── header_footer.tex
├── chapters/
├── bibliography/references.bib
├── figures/
├── tables/
├── appendix/appendix.tex
├── assets/branding/
└── build/                 # PDF và file trung gian sinh ra khi biên dịch
```

## Yêu cầu

- MiKTeX hoặc TeX Live có `pdfLaTeX` và `Biber`.
- `latexmk` để tự chạy các lượt biên dịch cần thiết. Trên Windows với MiKTeX, cần cài Perl riêng.

## Biên dịch

Từ thư mục gốc của repository:

```powershell
latexmk -pdf -outdir=build main.tex
```

PDF được tạo tại `build/main.pdf`. Dừng và dọn file sinh ra bằng:

```powershell
latexmk -C -outdir=build main.tex
```

## Bắt đầu báo cáo mới

1. Cập nhật tên đề tài, môn học, học kỳ và thông tin nộp trong `metadata/metadata.tex`.
2. Viết mỗi chương trong một file riêng dưới `chapters/`, rồi thêm lệnh `\input` tương ứng vào `main.tex`.
3. Đặt hình trong `figures/`, bảng tách riêng trong `tables/`, phụ lục trong `appendix/`.
4. Khai báo nguồn trong `bibliography/references.bib` và trích dẫn trong nội dung.

Class hiện tại là `article` để giữ format gốc; mỗi chương được định dạng bằng `\section`.
