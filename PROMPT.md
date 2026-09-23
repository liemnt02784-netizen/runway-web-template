# Prompt mẫu để vibe code

Copy nguyên khối dưới đây, dán vào AI bạn đang dùng (Claude, Gemini, Cursor, v.v.). Nhớ mở AI **ngay trong thư mục repo này** để nó đọc được asset.

---

## Prompt khởi tạo

```
Tôi đang làm một trang web giới thiệu câu lạc bộ IT tên Runway (thuộc GDG on Campus,
Đại học Hoa Sen) để dự thi.

Hãy đọc trước 3 file trong repo này:
- BRAND.md  — màu, font, quy tắc dùng logo. Phải tuân thủ tuyệt đối.
- CONTENT.md — nội dung chữ về CLB. Dùng đúng nội dung này, đừng bịa thêm.
- assets/    — logo, hình ảnh, icon có sẵn. Chỉ dùng ảnh trong này.

Yêu cầu kỹ thuật:
- HTML + CSS + JavaScript thuần, không dùng framework, không cần cài đặt gì.
- Một file index.html, một file styles.css, một file script.js.
- Responsive: chạy đẹp trên điện thoại (360px) lẫn máy tính.
- Có hỗ trợ dark mode theo prefers-color-scheme.
- Tiếng Việt, font phải hiện đúng dấu.
- Không dùng thư viện ngoài, trừ Google Fonts.

Các phần cần có, theo thứ tự:
1. Hero: logo, tên CLB, một câu slogan, nút "Đăng ký tham gia"
2. Giới thiệu: CLB là ai, làm gì
3. Các ban trong CLB
4. Hoạt động và sự kiện nổi bật
5. Lý do nên tham gia
6. Liên hệ và mạng xã hội

Bắt đầu bằng việc đọc file rồi mô tả bố cục bạn định làm, sau đó mới viết code.
```

## Prompt chỉnh sửa về sau

```
Phần hero đang nhạt quá. Làm lại cho nổi hơn nhưng vẫn giữ đúng màu trong BRAND.md,
đừng thêm màu mới.
```

```
Kiểm tra trang trên màn hình rộng 360px xem có bị tràn ngang không, có thì sửa.
```

```
Thêm hiệu ứng xuất hiện dần khi cuộn tới từng phần, dùng IntersectionObserver,
đừng dùng thư viện ngoài.
```

## Mẹo dùng AI cho hiệu quả

- **Đừng đòi làm hết trong một lần.** Làm từng phần một, xong phần nào xem phần đó.
- **Mở trang ra xem sau mỗi lần sửa.** AI hay nói "đã xong" trong khi trang vỡ bố cục.
- **Ảnh phải lấy từ `assets/`.** AI rất hay bịa ra đường dẫn ảnh không tồn tại — thấy ô ảnh trống là do vậy.
- **Hỏi lại khi không hiểu code.** Ban giám khảo sẽ hỏi bạn trang này chạy thế nào.
