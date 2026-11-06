# Trà sữa Tẹt Phượng (v30)

Game chạy thẳng trên trình duyệt, tối ưu cho Samsung (Android) và iPhone (kể cả 13 Pro Max).
Tất cả file nằm cùng một cấp, không cần thư mục.

## Danh sách file (tải lên cùng một chỗ, ở gốc repo)
- `index.html` : game
- `manifest.webmanifest` : để cài ra màn hình chính
- `sw.js` : chơi offline
- `icon-180.png`, `icon-192.png`, `icon-512.png`, `icon-512-maskable.png` : biểu tượng

## Đưa lên GitHub Pages
1. Tạo repo mới (Public) trên github.com.
2. Bấm **Add file → Upload files**, kéo thả toàn bộ file trên (không kéo thư mục), rồi **Commit changes**.
3. Vào **Settings → Pages → Build and deployment**: Source chọn **Deploy from a branch**, Branch chọn **main** và thư mục **/(root)**, bấm **Save**.
4. Đợi 1–2 phút, mở link `https://<tên-github>.github.io/<tên-repo>/` trên điện thoại.

## Cài ra màn hình chính
- **Samsung / Android (Chrome hoặc Samsung Internet):** bấm menu ⋮ → **Thêm vào màn hình chính** / **Cài đặt ứng dụng**.
- **iPhone (bắt buộc dùng Safari):** bấm nút **Chia sẻ** → **Thêm vào MH chính**.

## Lưu ý
- Tiến trình lưu trong trình duyệt của từng máy. Trên iPhone, Safari có thể xóa dữ liệu của trang web lâu không dùng, nên hãy cài ra màn hình chính và thỉnh thoảng vào tab **Sao lưu** để xuất file.
- Khi cập nhật game: ghi đè `index.html` và đổi `VERSION` trong `sw.js` (ví dụ `ttp-v30-2`) để điện thoại nhận bản mới.
- Chơi dọc màn hình. Nếu xoay ngang, game sẽ nhắc xoay lại.

## Có gì mới ở v30
- Bán theo số LY nhưng tổng kết theo số KHÁCH. Mỗi khách gọi từ 1 đến 3 ly. Giới hạn ly mỗi ngày: 30 ngày đầu tối đa 64 ly (cuối tuần, lễ nhiều hơn ngày thường), từ sau ngày 30 ngày đông tối đa 120 ly.
- Sự cố bất ngờ xảy ra NGAY TRONG GIỜ BÁN, ngẫu nhiên, trung bình khoảng 14 ngày một lần (mất điện, ngập đường, vỡ ống nước, chập điện, rào đường thi công, chủ quán ốm). Khách đang chờ phải về, quán đóng cửa ngay, chỉ tính doanh thu phần đã bán; tiền thuê và lương vẫn tính, có sự cố tốn thêm tiền sửa chữa.
- Máy ép ly tự động hoạt động thật: tự dừng rót ở vạch ĐẠT, ly đúng đơn thì thanh xanh chạy 0,7 giây rồi tự ép và giao ly; có nút Tắt/Bật tự động trên máy.

## Từ v29 trở về trước
- Thuế tuần phát đầu ngày 8, 15, 22,... có 5 ngày để nộp, biển báo ở tab Cửa hàng và Nhập hàng, công tắc Tự động nộp thuế.
- Vốn khởi điểm 520.000đ; tiền thuê ưu đãi 7 ngày đầu 40.000đ, 7 ngày kế 55.000đ, sau đó 70.000đ.
- Chống phá sản sớm: trong 10 ngày đầu, cuối ngày còn dưới 60.000đ thì gia đình cho mượn không lãi (tối đa 2 lần).
