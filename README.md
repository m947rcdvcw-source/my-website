# A.T.C Supply 1993 — Design System & Improved Homepage

**Version:** 1.0  
**Ngày:** 22/10/2026  
**Tối ưu cho:** Webflow / Framer / HTML tĩnh

---

## Danh sách file

| File | Mô tả |
|------|------|
| `index-improved.html` | Trang chủ đã cải thiện (Navigation mới + Hero + Category + ProductCard) |
| `atc-tokens.css` | Design Tokens (màu, spacing, radius, shadow, type…) |
| `atc-tokens.json` | Tokens dạng JSON (dùng import tool) |
| `ATC-Design-System-Tokens.md` | Tài liệu đầy đủ về Design System |
| `hero.css` | CSS hoàn chỉnh cho Hero section (responsive) |
| `category-card.css` | CSS cho Category Card mới |
| `product-card-demo.html` | Demo riêng ProductCard |
| `preview.html` | Xem trực quan toàn bộ Design Tokens |

---

## Cách sử dụng nhanh

### 1. Xem Design Tokens
Mở file `preview.html` bằng trình duyệt.

### 2. Xem trang chủ cải thiện
Mở file `index-improved.html`.

> **Lưu ý đường dẫn:**  
> File đang trỏ CSS gốc về `../Atcwebsite/assets/...`.  
> Nếu bạn đặt thư mục khác, hãy sửa lại đường dẫn trong thẻ `<link>` và `<script>`.

### 3. Áp dụng vào project hiện tại
1. Copy `atc-tokens.css`, `hero.css`, `category-card.css` vào thư mục CSS của bạn.
2. Thay dần các class cũ bằng class mới (`product-card-new`, `category-card-new`…).
3. Dùng `index-improved.html` làm tham chiếu cấu trúc.

---

## Những gì đã cải thiện

### Navigation
- Gộp **Kiến thức + Dự án** → **Tài nguyên** (dropdown)
- Bỏ “Liên hệ” khỏi menu desktop (chỉ còn mobile + footer)
- Menu gọn hơn, dễ nhìn hơn

### Hero
- Overlay tối rõ ràng hơn
- Side-note chỉ hiện từ tablet trở lên
- Button dùng đúng spec (Primary + Outline)
- Responsive đầy đủ

### Danh mục sản phẩm
- Category Card mới sạch sẽ
- Sẵn sàng thay icon bằng ảnh thật
- Hover đẹp, grid responsive (5 → 3 → 2 → 1)

### Sản phẩm tiêu biểu
- ProductCard mới (có badge, CTA rõ, hover mượt)
- Dễ thay ảnh thật sau này

### Design System
- Tokens đầy đủ: Color, Type, Spacing, Radius, Shadow, Motion
- Sẵn sàng import Webflow Variables / Framer Variables

---

## Thứ tự ưu tiên tiếp theo (gợi ý)

1. Thay ảnh Unsplash bằng ảnh local
2. Thay icon Category bằng ảnh thật sản phẩm
3. Chuẩn hóa toàn bộ Button theo spec
4. Làm tiếp các trang: Sản phẩm, Chi tiết sản phẩm, Báo giá
5. Chuyển sang Webflow hoặc Framer

---

## Liên hệ & hỗ trợ
File này được tạo để hỗ trợ redesign website A.T.C Supply 1993.
