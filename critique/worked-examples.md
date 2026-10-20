# Bốn bài critique có lời bình

[Critique](README.md)

**Tất cả tình huống dưới đây là bài tập giả định bằng lời, không phải review của một hình chưa được xem hoặc thí nghiệm đã chạy.** Giao AI dựng khi luyện; lời bình là một phương án hợp lý để so, không đáp án thẩm mỹ duy nhất.

## 1. Hai luồng, bốn khung giống hệt nhau

**Brief:** so sánh nhánh xử lý hình ảnh với nhánh xử lý trạng thái, sau đó kết hợp. **Output giả định:** mọi khối đều bo tròn xanh nhạt; các input nhỏ; fusion không có trọng tâm.

**Nhận xét yếu:** “Hãy làm giống paper top và chuyên nghiệp hơn.”

**Direction:** “Ở hai đầu vào, phân biệt image artifact với state vector bằng hình thức, không thêm icon trang trí. Giữ hai nhánh căn tại các giao diện tương ứng. Dành contrast chính cho fusion; khung nhóm nhẹ hơn operator. Không thay số đường vào fusion.”

**Nghiệm thu:** xem bản nhỏ để xác định hai nhánh và fusion; xem cận để kiểm tra labels/ports; đọc nguồn để kiểm tra topology. Nếu chỉ đổi màu mà mọi object vẫn là một card, mục tiêu chưa đạt.

**Đánh đổi:** mở rộng fusion có thể làm context quá nhỏ. Hỏi người đọc xem còn xác định được mỗi nhánh nhận gì không.

## 2. Typography nhìn to, nhưng không sang

**Output giả định:** title ấn tượng, module labels đều bold, công thức nhỏ bị chật trong khối, nhãn edge nhạt.

**Direction:** “Giảm sự cạnh tranh của title và module label; giữ tên có hierarchy nhưng không bold tất cả. Cho công thức đủ chỗ thay vì tiếp tục giảm cỡ; reflow khối nếu cần. Đưa nhãn edge gần đúng đoạn nó giải thích và tăng độ rõ tại kích thước đặt trong paper.”

**Không được đổi:** ký hiệu toán, thứ tự phép nhân, nội dung edge. **Nghiệm thu:** kiểm tra năm nhãn nhỏ nhất, một công thức và một line label; đối chiếu ảnh toàn hình, không duyệt bằng crop riêng.

**Counterexample:** việc mọi nhãn dùng cùng font có thể đúng; vấn đề ở role/weight/spacing chứ không nhất thiết thiếu họ font thứ hai.

## 3. Accuracy–cost hấp dẫn nhưng mất ý nghĩa

**Output giả định:** marker đẹp, gradient đẹp, đường nối các model độc lập; một điểm lấy cost ở batch khác với quality protocol.

**Direction:** “Tách vấn đề dữ liệu khỏi style. Trước hết đối chiếu cấu hình của từng tọa độ; không có cặp hợp lệ thì để missing, không ước lượng. Bỏ đường liên tục khi không có ý nghĩa nội suy. Giữ context trục, làm baseline đủ đọc; thử direct labels chỉ cho những series cần đọc nhanh.”

**Nghiệm thu:** bảng point–source/config; trả lời một câu hỏi trade-off; caption nói rõ đại lượng và scope. Không duyệt bằng thẩm mỹ nếu dữ liệu chưa được giải quyết.

## 4. Recipe ba stage trông như slide bán hàng

**Output giả định:** ba card lớn, mỗi card ba dòng khẩu hiệu và icon robot. Chuyển checkpoint, dữ liệu và feedback dùng cùng một loại arrow.

**Direction:** “Giữ ba stage nhưng bỏ card phình to. Đưa dữ liệu, model và checkpoint thành đối tượng riêng, thể hiện thứ chuyển giữa stage. Dùng typography và khoảng nhóm để giữ bố cục, không thêm outline lồng nhau. Tách đường checkpoint khỏi dữ liệu; chỉ vẽ feedback nếu protocol cho phép.”

**Nghiệm thu:** người đọc nói được stage 2 nhận weights hay training examples từ stage 1. Sau đó mới hỏi thích style nào. Nếu bài thực tế chỉ có hai stage, không được chép cấu trúc ba stage từ bài luyện này.
