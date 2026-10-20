# AI là người thực thi; bạn là người chỉ đạo

[Trang chủ](../README.md) · [M11](../modules/11-ai-direction/README.md)

Dùng các prompt này trong môi trường AI có công cụ dựng hình phù hợp. Chúng là lệnh làm việc, không cài plugin, không đảm bảo backend khả dụng và không thay việc học thiết kế của bạn.

| Công đoạn | Prompt | Quyết định con người phải giữ |
|---|---|---|
| Tạo và so phương án | [Design production](design-production.md) | Brief, reference, chọn phương án |
| Luyện một biến thị giác | [Controlled variants](controlled-variants.md) | Biến nào đổi, đọc sự khác biệt, lý do chọn |
| Sửa bản đã chọn | [Targeted revision](targeted-revision.md) | Phạm vi, bất biến và chấp nhận kết quả |
| Trao đổi và tự học | [Tutor and critic](tutor-and-critic.md) | Nhận xét của bạn trước, phản hồi AI sau |

## Yêu cầu chung

AI phải đọc nguồn, không tự thêm dữ liệu hoặc thuật toán. Các số liệu giả định có nhãn luyện tập. Khi có measured marks, chúng được tạo từ dữ liệu qua công cụ định lượng; không để image generator tự vẽ các con số nghiên cứu. Bản minh họa phong cách không phải empirical evidence.

Yêu cầu đúng source của bản xuất và mức editability thật. Một PNG được nhúng vào draw.io chưa phải diagram native. Phần chưa render hoặc chưa đối chiếu không được gắn pass. Bạn không cần học thao tác export để đòi bằng chứng này.

Không đưa dữ liệu nội bộ hoặc manuscript chưa công bố vào một dịch vụ chưa được phép. Đọc quy định sử dụng AI của venue/khóa học thực tế. Không dùng các prompt để giả danh tác giả paper hoặc giả nhận xét của reviewer.

## Cách tránh lệ thuộc gu của AI

Viết nhận xét và lựa chọn trước khi yêu cầu critique. Không chấp nhận một prompt chỉ nói “top-tier, elegant, beautiful”. Buộc bản brief nêu các quan hệ nhìn được; sau đó đánh giá sản phẩm chứ không đánh giá lời giải thích nghe hợp lý của agent.
