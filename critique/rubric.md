# Rubric — duyệt thiết kế, không dự đoán điểm hội nghị

[Critique](README.md) · [Phiếu duyệt](../templates/acceptance.md)

## A. Chất lượng sản phẩm

Ghi mỗi mục: **đạt / cần sửa / chưa kiểm tra / không áp dụng**, kèm vị trí hoặc bằng chứng. Không cộng thành điểm tổng; đẹp không bù cho sai dữ liệu.

| Tiêu chí | Cần quan sát | Ví dụ chưa đạt |
|---|---|---|
| Mục đích và hierarchy | Người đọc nhận ra câu hỏi và vùng quan trọng | Title lớn thắng cơ chế; mọi cụm có cùng mức nhấn |
| Composition | Các nhóm, đường đọc và khoảng trống có lý do | Panel tách rời; connector dài chỉ vì chia đều canvas |
| Component craft | Tỷ lệ chữ–khối, silhouette, góc, padding và nội bộ phù hợp vai trò | Tất cả dữ liệu/operator/actor thành thẻ giống nhau |
| Typography | Nhãn, toán học, weight, spacing và xuống dòng có phân cấp | Chữ chỉ đọc được khi phóng lớn; đổi subscript thành exponent |
| Color và line | Vai trò rõ, tương phản theo cấp, đầu nối không mơ hồ | Cùng màu khác nghĩa; viền nhóm nặng hơn dữ liệu chính |
| Chart/evidence | Encoding, nguồn, cấu hình, đơn vị, uncertainty và sample giải thích được | Điểm ghép hai config; crop khác; heatmap không nguồn |
| Scientific fidelity | Đối tượng, nhánh, điều kiện và claim khớp nguồn | Bỏ loss hoặc residual để làm hình thoáng hơn |
| Paper integration | Caption/prose bổ sung nhau; bản đặt trong paper đọc được | Hình đẹp khi mở riêng nhưng bị thu nhỏ/crop trong bài |
| Deliverability | Có đúng bản được duyệt và source sửa được theo yêu cầu | PNG khác source; renderer chưa chạy nhưng báo pass |

Với request về style, dành thời gian thực hành chủ yếu cho năm mục đầu; kiểm tra khoa học vẫn là điều kiện phát hành, không biến toàn khóa thành QA kỹ thuật.

## B. Năng lực của người chỉ đạo

Dùng bốn mức sau cho từng năng lực, không lấy trung bình:

- **Nhận ra:** chỉ được vùng gây vấn đề nhưng lý do còn mơ hồ.
- **Giải thích:** liên hệ observation với nhiệm vụ người đọc và nêu counterexample.
- **Chỉ đạo:** viết yêu cầu AI hiểu được, giữ bất biến và có phép nghiệm thu.
- **Chuyển giao:** áp dụng được lên cơ chế khác, agent khác hoặc phương án chưa thấy trước.

Theo dõi các năng lực: nhìn hierarchy; chọn bố cục; kiểm soát component/type/color/line; chọn chart; đọc evidence; viết brief; critique; chọn và bảo vệ bản cuối.

**Dấu hiệu tiến bộ:** bạn không chỉ chọn bản mình thích, mà chỉ ra được một bản đẹp hơn ở đâu, đánh đổi điều gì, và một điểm mình chưa đủ căn cứ duyệt. Kết quả không cần trùng với AI.

## C. Bài kiểm tra giữ lại

Cuối tuần 6/12/24, dùng một brief chưa luyện, ưu tiên họ cơ chế khác. Giữ nguồn, scope, kích thước, số lượt sửa và ngân sách AI tương đương khi so tiến bộ. Lưu nhận xét ban đầu trước khi xem lời giải.

Nhờ người hiểu lĩnh vực nhưng chưa biết hình đọc thử; hỏi không dẫn dắt và ghi nguyên câu trả lời. Ghi rõ human / fresh-context agent / self-review. Không gọi tự review là blinded test.

Nếu đo thời gian, ghi điều kiện và cách đo; không đặt ngưỡng 10 giây làm chuẩn khoa học chung. Số lần chỉnh ít hơn có thể do agent mạnh hơn, không nhất thiết do người học thiết kế tốt hơn.

## D. Sản phẩm cuối và sự trung thực

Mỗi sản phẩm có ba quyết định riêng: **content approved? appearance approved? integrated-output approved?** Trạng thái unknown không được tính như pass. Các mốc trong roadmap là mốc luyện tập tự đề xuất, không chứng chỉ designer hoặc prediction về presentation 4/4.
