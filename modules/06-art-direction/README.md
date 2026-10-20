# M06 — Học reference và viết art direction

[Mục lục](../README.md) · [Reference card](../../templates/reference-card.md)

## Quyết định cần làm chủ

Biến “tôi muốn đẹp như hình này” thành brief đủ cụ thể để AI tạo hình mới cho nội dung khác. Không học bằng cách trộn tất cả điểm đẹp của mười paper thành một style trung bình.

## Kiến thức cần học

**Phù hợp trước nổi tiếng:** chọn reference có câu hỏi, mật độ và cấu trúc tương thích. Một teaser nhiều ảnh chưa chắc phù hợp với công thức hay một pipeline nhiều vòng phản hồi.

**Đọc bốn cấp:** silhouette toàn hình; cách ghép cụm; hình thức của object/line/type; màu và chi tiết. Xem cả toàn hình và crop component ở tỷ lệ chữ tương đương. Đừng đoán font chính xác khi chỉ có ảnh.

**Transfer chứ không copy:** học quan hệ chữ–khối, hierarchy, cách căn phần chung và lối đi của các đường phụ. Không mượn thêm query, loss hoặc dataset của reference để lấp chỗ thiếu trong phương pháp hiện tại.

**Primary direction:** mỗi phương án có một reference chính, có thể thêm một nguồn phụ cho một quyết định được chỉ rõ. Không dùng “kiểu NeurIPS” như một specification có sẵn; các paper có nhiều style khác nhau.

**Negative reference:** lưu điều không muốn lặp lại: wall of cards, viền mọi cấp bằng nhau, khoảng trống không có vai trò, chi tiết giả hoặc icon thừa. Một mẫu bạn đã chê không trở thành positive template vì agent gọi nó là pass.

## Materials

[The New Basics](https://papress.com/products/graphic-design-the-new-basics-revised-second-edition-paperback) cho modes of representation/hierarchy; [MIT Figure Design](https://mitcommlab.mit.edu/eecs/commkit/figure-design/) cho audience/message; [style atlas](../../resources/style-atlas.md) cho bài quan sát paper.

## Bài tập

Chọn hai reference khác cấu trúc. Với mỗi hình, viết ba quyết định muốn học, hai điều không phù hợp và một câu mô tả cá tính thị giác bằng các thuộc tính cụ thể. AI nhận một brief hoàn chỉnh, dựng một cụm đại diện cho mỗi direction, chưa dựng toàn bộ figure.

Bạn chọn hoặc từ chối; sau đó AI triển khai direction được duyệt lên toàn hình. Đánh giá lại vì cụm đẹp riêng lẻ có thể thành wall of cards khi nhân rộng.

Ví dụ brief: “Học sự phối hợp module đậm và layer mảnh của reference A; giữ chữ thoáng trong các vùng nhỏ. Không dùng ảnh 3D vì phương pháp không có dữ liệu không gian. Lần theo hai nhánh song song là nhiệm vụ chính; không thêm mục tiêu huấn luyện mới.”

## Đầu ra và điều kiện hoàn thành

Hai reference cards, một art-direction brief và một quyết định chọn. Đạt khi AI có thể biết cần đổi gì mà không cần bạn chọn từng tọa độ; bạn nêu được phần khác có chủ ý so với reference.

**Counterexample:** giống pixels nhất không phải thành công nếu nội dung nguồn khác hoặc hình mới kém đọc. Không gán điểm figure từ giải thưởng hoặc citation count của paper.
