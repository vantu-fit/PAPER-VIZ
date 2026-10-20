# Từ “nhựa / rối / chưa đẹp” đến giả thuyết sửa

[Critique](README.md) · [Ticket](../templates/critique-ticket.md)

Các chẩn đoán dưới đây là giả thuyết thiết kế. Xem hình thực trước khi chọn, không coi một đặc điểm là dấu hiệu chắc chắn ảnh do AI tạo.

| Nhận xét ban đầu | Điều cần kiểm tra | Yêu cầu thử với AI | Bất biến / counterexample |
|---|---|---|---|
| “Nhìn nhựa” | Mọi khối cùng bo góc, cùng pastel, cùng padding, ít khác vai trò? | Dựng một cụm với operator, dữ liệu, phạm vi có silhouette khác nhau; giữ cùng cơ chế | Không thêm texture hoặc nét lệch để giả vẽ tay |
| “Border chưa đẹp” | Viền ngoài, nội bộ, nhóm và connector có cùng độ nặng? | Tạo hai hệ nét, không đổi màu hay bố cục, xem ở kích thước cuối | Đen không đồng nghĩa dày; viền đậm có thể đúng ở sơ đồ ít chi tiết |
| “Font thiếu chuyên nghiệp” | Hệ weight/type scale, line break, optical balance, tỷ lệ chữ–khối? | Chỉ chỉnh typography ở cùng geometry hoặc đề xuất reflow có lý do | Serif không tự học thuật; không đổi notation |
| “Màu nhạt như template” | Có tương phản nền–module–điểm nhấn không? | Thử phân bố tương phản khác, giữ mapping role; không tăng saturation mọi thứ | Nhiều màu mạnh có thể làm mất focal point |
| “Rối” | Có cạnh giao nhau, ba loại quan hệ dùng cùng nét, chi tiết không cần thiết? | Tách loại quan hệ, tạo corridor hoặc inset khớp giao diện | Không xóa nhánh khoa học; không chia panel tùy tiện |
| “Trống và rời rạc” | Khoảng cách theo nhóm hay đều máy móc? | Siết cụm liên quan, giữ khoảng giữa ý khác nhau; không phóng to text để lấp | Whitespace cho feedback path có thể cần giữ |
| “Quá nhiều hộp” | Đối tượng dữ liệu bị vẽ như phép xử lý? | Thay đúng vai trò bằng array, document, state, tree hoặc nhãn | Không thay hộp bằng icon khó hiểu chỉ để đa dạng |
| “Complex nhưng không có trọng tâm” | Mọi nội bộ đều mở; novelty chỉ chiếm góc nhỏ? | Thu context đã quen, mở đúng cơ chế; lập danh sách omissions | Không làm baseline cố ý xấu hoặc mờ |
| “Chart đẹp nhưng khó so” | So sánh dùng nhiều legends, scale khác nhau, thứ tự category bất nhất? | Thử aligned view/direct label có giới hạn và cùng scale phù hợp | Không đổi trục để phóng đại lợi thế |
| “Hình trông như poster” | Title, slogan, icon lớn thắng nội dung? | Chuyển headline sang caption khi phù hợp; ưu tiên cơ chế và dữ liệu | Poster thực tế có nhiệm vụ khác paper figure |
| “Mọi thứ quá đều” | Alignment đúng nhưng scale/hierarchy thiếu? | Giữ trục căn, biến thiên diện tích theo vai trò | So sánh ngang cần mức nhấn công bằng |
| “Nhìn khác reference” | Khác proportion/contrast/type hay chỉ khác thuật toán? | Ghi ba delta thị giác; thử một delta/lượt | Không sao chép cơ chế để giống pixels |

## Thứ tự sửa đề xuất

Sai nội dung hoặc không đọc được → sai hierarchy/composition → sai cách tạo hình component → type/line/color → polish cục bộ. Với một composition đã tốt, có thể bắt đầu ở micro-craft; không redesign toàn bộ để sửa một nhãn.

Không dùng bảng như bộ quy tắc tự động. Mỗi ticket phải chỉ vùng, mục đích, thay đổi được phép và cách xem lại. Giữ nguyên bản trước để phát hiện sửa điểm này làm hỏng điểm khác.
