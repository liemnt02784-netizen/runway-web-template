# Bộ nhận diện thương hiệu

## Màu

Logo Runway là một dải gradient xanh, chạy từ xanh tím ở trên xuống xanh da trời ở dưới. Các mã dưới đây lấy trực tiếp từ file logo gốc.

| Vai trò | Mã màu | Dùng ở đâu |
|---|---|---|
| Xanh Runway đậm | `#426EF0` | Tiêu đề, nút chính, điểm nhấn |
| Xanh Runway sáng | `#3FB4FE` | Điểm cuối gradient, hover, highlight |
| Xanh Hoa Sen | `#0C4DA2` | Khi đặt cạnh logo Khoa Công nghệ |
| Đỏ Hoa Sen | `#E8112D` | Chỉ dùng rất ít, làm điểm nhấn |
| Chữ | `#1A1A1A` | Chữ nội dung trên nền sáng |
| Nền sáng | `#FFFFFF` | Nền mặc định |
| Nền tối | `#0F1115` | Dark mode |

Màu Google, dùng khi nhắc tới GDG on Campus:

| Màu | Mã |
|---|---|
| Blue | `#4285F4` |
| Red | `#EA4335` |
| Yellow | `#FBBC04` |
| Green | `#34A853` |

Dán vào CSS:

```css
:root {
  --runway-deep:  #426ef0;
  --runway-light: #3fb4fe;
  --runway-gradient: linear-gradient(160deg, #426ef0 0%, #3fb4fe 100%);

  --hsu-blue: #0c4da2;
  --hsu-red:  #e8112d;

  --google-blue:   #4285f4;
  --google-red:    #ea4335;
  --google-yellow: #fbbc04;
  --google-green:  #34a853;

  --text: #1a1a1a;
  --bg:   #ffffff;
}

@media (prefers-color-scheme: dark) {
  :root { --text: #f2f2f2; --bg: #0f1115; }
}
```

Gradient của logo đi theo hướng chéo từ trên xuống dưới. Khi làm nền hoặc nút bấm, giữ đúng hướng đó cho đồng bộ với logo.

## Font

| Vai trò | Font | Ghi chú |
|---|---|---|
| Tiêu đề | **Poppins** hoặc **Google Sans** | Chữ trong logo là kiểu geometric sans, Poppins gần nhất |
| Nội dung | **Inter** hoặc **Roboto** | Hỗ trợ tiếng Việt đầy đủ |

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@600;700&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
```

Luôn kiểm tra font hiển thị đúng dấu tiếng Việt: **ê ệ ữ ỳ ọ ậ**. Nhiều font đẹp nhưng thiếu dấu, chữ sẽ nhảy sang font khác trông rất lộ.

## Logo có sẵn

Tất cả nằm trong `assets/logo/`.

| File | Dùng khi nào |
|---|---|
| `logo-runway-horizontal.png` | Logo chính, có chữ "Runway Club" và slogan. Dùng ở header, hero |
| `logo-runway-icon.png` | Chỉ hình tam giác chữ R. Dùng làm favicon, avatar, icon nhỏ |
| `logo-runway-white.png` | Bản trắng có chữ, đặt trên nền tối hoặc nền ảnh |
| `logo-runway-icon-white.png` | Icon bản trắng |
| `logo-gdg-oncampus-light.png` | Logo GDG on Campus cho nền sáng |
| `logo-gdg-oncampus-white.png` | Logo GDG on Campus cho nền tối |
| `logo-google-developers.png` | Logomark Google Developers |
| `logo-hsu-congnghe-blue-vi.png` | Khoa Công nghệ HSU, tiếng Việt, nền sáng |
| `logo-hsu-congnghe-white-vi.png` | Khoa Công nghệ HSU, tiếng Việt, nền tối |
| `logo-hsu-fit-blue-en.png` | Faculty of Information Technology, tiếng Anh |

## Quy tắc dùng logo

**Được:**
- Giữ nguyên tỉ lệ khi phóng to thu nhỏ
- Chừa khoảng trống quanh logo tối thiểu bằng chiều cao chữ "R" trong logo
- Dùng bản trắng khi nền tối hoặc nền ảnh
- Logo icon tối thiểu 32px, logo ngang tối thiểu 120px chiều rộng

**Không được:**
- Đổi màu logo, kể cả đổi gradient sang màu khác
- Kéo giãn làm méo
- Thêm viền, đổ bóng, xoay nghiêng
- Đặt logo màu lên nền xanh cùng tông làm chìm mất
- Ghép logo Runway dính sát logo GDG hay HSU thành một khối

## Giọng văn

Thân thiện, gần gũi với sinh viên, không sáo rỗng. Xưng "chúng mình" hoặc "CLB", gọi người đọc là "bạn". Slogan chính thức: **New Journey – New Challenges**.
