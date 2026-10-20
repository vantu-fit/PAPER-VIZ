# PAPER-VIZ — Scientific Art Direction

**Học để quyết định thiết kế, chỉ đạo AI và duyệt figure/chart/diagram cho paper. Không học để tự viết code hoặc tự thao tác phần mềm vẽ.**

> Bạn quyết định hình cần nói gì, nên trông như thế nào và vì sao một phương án tốt hơn. AI dựng hình, chỉnh source, tạo biến thể và xuất file. Bạn giữ quyền duyệt nội dung và chất lượng cuối cùng.

Đây là bản thiết kế lại theo yêu cầu của chủ repo. Lộ trình cũ thiên về draw.io, Inkscape, Matplotlib và thao tác dựng hình đã được thay bằng **visual literacy → art direction → critique → paper-level editorial judgment**. Không có bài tập bắt buộc lập trình, kéo shape hoặc tự dựng lại figure bằng tay.

## Bắt đầu học

- [START-HERE](START-HERE.md): bài chẩn đoán năng lực nhìn và nhận xét, không cần biết công cụ.
- [ROADMAP](ROADMAP.md): 12 tuần nền tảng và 12 tuần studio nâng cao.
- [12 submodule](modules/README.md): kiến thức, tài liệu chọn lọc, bài tập chỉ đạo AI và điều kiện hoàn thành.
- [Materials](resources/README.md): sách, khóa học, bài viết; chỉ rõ phần nên đọc và cách áp dụng.
- [Style atlas](resources/style-atlas.md): học từ paper bằng câu hỏi thiết kế, không bằng danh tiếng.
- [Critique handbook](critique/README.md): biến “nhựa”, “rối”, “không sang” thành yêu cầu sửa có thể kiểm tra.
- [Brief và phiếu duyệt](templates/README.md) · [Prompt cho AI](ai/README.md) · [Studio và capstone](studio/README.md).

## Phân công con người và AI

| Công việc | Bạn học và quyết định | AI thực thi |
|---|---|---|
| Mục đích | Câu hỏi người đọc, claim, thứ tự ưu tiên, phạm vi phải giữ | Trích nguồn, liệt kê chỗ chưa rõ, chuẩn bị bản tóm tắt |
| Art direction | Reference chính, bố cục, ngôn ngữ component, typography, màu và hệ nét | Dựng phương án A/B đúng brief, không tự thêm cơ chế |
| Chart | Cần so sánh điều gì, encoding, scale, điều kiện và uncertainty | Đọc dữ liệu, tính toán theo protocol, vẽ và kiểm tra provenance |
| Critique | Chỉ ra vùng lỗi, nguyên nhân, mức ảnh hưởng và sửa ưu tiên | Chỉnh đúng vùng, giữ phần đã duyệt, xuất before/after |
| Phát hành | Duyệt hình trong paper thật, nội dung, quyền sử dụng và giới hạn | Xuất source/vector/preview, kiểm tra kỹ thuật và báo phần chưa làm |

Bạn không phải học cách sửa kerning bằng chuột, nhưng cần nhìn ra spacing chưa tốt và yêu cầu AI sửa. Bạn không phải code error bar, nhưng cần biết nó biểu diễn gì để không duyệt một hình đẹp mà sai.

## 12 submodule

| Module | Quyết định cần làm chủ |
|---|---|
| [01 — Visual judgment](modules/01-visual-judgment/README.md) | Vì sao hình đẹp hoặc chưa đẹp? Phân biệt taste, clarity và truth. |
| [02 — Composition](modules/02-composition/README.md) | Đặt trọng tâm ở đâu? Nhóm, căn, chia panel và dùng khoảng trắng thế nào? |
| [03 — Component & line craft](modules/03-component-craft/README.md) | Hình dáng, tỷ lệ, border, góc, connector và cách ghép cụm. |
| [04 — Typography](modules/04-typography/README.md) | Hệ chữ, độ đậm, khoảng cách, toán học và quan hệ chữ–khối. |
| [05 — Color](modules/05-color/README.md) | Palette, sắc độ, vai trò màu, tương phản và colormap. |
| [06 — Reference & art direction](modules/06-art-direction/README.md) | Học nguyên lý từ reference, viết style brief, không sao chép skin. |
| [07 — Complex diagrams](modules/07-complex-diagrams/README.md) | Kiến trúc đa dạng, pipeline, recipe, topology và nhiều cấp chi tiết. |
| [08 — Chart design](modules/08-chart-design/README.md) | Chọn biểu diễn theo câu hỏi, không theo template. |
| [09 — Evidence judgment](modules/09-evidence-judgment/README.md) | Duyệt dữ liệu, uncertainty, qualitative panels và giới hạn kết luận. |
| [10 — Paper presentation](modules/10-paper-presentation/README.md) | Cả bộ figure, caption, bảng và phần chữ tạo thành một lập luận. |
| [11 — AI design direction](modules/11-ai-direction/README.md) | Brief, phương án, phản hồi, scope thay đổi và dừng đúng lúc. |
| [12 — Critique & mastery](modules/12-critique-mastery/README.md) | Duyệt có lý do, thử người đọc và chuyển năng lực sang paper mới. |

Các submodule là **thư mục bài học**, không phải Git submodules. Không cần cài môi trường lập trình để học. Có thể đọc hoàn toàn trên GitHub; công cụ sản xuất thuộc môi trường AI của bạn.

## Nhịp học

**Tuần 1–12:** một module/tuần, khoảng 4–6 giờ học và đánh giá của con người. **Tuần 13–24:** studio trên các cơ chế khác nhau và một paper thật. Thời gian chờ AI hoặc chạy thí nghiệm không tính vào số giờ này. Đây là ngân sách đề xuất, không là cam kết trở thành chuyên gia hoặc đạt điểm presentation cụ thể.

Một buổi học: xem nguồn → tự nêu quyết định → giao AI dựng → so sánh bản xuất → viết critique → duyệt hoặc yêu cầu sửa. Sản phẩm học tập chính là **brief, quyết định chọn, phiếu sửa và hồ sơ duyệt**, kèm hình do AI tạo.

## Materials trọng tâm

CalArts và sách của Ellen Lupton cho ngôn ngữ thiết kế; Bang Wong cho figure khoa học; Wilke và Munzner cho thiết kế chart; *Discussing Design* cho critique; MIT Communication Lab cho thông điệp và người đọc. Chi tiết, đường dẫn và giới hạn truy cập nằm trong [catalog](resources/README.md).

Các bài tập trong repo là bài tập tự học riêng, không phải cách thay thế bài nộp/chứng chỉ của khóa gốc. Quy định về AI của từng khóa, hội nghị hoặc nguồn dữ liệu vẫn phải được tuân thủ.

## Ranh giới chất lượng

**Không phải mục tiêu:** làm giả nét vẽ tay, che việc dùng AI, tối đa số hình, học mọi phần mềm, hoặc làm phương pháp trông tốt hơn dữ liệu.

**Mục tiêu:** sản phẩm có chủ đích, đẹp trong ngữ cảnh học thuật, dễ đọc, trung thành với nghiên cứu và có thể yêu cầu chỉnh sửa chính xác.

Một paper được giải không tự có “figure score cao”. Một điểm style do AI tự chấm không xác nhận tiến bộ. Dùng [rubric](critique/rubric.md) để tách chất lượng hình thức, hiểu đúng và trung thực; không cộng chúng thành điểm reviewer giả.

[Phạm vi kiểm chứng](VERIFICATION.md) · [Quyền nội dung](RIGHTS.md) · [Quy tắc đóng góp](CONTRIBUTING.md).
