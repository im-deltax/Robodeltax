# Bàn giao thay đổi cơ khí V11 cho B

Dùng Micro_Duck_Pumpkin_V11_A_Assembly.FCStd làm tham chiếu mới, tiếp tục PCB hiện có. Không đổi kích thước linh kiện hoặc thiết kế điện chỉ vì vỏ cao hơn.

V11 giữ nguyên hình học vỏ chức năng gốc, Neck, toàn bộ HW_, LCD/pin/loa và các khoảng dự phòng, dịch tất cả +15,12mm Z. Nếu B đang dùng hệ tọa độ CAD toàn cục, cập nhật chung biến đổi(0,0,+15,12), bao gồm cổng USB/công tắc gắn trên cụm; nếu dùng hệ tọa độ cục bộ PCB thì vị trí tương đối không đổi. Đầu/nón/kính cũng cùng phép tịnh tiến. Bụng/áo/tay được mở rộng XY1,18 và Z1,42 quanh datumZ7, đế chỉ mở rộng XY1,18. Thêm vòng đỡ cụm chức năng ở Z8,6..22,02, OD30/ID16.

Kiểm tra308 giao thể tích giữa vỏ chính mới và khối linh kiện tham chiếu không thấy va chạm. Còn phải kiểm tra đường quét áo sau, khả năng đưa đầu cáp sạc/nạp code qua áo mở, liên kết vòng đỡ và dung sai với module thực. Cổng Type-C cần vừa nạp code vừa cấp nguồn theo yêu cầu đã chốt; V11 không thay mạch điện hoặc xác nhận chức năng đó. Đọc README_V11/A_PROPORTION_CHECK/A_STATIC_BODY_CHECK. Bằng chứng đầu V10 trong evidence có tọa độ gốc, kế thừa qua tịnh tiến chung, không phải lần test mới.
