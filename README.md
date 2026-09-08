# Tra cứu Thủ tục & Chứng từ CTKM

Công cụ nội bộ tra cứu thủ tục pháp lý và danh mục chứng từ cần chuẩn bị cho các chương trình khuyến mại (CTKM), dựa trên nhóm hàng hóa/dịch vụ áp dụng và hình thức CTKM đã chọn. Kèm hướng dẫn xuất hóa đơn theo từng hình thức.

Toàn bộ tool nằm gọn trong 1 file `index.html` — không cần server, không cần build, không phụ thuộc thư viện ngoài (trừ font chữ, sẽ tự chuyển sang font hệ thống nếu máy không có mạng).

## Chạy thử trên máy

Mở trực tiếp file `index.html` bằng trình duyệt bất kỳ (Chrome, Edge, Safari...).

## Xuất bản qua GitHub Pages

1. Vào **Settings → Pages** của repo này.
2. Ở mục "Build and deployment", chọn **Deploy from a branch**.
3. Chọn branch `main`, thư mục `/ (root)`, bấm **Save**.
4. Sau 1–2 phút, link sẽ có dạng `https://<tên-tài-khoản>.github.io/<tên-repo>/`.

> **Lưu ý:** GitHub Pages ở chế độ mặc định là **công khai** — ai có link đều xem được, kể cả khi repo ở chế độ Private (Pages chỉ private nếu có gói GitHub Enterprise Cloud). Nếu cần giới hạn người xem, cân nhắc đặt thêm lớp xác thực riêng (ví dụ Cloudflare Access) phía trước link, hoặc chỉ chia sẻ link nội bộ và không đăng công khai.

## Cập nhật nội dung

Khi cần chỉnh sửa thủ tục/chứng từ/hóa đơn, thay file `index.html` bằng bản mới rồi commit — GitHub Pages sẽ tự cập nhật theo, không cần thao tác gì thêm.

---
Công cụ được thiết lập dựa trên nền tảng kiến thức và kinh nghiệm của tác giả - Lyn, cũng như pháp luật hiện hành tại thời điểm thiết lập công cụ. Vui lòng đối chiếu và cân nhắc với tình huống thực tế khi sử dụng.
