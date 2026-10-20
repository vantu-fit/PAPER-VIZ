# M05 — Color: sắc độ, ý nghĩa và mức nhấn

[Mục lục](../README.md)

## Quyết định cần làm chủ

Chọn vai trò của màu trước mã màu. Duyệt được độ tương phản, mức nhấn, sự nhất quán và cách màu biểu diễn dữ liệu. Không cần tự cài thư viện colormap.

## Kiến thức cần học

**Ba công việc khác nhau:** màu phân loại vai trò; màu biểu diễn số đo; màu tạo hierarchy. Không lấy palette của các module áp lên heatmap định lượng. Không dùng cùng một màu cho hai vai trò mâu thuẫn giữa các figure mà không giải thích.

**Hue, saturation, lightness:** một palette có nhiều hue nhưng cùng mức nhấn có thể làm mọi thứ cạnh tranh. Nền nhạt, đối tượng vừa và điểm nhấn mạnh là lựa chọn để thử, không phải công thức bắt buộc. Làm nhạt toàn bộ thường không sửa được bố cục.

**Foreground/background:** phải xem màu cùng chữ và viền trên nền thực. Chữ trắng trên màu mạnh có thể rõ; chữ trắng trên pastel thường khó đọc. Không kết luận bằng swatch đứng một mình.

**Màu dữ liệu:** chọn loại thang theo đại lượng và giữ ý nghĩa colorbar/normalization. Một vùng sáng không được tạo ra tầm quan trọng mà số đo không có. Kiểm tra grayscale hữu ích nhưng không tương đương kiểm tra mọi dạng suy giảm nhận màu.

**Emphasis có đạo đức:** làm nổi contribution không cho phép làm baseline không đọc được. Màu xám không tự đồng nghĩa frozen, skipped hoặc stop-gradient; cần nguồn và nhãn.

## Materials

- [Wilke — Color basics](https://clauswilke.com/dataviz/color-basics.html): cách dùng màu để phân biệt, biểu diễn và nhấn.
- [Crameri, Shephard, Heron — The misuse of colour in science communication](https://www.nature.com/articles/s41467-020-19160-7): học nguy cơ màu làm biến dạng cách đọc dữ liệu. Không cần học cách code palette.
- [CalArts Fundamentals](https://www.coursera.org/learn/fundamentals-of-graphic-design): phần Shape & Color.

## Bài tập

Bạn lập bảng role → màu/shape/line hỗ trợ. AI dựng hai palette cùng bố cục: một tương phản tiết chế và một nhấn mạnh hơn, sau đó cung cấp bản màu/grayscale. Nếu có dữ liệu, giữ nguyên data và normalization trong mọi bản.

Bạn duyệt: nhìn thấy gì trước; nhóm nào chưa phân biệt được; màu nào đang mang hai nghĩa; chữ nào mất tương phản; có điểm nào bị nhấn mà không được nguồn hỗ trợ? Giao AI sửa từng vấn đề, không chỉ đổi tất cả sang màu mình thích.

## Đầu ra và điều kiện hoàn thành

Bảng vai trò–encoding, hai preview và quyết định có lý do. Đạt khi giải thích được tại sao dùng màu đó trong ngữ cảnh, và không nhầm đẹp với accurate.

**Counterexample:** grayscale không phải style bắt buộc; một palette nhiều màu có thể đúng khi thật sự có nhiều nhóm cần phân biệt. Không gọi palette “colorblind-safe” nếu chưa kiểm tra cách dùng thực tế.
