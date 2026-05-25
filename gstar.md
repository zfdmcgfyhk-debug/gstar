# 🎨 Project Design System & Guidelines (`DESIGN.md`)

Mục lục này chứa toàn bộ quy chuẩn thiết kế giao diện (UI) và trải nghiệm (UX) của dự án. Tất cả các thành viên (Developers, Designers) và các AI Agent đều phải tuân thủ nghiêm ngặt hệ thống này.

---

## 1. Bản sắc Thương hiệu (Identity)
* **Tên dự án:** [Tên Dự Án]
* **Phong cách cốt lõi:** Tối giản (Minimalism), Tập trung vào không gian thở (White space), Độ tương phản cao.
* **Cảm xúc hướng tới:** Tinh tế, Chuyên nghiệp, Đáng tin cậy.

---

## 2. Hệ thống Tokens (Design Tokens)

### Bảng màu chuẩn
| Loại màu | Mã HEX | Vị trí áp dụng |
| :--- | :--- | :--- |
| **Nền chính** | `#F8FAFC` | Nền toàn trang (Light mode) |
| **Chữ chính** | `#0F172A` | Tiêu đề, văn bản chính |
| **Điểm nhấn** | `#3B82F6` | Nút kêu gọi hành động (CTA), liên kết |
| **Chữ phụ** | `#64748B` | Đoạn văn mô tả nhỏ, chú thích |

### Kiểu chữ (Typography)
* **Font họ:** `Inter`, `system-ui`, sans-serif.
* **Quy tắc kích thước:**
    * `h1`: `2.25rem` (36px) | Bold 700
    * `h2`: `1.5rem` (24px) | SemiBold 600
    * `body`: `1rem` (16px) | Regular 400

---

## 3. Quy chuẩn Bố cục & Component (Layout)

* **Hệ thống khoảng cách:** Sử dụng bội số của **8px** (`8px`, `16px`, `24px`, `32px`).
* **Bo góc (Border Radius):** Mặc định là `8px` cho nút bấm nhỏ và `12px` cho các khối nội dung (Cards).
* **Đổ bóng (Shadows):** Chỉ dùng bóng mờ, mịn để tạo chiều sâu tự nhiên: `box-shadow: 0 4px 6px -1px rgb(0 0 0 / 0.05);`

---

## 4. Quy tắc Nghiêm ngặt (Do's & Don'ts)

> [!IMPORTANT]
> **NÊN LÀM (DO):**
> * Giữ tỷ lệ tương phản giữa chữ và nền lớn hơn 4.5:1 (Chuẩn WCAG AA).
> * Để lề (Padding) bên trong các Card tối thiểu là `24px`.

> [!WARNING]
> **KHÔNG ĐƯỢC LÀM (DON'T):**
> * Không dùng các dải màu Gradient quá sặc sỡ hoặc bóng đổ cứng (Hard shadows).
> * Không dùng cỡ chữ nhỏ hơn `12px` cho các phần văn bản đọc chính.
