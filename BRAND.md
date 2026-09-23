# Bộ nhận diện thương hiệu

> Ban tổ chức điền các giá trị thật vào chỗ `<...>` trước khi phát kit cho người thi.

## Màu

| Vai trò | Mã màu | Dùng ở đâu |
|---|---|---|
| Chính | `<#000000>` | Nút bấm, tiêu đề lớn, điểm nhấn |
| Phụ | `<#000000>` | Nền phụ, viền, thẻ |
| Nhấn | `<#000000>` | Link, trạng thái hover |
| Nền sáng | `#FFFFFF` | Nền mặc định |
| Chữ | `<#111111>` | Chữ nội dung |

Màu của Google (dùng khi nhắc tới GDG on Campus):

| Màu | Mã |
|---|---|
| Blue | `#4285F4` |
| Red | `#EA4335` |
| Yellow | `#FBBC04` |
| Green | `#34A853` |

Dán vào CSS:

```css
:root {
  --brand-primary: <#000000>;
  --brand-secondary: <#000000>;
  --brand-accent: <#000000>;
  --text: <#111111>;
  --bg: #ffffff;

  --google-blue: #4285f4;
  --google-red: #ea4335;
  --google-yellow: #fbbc04;
  --google-green: #34a853;
}
```

## Font

| Vai trò | Font | Ghi chú |
|---|---|---|
| Tiêu đề | `<Google Sans / Poppins>` | |
| Nội dung | `<Roboto / Inter>` | Hỗ trợ tiếng Việt đầy đủ |

Nhớ kiểm tra font hiển thị đúng dấu tiếng Việt (ê, ệ, ữ, ỳ).

## Logo

Nằm trong `assets/logo/`. Ưu tiên dùng bản `.svg` vì phóng to không vỡ.

**Được:**
- Giữ nguyên tỉ lệ khi phóng to thu nhỏ
- Chừa khoảng trống quanh logo ít nhất bằng chiều cao chữ trong logo
- Dùng bản logo trắng khi đặt trên nền tối

**Không được:**
- Đổi màu logo
- Kéo giãn làm méo
- Thêm viền, đổ bóng, hiệu ứng
- Đặt logo lên ảnh rối làm không đọc được

## Giọng văn

Thân thiện, gần gũi với sinh viên, không quá trang trọng. Xưng "chúng mình" hoặc "CLB", gọi người đọc là "bạn".
