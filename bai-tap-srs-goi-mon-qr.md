# Bài tập SRS – Hệ thống gọi món qua mã QR

## Bước 1 — Phân loại 5 ghi chú thành yêu cầu chức năng/phi chức năng và xác định vị trí IEEE 830

| Ghi chú | Loại yêu cầu (Chức năng/Phi chức năng) | Vị trí IEEE 830 đề xuất |
|---|---|---|
| Ghi chú 1 | Chức năng (Functional) | 3.2 Functional Requirements |
| Ghi chú 2 | *Phi chức năng* | 3.3 Non-Functional Requirements |
| Ghi chú 3 | *Chức năng* | 3.2 Functional Requirements |
| Ghi chú 4 | *Phi chức năng* | 3.1 External Interfaces |
| Ghi chú 5 | Chức năng | *3.3 Non-Functional Requirements* |

## Bước 2 — Xác định vị trí cho 2 sơ đồ đã có sẵn

| Sơ đồ | Vị trí IEEE 830 đề xuất | Lý do |
|---|---|---|
| Use Case Diagram tổng thể | 2.2 Tóm tắt chức năng chính | Sơ đồ Use Case tổng thể thể hiện các chức năng chính của hệ thống và các Actor tương tác với hệ thống, nên nằm ở phần mô tả tổng quan. |
| ERD Đơn hàng - Món ăn | 3.4 Sơ đồ CSDL | ERD mô tả các thực thể, dữ liệu và mối quan hệ giữa chúng, thuộc yêu cầu chi tiết về cơ sở dữ liệu. |

## Bước 3 — Viết lại các ghi chú còn vi phạm đặc tính vàng

| Ghi chú | Đặc tính vàng bị vi phạm | Viết lại đạt chuẩn (có chỉ số/điều kiện cụ thể) |
|---|---|---|
| Ghi chú 2 | *Verifiable* | Hệ thống phải hiển thị đầy đủ thực đơn trong thời gian tối đa 2 giây kể từ khi khách hàng quét mã QR thành công, trong điều kiện kết nối mạng bình thường. |
| Ghi chú 4 | Verifiable | Hệ thống có thể hoạt động trên các trình duyệt như Chrome, Cốc Cốc, Safari trên các thiết bị đang còn được các nhà phát triển hỗ trợ. Đối với các thiết bị quá cũ sẽ không hoạt động tốt khi kết nối với hệ thống. |
