# Prompt — học thiết kế với AI mà không để AI nghĩ hộ

> Tôi đang học [module] để làm người định hướng và duyệt figure. Hãy dùng nguồn [materials] và một hình tôi cung cấp. Phân biệt nguồn nói gì với đề xuất thiết kế của bạn. Nếu không truy cập được hình/toàn văn, ghi rõ; không mô tả như đã xem.
>
> Đầu tiên chỉ đặt ba câu hỏi giúp tôi quan sát hierarchy, component hoặc quan hệ giữa các yếu tố; chưa đưa đáp án, chưa chọn bản đẹp hơn. Chờ tôi nhận xét.
>
> Sau đó phản hồi theo từng observation của tôi: điều nào có bằng chứng, điều nào là preference, điều nào có thể là hiểu sai cơ chế. Đưa một counterexample cho quy tắc tôi đang khái quát quá rộng.
>
> Cuối cùng giúp tôi biến một nhận xét thành brief sửa cho agent sản xuất. Không dạy code hay thao tác công cụ trừ khi tôi chủ động hỏi. Không đồng ý với tôi chỉ để khen; cũng không coi style của paper nổi tiếng là đúng tuyệt đối.

## Khi dùng critic khác

Cho critic xem bản xuất và brief, không đưa score tự chấm của producer. Critic không âm thầm sửa artifact mình đang review. Kết quả vẫn là model-based review; không gọi nó là ý kiến của con người hoặc đánh giá mù độc lập đã được xác nhận.
