# Quy tắc cho AI Agent

## Viết báo cáo

- Mặc định viết bằng tiếng Việt, văn phong học thuật, rõ ràng và nhất quán thuật ngữ.
- Không tự tạo số liệu, kết quả thực nghiệm, trích dẫn hoặc thông tin cá nhân. Nếu thiếu dữ liệu, để chỗ trống và hỏi người dùng.
- Dùng một file `.tex` cho mỗi chương trong `chapters/`. Class hiện tại là `article`, vì vậy tiêu đề chương dùng `\section`; không đổi sang `report` hoặc `book` vì sẽ làm thay đổi format.
- Đặt nhãn ngay sau tiêu đề hoặc caption. Dùng tiền tố dễ nhận biết như `sec:`, `fig:`, `tab:`, `eq:` và `app:`.
- Mọi tài liệu được trích dẫn phải có entry trong `bibliography/references.bib`; không bịa DOI, URL, tác giả hoặc năm xuất bản.
- Đặt ảnh trong `figures/`; đặt bảng lớn hoặc bảng dùng lại trong `tables/`; đặt nội dung phụ lục trong `appendix/`.
- Dùng `\input{...}` để ghép các file nội dung. Giữ `main.tex` làm entry point và nơi quy định thứ tự các phần.

## Metadata và format

- Chỉnh thông tin báo cáo trong `metadata/metadata.tex`, không chèn thông tin cá nhân trực tiếp vào style.
- Danh sách nhóm trên bìa được tạo bởi `\studentrows` trong metadata; thêm một hàng gồm tên và MSSV cho mỗi thành viên. GVHD là thông tin riêng bên dưới tên đề tài.
- Giữ các file nguồn ở UTF-8. Template dùng `pdfLaTeX` và encoding T5 cho tiếng Việt; không đổi compiler hoặc thứ tự encoding nếu chưa xác nhận khả năng hiển thị tiếng Việt.
- Không sửa `style/config.tex`, `style/cover_page.tex`, `style/header_footer.tex` hoặc logo/thương hiệu trừ khi người dùng yêu cầu thay đổi trình bày.
- Giữ nguyên các thông số bố cục, kiểu tiêu đề, màu sắc và cách trình bày bìa hiện có khi chỉ viết nội dung.

## Biên dịch và file sinh ra

- Lệnh build từ thư mục gốc: `latexmk -pdf -outdir=build main.tex`.
- Dùng `latexmk` để tự chạy `pdfLaTeX` và Biber khi cần. Trên Windows, `latexmk` của MiKTeX yêu cầu Perl.
- Không sửa thủ công các file trong `build/`; đây là output được tạo lại khi biên dịch.
- Khi thay đổi cấu trúc file, cập nhật các đường dẫn `\input`, bibliography và README tương ứng.
