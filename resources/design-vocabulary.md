# Từ vựng thiết kế để nhận xét cụ thể

[Materials](README.md) · [Chẩn đoán](../critique/diagnostic-atlas.md)

Các diễn giải ngắn dưới đây dành cho luyện nói và viết direction, không thay giáo trình đầy đủ. Đọc R01–R09 trong materials để đi sâu.

| Thuật ngữ | Cần nhìn điều gì? | Câu có thể dùng khi chỉ đạo AI |
|---|---|---|
| Hierarchy / phân cấp | Thứ tự chú ý giữa các vùng | “Làm rõ cơ chế trung tâm; giảm cạnh tranh của tiêu đề phụ.” |
| Visual weight / trọng lượng thị giác | Kích thước, độ đậm, contrast, mật độ | “Khung nhóm đang nặng như operator; thử giảm nét khung.” |
| Proportion / tỷ lệ | Tương quan giữa chữ và khối, lớn và nhỏ | “Giữ cỡ nhãn; giảm padding để layer giống thanh xử lý, không giống card.” |
| Silhouette / hình dáng tổng thể | Nhìn hình bao trước nội dung chi tiết | “Hai mạng nhiều scale cần đọc được như hai hệ liên quan, không ba hộp rời.” |
| Grouping / nhóm | Gần nhau, giống nhau, nối nhau, chung vùng | “Siết các đối tượng trong cùng cơ chế; tách hơn khỏi nhánh điều kiện.” |
| Figure–ground | Đối tượng và nền có phân biệt? | “Nền chỉ giúp nhóm, không được thắng các marks bên trong.” |
| Alignment | Các trục, baseline, điểm tương ứng | “Căn hai input theo cùng hàng; kiểm tra optical balance sau khi dựng.” |
| Rhythm | Lặp và biến thiên có chủ đích | “Giữ nhịp các stage nhưng cho cơ chế cần chi tiết nhiều diện tích hơn.” |
| Negative space | Khoảng trống phục vụ nhóm hoặc đường nối | “Giữ corridor phản hồi; đừng lấp nó bằng một legend thừa.” |
| Type hierarchy | Vai trò qua cỡ/weight/placement | “Tên layer không bold bằng panel label; toán trung tâm vẫn rõ.” |
| Optical balance | Cảm giác cân, không chỉ tọa độ đều | “Kiểm tra nhãn có vẻ lệch trong khối dù đã căn giữa hình học.” |
| Leading / tracking / kerning | Khoảng dòng, khoảng chữ tổng thể, cặp chữ | “Nhãn hai dòng quá sát; tăng khoảng dòng mà không đổi thuật ngữ.” |
| Contour hierarchy | Viền, nội bộ, connector có cấp nét | “Tensor outline rõ, nét chia ô nhẹ; không tăng đậm tất cả.” |
| Semantic color | Màu có một vai trò rõ | “Giữ màu cho data role, không dùng lại nó làm scale giá trị không liên quan.” |
| Contrast range | Nền nhẹ, đối tượng, điểm nhấn phân bố thế nào | “Chỉ tăng contrast vùng cần chú ý, không tăng saturation toàn hình.” |
| Visual encoding | Marks/channels đại diện dữ liệu | “Không dùng diện tích để biểu diễn thứ hạng nếu người đọc cần so số chính xác.” |
| Small multiples | Nhiều view tương ứng | “Giữ scale/category tương ứng hoặc giải thích khác biệt trong caption.” |
| Focus + context | Vùng cơ chế được mở rộng nhưng không mất vị trí | “Inset khớp input/output với block gốc; đường tham chiếu không là data edge.” |

Đừng dùng từ chuyên môn để thay quan sát. “Hierarchy chưa tốt” vẫn mơ hồ; phải chỉ được vùng, tác động và mục tiêu sửa.
