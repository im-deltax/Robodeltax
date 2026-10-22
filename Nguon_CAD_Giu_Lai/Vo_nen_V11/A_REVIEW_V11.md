# Kiểm tra phạm vi V11

| ID | Kết quả | Bằng chứng |
|---|---|---|
|V11-PROP|Bụng/áo cao42% và ngang18% hơn V10; đầu không co giãn; tổng cao129,95mm|A_PROPORTION_CHECK.json; renders/whole.png|
|V11-SCOPE|V10 giữ nguyên; toàn bộ lõi chức năng và HW_ dịch chung15,12mm|source_V10_sha256; operations; hardware_unscaled|
|V11-STATIC|308 cặp giữa vỏ chính và khối linh kiện tham chiếu, không thấy giao thể tích|A_STATIC_BODY_CHECK.json|
|V11-NATIVE|73 chi tiết native hợp lệ; STL kín kế thừa hoặc kiểm tra mới với vòng đỡ|A_ASSEMBLY_CHECK.json:parts|
|V11-VIEW|Ảnh dùng mesh nằm trong V11; sửa liên kết mesh lớp màu logo bị trỏ nhầm sang khối LCD cũ|SCENE_MANIFEST.json; renders/*.json|
|V11-PENDING|Chưa thử in/lắp, đường quét áo/cáp, liên kết vòng đỡ, linh kiện thực hoặc bench|README_V11.md|

Các ID này mô tả bản sửa tỷ lệ cơ khí, không thay tiêu chí điện/DRC/mô phỏng của kế hoạch PCB.
