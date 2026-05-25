# G-Star Design System (GStar Design System)

Chào mừng bạn đến với tài liệu hệ thống thiết kế **G-Star Design System**. Đây là nơi lưu trữ tập trung toàn bộ tài nguyên thương hiệu, tài liệu hướng dẫn, các biến thể logo, font chữ, hình minh họa và các ấn phẩm quảng cáo truyền thông chính thức của **G-Star**.

Hệ thống thư mục được cấu trúc rõ ràng để giúp đội ngũ thiết kế (Designers) và phát triển (Developers) dễ dàng đồng bộ và sử dụng.

---

## 📁 Cấu trúc Thư mục Tài nguyên (Folder Directory)

```text
GStar Design System/
├── 📘 Brand guideline/     # Tài liệu & hình ảnh quy chuẩn thương hiệu, giao diện LDP
├── ✍️ Typography/          # Các bộ font chữ chính thức được sử dụng
├── 🏷️ Logo/                # Biểu tượng (Symbol) chính thức của thương hiệu dưới dạng SVG
├── 🎨 Illustration/        # Hình ảnh minh họa vector (SVG) dùng trên website/app
└── 📢 Sample/              # Các ấn phẩm quảng cáo, banner Ads, popup mẫu
```

---

## ✍️ 1. Typography (Phông chữ)
Hệ thống sử dụng hai họ font chữ chính là **Manrope** (hiện đại, bo góc mềm mại, độ đọc tốt cao trên màn hình kỹ thuật số) và **Saira Semi Condensed** (mạnh mẽ, gọn gàng, phù hợp cho tiêu đề hiển thị).

| Tên Tập Tin | Họ Font (Font Family) | Định dạng | Vai trò trong Thiết kế |
| :--- | :--- | :--- | :--- |
| `Manrope-Bold.ttf` | Manrope | TrueType | Dùng cho tiêu đề phụ (Subheadings), các đoạn văn bản nhấn mạnh. |
| `Manrope-ExtraBold.ttf` | Manrope | TrueType | Dùng cho các con số nổi bật, tiêu đề chính cần nhấn mạnh cao. |
| `SairaSemiCondensed-Bold.ttf` | Saira Semi Condensed | TrueType | Dùng cho tiêu đề hiển thị chính (Main Headers), nút bấm (Buttons) hoặc thẻ (Cards). |

---

## 🏷️ 2. Logo (Biểu trưng)
Bộ nhận diện thương hiệu G-Star sử dụng các biểu tượng dạng Vector (`.svg`) sắc nét, dễ dàng co giãn mà không bể hình, tối ưu hóa cho hiển thị trên website, ứng dụng di động:

*   **`Symbol.svg`**: Phiên bản biểu tượng gốc chuẩn.
*   **`Symbol 2.svg`**: Biến thể biểu tượng thay thế phiên bản 2.
*   **`Symbol 3.svg`**: Biến thể biểu tượng thay thế phiên bản 3.

---

## 📘 3. Brand Guideline (Quy chuẩn thương hiệu)
Thư mục này chứa các thiết kế giao diện giới thiệu G-Stars ở nhiều thiết bị và các thành phần cấu trúc giao diện dạng SVG:

### 📱 Giao diện giới thiệu G-Stars (Layout Preview):
*   `Giới thiệu G-Stars desktop.jpg` - Layout xem trước trên máy tính bàn chuẩn.
*   `Giới thiệu G-Stars pc.jpg` - Layout tối ưu hóa cho màn hình máy tính lớn.
*   `Giới thiệu G-Stars ldp.jpg` - Thiết kế tổng thể trang Landing Page đầy đủ.
*   `Giới thiệu G-Stars mobile.jpg` - Thiết kế tối ưu hóa hiển thị trên thiết bị di động.

### 🧩 Thành phần Vector thương hiệu:
*   Từ `1.svg` đến `9.svg` (bao gồm cả `8-1.svg` và `2.jpg`): Chứa các thành phần thiết kế riêng lẻ, các icon quy chuẩn và tài nguyên đồ họa cấu thành nên bộ quy chuẩn thương hiệu G-Stars.

---

## 🎨 4. Illustration (Hình minh họa)
Bộ hình ảnh minh họa vector sắc nét định dạng SVG được sử dụng làm hình nền hoặc mô tả tính năng dịch vụ trên nền tảng số:
*   `10.svg`
*   `201.svg`
*   `202.svg`

---

## 📢 5. Sample (Ấn phẩm Mẫu & Banner Ads)
Tổng hợp các ấn phẩm quảng cáo, truyền thông thực tế của G-Star trên nhiều nền tảng và kích thước khác nhau:

### 🖼️ Mẫu Popup Chiến dịch:
*   `Popup Bí kíp thành công 1.png`
*   `Popup Bí kíp thành công 2.png`

### ⚡ Banner Quảng cáo (Ads Banner):
*   **Ads tiêu chuẩn:** `Ads 1.jpg`, `Ads 2.jpg`, `Ads 3.jpg`, `Ads 5.jpg`, `Ads 6.jpg`, `Ads 7.jpg`, `Ads 8.jpg`, `Ads 10.jpg`, `Ads 11.jpg`.
*   **Kích thước đặc biệt:** `Ads 9 640x360.jpg` (Tỉ lệ 16:9), `Ads 9 1x1.jpg` (Hình vuông cho mạng xã hội).
*   **Thiết kế thích ứng:** `Ads 1 Adapt.jpg`, `Ads 7 Adapt.jpg` (Phiên bản căn chỉnh tương thích đa nền tảng).
*   **Hình ảnh bổ trợ chiến dịch:** Các tệp từ `2.jpg` đến `14.jpg` hỗ trợ minh họa cho các bài đăng quảng cáo.

---

## 🛠️ Hướng dẫn Sử dụng cho Dự án
1.  **Dành cho Frontend Developers:**
    *   Hãy nhúng các tệp font từ thư mục `Typography` vào CSS thông qua `@font-face`.
    *   Sử dụng trực tiếp các tệp `.svg` trong thư mục `Logo` và `Illustration` cho các thẻ `<img>` hoặc inline SVG trên web để đảm bảo hiển thị sắc nét nhất trên màn hình Retina.
2.  **Dành cho Designers:**
    *   Vui lòng tham khảo kỹ bố cục trong thư mục `Brand guideline` trước khi triển khai các ấn phẩm thiết kế mới để đảm bảo tính nhất quán của thương hiệu G-Star.
