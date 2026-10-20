# Studio C — chỉ đạo chart và qualitative panels

[Studio](README.md) · [M08](../modules/08-chart-design/README.md) · [M09](../modules/09-evidence-judgment/README.md)

## Mục tiêu

Làm evidence dễ đọc và có chất lượng thị giác, không dùng style để che mức biến thiên hoặc khác biệt điều kiện. AI lo plot/data processing; bạn chốt câu hỏi và diễn giải.

## Đầu vào

Dữ liệu thật được phép dùng, hoặc dữ liệu luyện tập có nhãn synthetic. Với qualitative, cần ảnh và sample ID thật hoặc minh họa ghi rõ; thiếu dữ liệu thì bỏ bài qualitative, không tự dựng kết quả.

## Ba quyết định thiết kế

**Encoding:** viết một câu hỏi lookup/ranking và một câu hỏi trend/trade-off/distribution. Yêu cầu AI đề xuất chart/table cho từng câu, giải thích marks/channels. Bạn chọn trước khi xem styling đẹp.

**Visual hierarchy:** quyết định đâu là đường chính, comparator, annotation và thông tin phụ. Giữ baseline cần đối chiếu đủ đọc. Chọn direct labels hay legend theo mật độ, không mặc định một loại tốt hơn.

**Multi-panel:** chọn chung/thay scale có công bố, căn category, thống nhất ký hiệu và điều kiện. Caption giải mã uncertainty và phạm vi, không tự kết luận significance hoặc causality.

## Các lượt AI thực hiện

Lượt đầu tạo hai encoding từ cùng input. Lượt sau giữ encoding được chọn, thử hai cách hierarchy/type/color. Cuối cùng đặt chart vào trang paper và cung cấp bảng source-to-mark theo yêu cầu.

Bạn nộp ít nhất một quyết định không dựa vào thẩm mỹ: từ chối trộn config, yêu cầu interval definition, hoặc giữ một bảng vì người đọc cần số chính xác. Sau đó làm cho lựa chọn đúng đó cũng đẹp bằng typography, spacing, alignment và mức nhấn.

## Đầu ra và nghiệm thu

Chart brief, A/B selection, data/condition checklist do AI chuẩn bị và bạn duyệt, caption, bản cuối. Bạn đọc được một giá trị, một so sánh và một giới hạn của kết luận. Qualitative panel phải giữ sample/crop/transform tương ứng hoặc công bố sự khác nhau.

Không đánh giá bằng số màu, số panel, lượng dữ liệu nhồi vào hoặc việc AI báo đã chạy code. Không dùng nghiên cứu thật làm nơi cài lỗi có chủ ý; bài phát hiện lỗi phải tách riêng và ghi rõ luyện tập.
