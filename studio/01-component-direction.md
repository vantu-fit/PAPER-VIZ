# Studio A — làm chủ style của component

[Studio](README.md) · [M03](../modules/03-component-craft/README.md) · [Style direction](../templates/style-direction.md)

## Bài toán

Một diagram AI dựng có thể đúng topology nhưng quá giống các thẻ giao diện. Nhiệm vụ của bạn là chỉ đạo thay đổi ngôn ngữ component, không chỉ tô lại màu hoặc làm viền dày hơn.

## Đầu vào

Chọn một cơ chế bạn hiểu, có ít nhất hai loại đối tượng và một quan hệ quan trọng: ví dụ dữ liệu đi qua operator rồi kết hợp với trạng thái. Đưa nguồn hoặc ghi rõ hypothetical. Chọn một reference chính có quyền truy cập và một negative example.

## Ba lượt của người chỉ đạo

**Lượt 1 — phân tích.** Chưa xem lời bình AI. Ghi tỷ lệ chữ–khối, độ nặng các loại nét, cách đặt nhãn, màu nền/đối tượng/nhấn và khoảng cách trong/ngoài cụm. Nêu một điểm cần học và một điểm không hợp cơ chế của bạn.

**Lượt 2 — thử riêng.** Giao AI hai hoặc ba phép thử, mỗi phép chỉ thay một nhóm yếu tố: silhouette/tỷ lệ; typography; line/color. Không cố làm baseline xấu. Với mỗi bản, viết observation và trade-off. Không phải thích màu mạnh hơn là đạt.

**Lượt 3 — tổng hợp.** Bạn chọn một direction, AI dựng cả diagram theo direction đó. So toàn hình với cụm ban đầu. Nếu component đẹp riêng nhưng cả hình thành tường card, sửa cách nhóm/nhịp thay vì thêm shadow.

## Đầu ra

Reference card, style direction một trang, lựa chọn trước AI critique, các preview do AI dựng, hai tickets và bản cuối. Có thể giữ bản trước nếu tổng hợp làm hình tệ hơn.

## Tự kiểm tra

Bạn chỉ được vị trí nào tạo cảm giác “nhựa”, giải thích nguyên nhân, nêu thay đổi mong muốn và kiểm tra đúng thay đổi đó chưa? Bạn có biết trường hợp viền mảnh, không viền hoặc chữ trắng trên màu đậm lại phù hợp hơn không?

Không yêu cầu tự đo từng pixel hoặc vẽ từng shape. Thông số do AI đề xuất phải được xem qua bản xuất ở kích thước đọc. Một bộ mã màu không thay cho hệ thiết kế.
