# M02 — Composition: tổ chức toàn hình trước khi chọn màu

[Mục lục](../README.md)

## Quyết định cần làm chủ

Chọn đường đọc, vị trí trọng tâm, cách nhóm và mức phân chia panel. Bạn mô tả bố cục bằng lời hoặc chú thích trực tiếp trên preview; AI đặt tọa độ và dựng source.

## Kiến thức cần học

**Macro–meso–micro:** toàn hình có một cấu trúc chính; mỗi vùng là một cụm giải thích; trong cụm có chi tiết vừa đủ. Không cần ba khung lồng nhau mới có ba cấp. Có thể phân cấp bằng alignment, khoảng trống và tỷ lệ.

**Proximity và alignment:** khoảng cách bên trong nhóm nên thể hiện chúng liên quan, khoảng cách giữa nhóm nên giúp tách ý nghĩa. Nhưng không ấn định cùng một khoảng cách cho mọi hình. Một corridor lớn có thể cần thiết để giữ nhánh phản hồi dễ lần theo.

**Figure–ground:** nền giúp nhận ra đối tượng. Nếu quá nhiều nền màu và khung bao, người đọc phải giải mã thêm các vùng không mang nghĩa. Ngược lại, bỏ mọi nền có thể làm mất ranh giới tham số hoặc tài nguyên.

**Rhythm:** sự lặp đúng chỗ giúp theo dõi giai đoạn, tầng hoặc thời gian. Phải nói rõ đang lặp theo nghĩa nào. Nhịp không đồng nghĩa chia đều mọi panel.

**Information budget:** một overview không phải implementation manual. Phần nào thu gọn phải được chốt trong brief; không để AI bỏ nhánh để giảm rối. Inset cần khớp giao diện với vùng được mở rộng.

## Đọc có mục tiêu

- [Bang Wong — Layout](https://www.nature.com/articles/nmeth.1711): đọc cách tổ chức trang và grid; không lấy tỷ lệ vàng làm luật bắt buộc.
- [Wilke — Multi-panel figures](https://clauswilke.com/dataviz/multi-panel-figures.html): học quan hệ giữa panel và điều kiện đối chiếu.
- [CalArts](https://www.coursera.org/learn/fundamentals-of-graphic-design): phần Composition and Visual Hierarchy.

## Bài tập chỉ đạo

Dùng một pipeline có hai nhánh chung đầu vào và một bước kết hợp. Yêu cầu AI dựng: A hai luồng ngang căn tương ứng; B overview và một vùng phóng lớn. Giữ cùng nội dung bắt buộc, caption và chiều rộng dự kiến. So sánh không chỉ trên ảnh phóng lớn mà trong trang đọc thử.

Bạn trả lời: mắt đi đâu đầu tiên; phần mới ở đâu; có thể lần một đường từ đầu vào đến đầu ra không; vùng nào chiếm diện tích nhưng chưa có công việc rõ ràng?

Ví dụ edit ticket: “Đưa điều kiện sang dải phía trên, giữ nhánh dữ liệu chính ngang ở giữa. Không đổi direction hoặc hợp nhất hai đầu vào. Duyệt lại bằng việc lần từng loại đường.”

## Đầu ra và điều kiện hoàn thành

Hai preview do AI dựng; một sơ đồ quyết định bằng lời; một phương án được chọn và một lý do không chọn phương án kia. Đạt khi bố cục được giải thích bằng nội dung, không bằng ‘bên trái còn trống’.

**Counterexample:** equal panels rất hợp cho so sánh có cùng điều kiện. Bố cục bất đối xứng không tự chuyên nghiệp hơn.
