# Critique — từ cảm giác đến quyết định thiết kế

[Trang chủ](../README.md) · [Rubric](rubric.md) · [Chẩn đoán](diagnostic-atlas.md) · [Bài có lời bình](worked-examples.md)

Bạn không học để thay người vận hành phần mềm. Bạn học để chỉ ra **thiết kế đang làm gì, tác động đến người đọc ra sao và cần thay điều gì**. Không cần yêu cầu AI chọn từng tọa độ.

## Vòng critique

1. Xem bản render + caption, chốt nhận xét của bạn trước khi xem phân tích AI.
2. Đối chiếu mục đích và ràng buộc nguồn; phân loại lỗi hình thức, diễn giải hoặc nội dung.
3. Chọn tối đa ba vấn đề ưu tiên cho một lượt, không tung danh sách thay đổi toàn trang.
4. Viết ticket: vị trí → quan sát → tác động → mục tiêu sửa → bất biến → cách nghiệm thu.
5. Giao AI thực thi, xem before/after ở cả crop và toàn hình; chấp nhận, yêu cầu sửa hoặc quay về bản trước.

Ba vấn đề/lượt là ngân sách thực hành, không luật thiết kế. Một lỗi khoa học nghiêm trọng cần dừng phát hành ngay, không đợi vòng làm đẹp.

## Phân biệt bốn phát biểu

**Observation:** “Viền khung ngoài và viền operator đều nặng, cả hai chiếm mắt.” Có thể kiểm tra trên ảnh.

**Interpretation:** “Tôi tưởng khung ngoài là một phép xử lý.” Có thể đúng hoặc sai; hỏi caption/nguồn.

**Design hypothesis:** “Giảm mức nhấn của khung ngoài có thể giúp operator nổi rõ.” Đây là đề xuất để thử.

**Preference:** “Tôi thích góc vuông hơn bo nhẹ.” Hợp lệ như sở thích, nhưng chưa chứng minh góc vuông dễ hiểu hơn.

Tách bốn loại giúp tránh biến gu thành chân lý hoặc biến một giải pháp tình cờ thành luật cho mọi paper.

## Nhận xét tốt không chỉ là mệnh lệnh

“Đổi hết sang đen” chỉ nói cách làm. Tốt hơn: “Trong panel B, màu của connector và nền khá gần nhau nên nhánh quay về khó lần. Hãy tăng phân biệt ở chính nhánh này, giữ mapping màu các phương pháp và không làm baseline nhạt đi.” AI có thể đề xuất tăng nét, đổi vị trí hoặc dùng nhãn; bạn duyệt giải pháp.

## Những quyền quyết định phải ở bạn

Chọn thông điệp, reference, mức chi tiết, thay đổi nội dung được phép, lựa chọn A/B và chấp nhận cuối. AI có thể tư vấn nhưng không được tự biến phiếu chưa điền thành approval. Một AI critic khác vẫn là model-based review, không là ý kiến của researcher thật.

## Dừng ở đâu?

Dừng khi các lỗi chặn đã hết hoặc được ghi rõ chưa xác minh, mục tiêu của lượt đã đạt, và sửa tiếp không giải quyết một vấn đề cụ thể. Không dừng chỉ vì AI tự cho 9/10. Nếu công cụ không thực hiện được, giữ bản có trạng thái draft và nêu vấn đề; không hạ yêu cầu để hợp thức hóa output.

Khái niệm critique được định hướng bởi [Discussing Design](https://www.oreilly.com/library/view/discussing-design/9781491902394/). Vòng thao tác và phiếu đánh giá ở đây là đề xuất của PAPER-VIZ, chưa được đánh giá bằng nghiên cứu người dùng.
