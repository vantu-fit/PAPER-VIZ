# Bắt đầu — Bạn là người chỉ đạo thiết kế

[Trang chủ](README.md) · [Lộ trình](ROADMAP.md)

## Năng lực đích

Nhìn một bản AI tạo và biết: nó yếu ở bố cục, component, chữ, màu, đường nối hay nội dung; lỗi nào sửa trước; phương án nào tốt hơn và tốt hơn cho ai. Không cần biết thư viện Python hoặc cú pháp draw.io để đưa ra quyết định đó.

Tuy nhiên, giao AI thực thi không đồng nghĩa chỉ nói “đẹp hơn”. Bạn phải học ngôn ngữ mô tả và chịu trách nhiệm cho yêu cầu. Một brief sai không được cứu bằng render đẹp.

## Bài chẩn đoán — 60 phút của bạn

Dùng một figure có quyền sử dụng mà bạn hiểu và một đoạn nguồn mô tả nó. Không tải dữ liệu nội bộ lên dịch vụ chưa được phép. Bài này dùng [brief](templates/design-brief.md), [phiếu lựa chọn](templates/selection.md) và [critique](templates/critique-ticket.md).

1. **10 phút:** viết người đọc cần hiểu gì, ba điều bất biến và hai điểm hình hiện tại chưa tốt.
2. **10 phút:** chọn một reference chính và giải thích học gì, không học gì. Chưa xem lời bình của AI.
3. **Giao AI:** tạo hai phương án khác nhau về bố cục, cùng nội dung và cùng kích thước đặt trong paper. Không cần bạn viết code. Thời gian AI chạy không tính vào 60 phút.
4. **15 phút:** xem các ảnh A/B và đoạn caption, chọn A/B/hòa/cả hai chưa đạt. Nêu bằng chứng tại vị trí cụ thể.
5. **10 phút:** viết ba yêu cầu sửa theo cấu trúc vị trí → lỗi → tác động → thay đổi → điều phải giữ.
6. **15 phút:** xem bản sửa và ghi lỗi đã hết, lỗi mới, phần chưa kiểm tra. Nếu chưa có người đọc độc lập, chỉ ghi tự review.

Lưu toàn bộ quyết định trước khi AI giải thích bản nào “tốt hơn”. Mục đích là luyện judgment của bạn, không học lại lời chấm của nó.

## Một bài học hoàn thành khi nào?

Không phải khi xem hết video. Hoàn thành khi bạn có thể **chỉ ra, giải thích, yêu cầu và kiểm tra** một quyết định thiết kế trên trường hợp chưa luyện trước đó. Ví dụ: phát hiện khung nhóm quá nặng; yêu cầu giảm tương phản của khung, giữ viền module; rồi kiểm tra xem ba nhóm vẫn tách được ở kích thước cuối hay không.

Nếu AI không tạo đúng yêu cầu, bạn vẫn có thể hoàn thành phần chẩn đoán bằng việc chỉ ra sai lệch. Nhưng chưa được đánh dấu sản phẩm đạt. Năng lực chỉ đạo và năng lực công cụ là hai điều khác nhau.

## Cách đọc materials

Đọc để trả lời một câu hỏi đang có trong bản thiết kế. Với khóa có bài tập thao tác phần mềm, chọn phần lý thuyết và dùng bài tập tự học của PAPER-VIZ. Đây không phải cách đáp ứng bài tập chính thức của khóa. Không phải mua mọi sách; xem [đường học miễn phí](resources/README.md) trước.

## Điều không cần học trong lộ trình bắt buộc

Không có Python, SVG/XML, macro LaTeX, thao tác pen tool, cài môi trường hoặc tự render PDF. Bạn chỉ cần biết yêu cầu đúng loại đầu ra, xem bản xuất thật và yêu cầu AI cung cấp kiểm tra khi cần. Không bỏ kiểm tra khoa học vì bản thân không viết code.

## Bài đầu tiên

Học [M01](modules/01-visual-judgment/README.md). Sau tuần 6 và tuần 12, làm lại cùng bài chẩn đoán nhưng giữ bản baseline để so sánh. Không gọi việc thích bản mới hơn là bằng chứng đủ: kiểm tra thêm bạn đã đọc đúng điều gì và AI có làm mất thông tin không.

Nguồn định hướng về thông điệp/người đọc: [MIT Figure Design](https://mitcommlab.mit.edu/eecs/commkit/figure-design/). Bài chẩn đoán và cách tổ chức trên là đề xuất riêng của curriculum.
