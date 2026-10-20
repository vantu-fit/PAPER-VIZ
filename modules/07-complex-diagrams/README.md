# M07 — Art direction cho kiến trúc và pipeline phức tạp

[Mục lục](../README.md) · [Studio B](../../studio/02-complex-pipeline.md)

## Quyết định cần làm chủ

Chọn ngữ pháp thị giác theo cơ chế, không theo từ khóa AI. Chỉ đạo được một pipeline nhiều nhánh mà vẫn giữ style thống nhất; không yêu cầu mọi mô hình có Q/K/V, token hoặc encoder–decoder.

## Kiến thức cần học

Tách bốn câu hỏi: figure có nhiệm vụ gì; cơ chế nào thực sự tồn tại; đối tượng dữ liệu là gì; style nào phù hợp? Cùng dữ liệu hình ảnh có thể đi qua CNN, diffusion hoặc một thuật toán hình học. Cùng style có thể được chuyển sang cơ chế mới, nhưng không mang theo kiến trúc của reference.

| Họ cơ chế | Đối tượng cần cân nhắc thể hiện | Sai lầm cần nhận ra |
|---|---|---|
| CNN / đa tỉ lệ | Feature maps, độ phân giải, đường skip | Mọi tầng cùng một hộp nên mất cấu trúc scale |
| RNN / SSM / động lực | Trạng thái, thời gian, cập nhật, solver | Lặp tầng bị hiểu thành lặp thời gian |
| GNN / tập điểm | Lân cận, message, aggregate, hình học | Thêm attention weights dù nguồn không có |
| VAE / GAN / diffusion / flow | Latent, sampling, forward/reverse, đối thủ hoặc ánh xạ | Một pipeline sinh chung chung thay cơ chế thật |
| RL / planning / agent | Environment, action, observation, memory, search | Feedback bị vẽ như gradient hoặc ngược lại |
| Systems / phân tán | Ranh giới tài nguyên, queue, ownership, communication | Server icon đẹp nhưng giấu vị trí dữ liệu |
| Tree / kernel / optimization / theory | Branch, similarity, constraint, iterate, dependency | Ép mọi đối tượng vào mạng neural |
| Training/data recipe | Dataset, lọc, checkpoint, objective và đánh giá | Mũi tên dữ liệu và chuyển trọng số không phân biệt |

Đây là bản đồ quyết định thiết kế, không phải mô tả đầy đủ của từng họ. Lấy quan hệ cụ thể từ manuscript. Với kiến trúc lai, ghi rõ đối tượng đi qua mỗi giao diện. Một mũi tên phóng lớn không phải một phép tính mới.

## Materials

[Munzner](https://www.cs.ubc.ca/~tmm/vadbook/): Networks/Trees và Focus+Context; [Marshall et al.](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0318800): sự đa dạng cách đọc diagram. Nghiên cứu sau không xác nhận một style tốt cho mọi người hoặc đánh giá curriculum này.

## Bài tập chỉ đạo

Chọn một nguồn đã hiểu có hai họ cơ chế hoặc nhiều giai đoạn. Bạn viết contract một trang: đối tượng, đường dữ liệu/điều khiển/checkpoint, phần có thể thu gọn và phần bắt buộc. AI đề xuất hai bố cục rồi dựng một bố cục bạn chọn.

Lần thứ hai dùng một cơ chế không cùng họ, giữ tinh thần typography/line nhưng thay silhouette và object grammar. Bạn phải chỉ ra phần nào của style chuyển được và phần nào không.

## Đầu ra và điều kiện hoàn thành

Một architecture direction, một stage ledger khi cần và hai sản phẩm AI khác họ. Đạt khi đọc được các đường chính, phân biệt trạng thái và không tăng chi tiết chỉ để tạo vẻ phức tạp.

**Counterexample:** paper lý thuyết có thể cần phản ví dụ hình học thay vì pipeline; dùng bảng hoặc phương trình cũng là quyết định thiết kế đúng.
