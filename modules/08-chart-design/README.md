# M08 — Chart design: học quyết định, không học lệnh plot

[Mục lục](../README.md) · [Studio C](../../studio/03-evidence-panels.md)

## Quyết định cần làm chủ

Chọn cách biểu diễn giúp người đọc làm đúng việc: tra số, so sánh, xem phân bố, xu hướng, quan hệ hoặc trade-off. AI viết code; bạn chốt câu hỏi, encoding và giới hạn diễn giải.

## Kiến thức cần học

**Marks và channels:** điểm, đoạn, vùng, vị trí, độ dài và màu có công việc khác nhau. Không chọn chart chỉ vì có nhiều biến thì dùng nhiều màu. Một thuộc tính không được biến thành kích thước nếu người đọc sẽ hiểu nó là số đo khác.

**So sánh:** cùng trục hoặc small multiples có thể giúp đối chiếu; một chart chứa quá nhiều series làm mất nhiệm vụ chính. Chia panel cần giữ điều kiện và thang tương ứng hoặc công bố khác biệt.

**Trend và discrete choice:** đường nối gợi thứ tự/liên tục. Không nối các cấu hình độc lập thành đường cong mượt chỉ để trông tốt. Không phải mọi trục cần bắt đầu từ zero; bar encoding bằng độ dài cần baseline có ý nghĩa và không gây phóng đại.

**Direct labels và legend:** nhãn trực tiếp giảm việc tra màu ở chart ít đường nhưng có thể đè lên dữ liệu khi dày. Legend không phải mặc định xấu. Chọn theo mật độ và nhiệm vụ.

**Bảng cũng là thiết kế:** cần lookup chính xác có thể dùng bảng gọn. Không biến mọi bảng thành bubble plot để paper trông có nhiều hình hơn.

## Đọc có mục tiêu

- [Munzner — VAD](https://www.cs.ubc.ca/~tmm/vadbook/): What, Why, Marks & Channels, Multiple Views. Có video/slide công khai trên trang tác giả.
- [Wilke](https://clauswilke.com/dataviz/): chọn hình thức theo dữ liệu; [Multi-panel](https://clauswilke.com/dataviz/multi-panel-figures.html) cho nhiều phép đối chiếu.
- [Storytelling with Data](https://www.storytellingwithdata.com/books): xem ví dụ chọn nhấn mạnh và annotation; bối cảnh business không thay thế yêu cầu scientific evidence.

## Bài tập

Bạn đưa bảng dữ liệu thật được phép dùng hoặc bảng giả định có nhãn rõ. Viết hai câu hỏi khác nhau, chẳng hạn “giá trị nào cao nhất?” và “đánh đổi chất lượng–chi phí ra sao?”. AI đề xuất chart cho mỗi câu hỏi, tạo các bản xuất cùng data. Bạn không viết code.

Duyệt bằng ba việc: đọc một giá trị; diễn giải một xu hướng/so sánh; chỉ ra điều chưa thể kết luận. Sau đó chọn chart hoặc giữ bảng. Yêu cầu sửa annotation, scale hoặc grouping kèm lý do, không kéo điểm dữ liệu bằng tay.

## Đầu ra và điều kiện hoàn thành

Một chart-decision brief gồm câu hỏi, biến, encoding, units, scope, comparison controls và caption. Đạt khi giải thích được chart bị loại không phù hợp vì sao, chứ không chỉ vì ít đẹp.

**Counterexample:** Pareto chart không chứng minh latency khi trục x là FLOPs; một điểm không được ghép accuracy của config A với cost của config B.
