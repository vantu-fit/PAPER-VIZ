# M11 — Chỉ đạo AI: brief, chọn phương án, sửa có phạm vi

[Mục lục](../README.md) · [Prompts](../../ai/README.md)

## Quyết định cần làm chủ

Biết giao đúng vấn đề thiết kế, không giao một chuỗi tính từ. Tách khám phá phương án với sửa chi tiết, giữ quyền chọn của bạn và không để agent tự thay khoa học khi làm đẹp.

## Kiến thức cần học

**Brief có thứ tự:** người đọc/câu hỏi → nội dung bất biến → phạm vi và kích thước → reference/điều học → hierarchy/component/type/color/line → output và cách duyệt. Đừng mở đầu bằng “publication-ready 4K” rồi bỏ qua nội dung.

**Diverge rồi converge:** lúc đầu yêu cầu hai hoặc ba phương án khác về bố cục, không mười lần đổi màu. Khi đã chọn, sửa có mục tiêu. Đổi toàn bộ hướng sau mỗi comment gây mất những quyết định đã đúng.

**Constraint vs instruction:** “giữ branch A và B tách riêng” là bất biến; “thử đưa conditioning phía trên” là giả thuyết thiết kế. Ghi rõ để AI biết phần nào được thử.

**Production evidence:** yêu cầu source chỉnh sửa được, actual render, before/after và danh sách chưa kiểm tra. Không gọi PNG độc lập là render đã xác minh của draw.io; không gọi ảnh nằm trong SVG là mọi component chỉnh được.

**Budget:** chốt số phương án và số lần review hợp lý cho bài. Ba vòng là ngân sách đề xuất, không cho phép bàn giao lỗi nghiêm trọng. Khi không đạt, dừng với bản draft và ghi vấn đề, không tự gán pass.

## Materials

[Discussing Design](https://www.oreilly.com/library/view/discussing-design/9781491902394/): chọn Understanding Critique và Making Critique a Part of Your Process. Nội dung về critique/collaboration, không phải khóa prompt engineering. Quy trình AI trong module là thiết kế riêng của PAPER-VIZ, chưa được chứng minh tăng điểm reviewer.

## Bài tập: kiểm soát hai lượt sửa

Bạn viết [brief](../../templates/design-brief.md), giao AI dựng hai lựa chọn. Sau khi chọn, tạo hai tickets tuần tự: một đổi typography, một đổi cách nhóm. Mỗi ticket nêu vùng được đổi và vùng giữ nguyên. Bạn xem before/after và kiểm tra lần sửa sau còn giữ cải thiện trước không.

Ví dụ: “Panel b: tên module đang mạnh hơn công thức trung tâm. Giảm weight tên module và làm rõ công thức; giữ palette, topology, kích thước đặt hình. Gửi crop vùng b và toàn hình sau sửa. Không đổi dấu hoặc notation.”

## Đầu ra và điều kiện hoàn thành

Một brief, selection log, hai tickets, acceptance log và output của AI. Đạt khi agent có thể thực thi mà bạn không phải chỉ từng dòng code, và bạn phát hiện được nếu nó vượt phạm vi.

**Counterexample:** không buộc dùng một backend khi nó không phù hợp; thay backend là lựa chọn sản xuất, nhưng không được đánh tráo mức editability hoặc che việc chưa render.
