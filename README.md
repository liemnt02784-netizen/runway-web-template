# Runway × GDG on Campus — Web Contest Starter Kit

Bộ tài nguyên chính thức cho cuộc thi **làm web giới thiệu câu lạc bộ**.

Repo này **không phải một trang web mẫu**. Nó là **kho asset + tài liệu thương hiệu** để bạn tự do dựng trang theo ý mình (tự code, hay vibe code với AI đều được).

---

## 1. Lấy bộ kit về

**Cách 1 — dùng nút Use this template** (khuyên dùng): bấm **Use this template → Create a new repository**. Bạn sẽ có repo riêng, lịch sử git sạch.

**Cách 2 — clone:**

```bash
git clone https://github.com/<to-chuc>/runway-web-template.git my-club-site
cd my-club-site
rm -rf .git && git init
```

## 2. Trong kit có gì

```
assets/
  logo/        Logo Runway và GDG on Campus (SVG + PNG)
  images/      Ảnh hoạt động, ảnh nền, ảnh ban chủ nhiệm
  icons/       Icon nhỏ, favicon
  fonts/       Font được phép dùng
BRAND.md       Màu, font, quy tắc dùng logo — ĐỌC TRƯỚC KHI LÀM
CONTENT.md     Nội dung chữ về CLB: giới thiệu, sự kiện, liên hệ
PROMPT.md      Prompt mẫu để vibe code với AI
index.html     File trống có sẵn link tới asset, để bắt đầu cho nhanh
```

## 3. Bắt đầu làm

Không cần cài gì cả. Mở `index.html` bằng trình duyệt là chạy.

Muốn dùng AI để dựng trang thì mở [PROMPT.md](PROMPT.md), copy prompt trong đó rồi dán vào công cụ bạn dùng (Claude, Gemini, Cursor...). Prompt đã ghi sẵn đường dẫn asset và mã màu nên AI sẽ dùng đúng bộ nhận diện.

## 4. Luật thi

- **Bắt buộc** dùng logo và màu trong `BRAND.md`, không tự đổi màu logo, không kéo méo logo.
- **Bắt buộc** có các phần: giới thiệu CLB, các ban, hoạt động/sự kiện, cách đăng ký, liên hệ.
- Được thêm ảnh ngoài, nhưng phải là ảnh bạn có quyền dùng (tự chụp, hoặc nguồn miễn phí bản quyền).
- Được dùng AI thoải mái. Nhưng khi chấm, bạn phải giải thích được trang của mình chạy thế nào.
- Trang phải chạy được trên điện thoại.

## 5. Nộp bài

1. Deploy trang lên **GitHub Pages**: vào repo của bạn → **Settings → Pages → Source: Deploy from a branch → main → /(root) → Save**. Đợi khoảng 1 phút là có link.
2. Điền link repo và link trang đã deploy vào form: `<dán link form vào đây>`
3. Hạn chót: `<điền hạn chót>`

## 6. Tiêu chí chấm

| Tiêu chí | Điểm |
|---|---|
| Đúng nhận diện thương hiệu (màu, logo, font) | 25 |
| Nội dung đầy đủ, viết rõ ràng | 25 |
| Giao diện đẹp, bố cục hợp lý | 25 |
| Chạy tốt trên điện thoại | 15 |
| Sáng tạo, có điểm riêng | 10 |

---

Có gì không rõ thì hỏi trong nhóm chat của cuộc thi.
