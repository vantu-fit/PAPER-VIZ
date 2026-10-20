# Studio B — hướng thiết kế xuyên nhiều kiến trúc

[Studio](README.md) · [M07](../modules/07-complex-diagrams/README.md)

## Mục tiêu

Chuyển các nguyên lý về typography, line, contrast và grouping sang cơ chế khác mà không mang theo topology của reference. Không chỉ thiết kế attention dưới nhiều tên gọi.

## Đầu vào

Chọn hai nguồn hiểu đủ để xác minh, khác họ: một CNN đa tỉ lệ và một graph model; một pipeline agent và một thuật toán tối ưu; hoặc một recipe dữ liệu và một hệ thống memory. Đây là ví dụ để chọn, không yêu cầu nguồn phải có tất cả các thành phần đó.

## Thiết kế trước khi giao AI

Với mỗi nguồn, viết reader question và nhóm thực thể: dữ liệu, phép xử lý, trạng thái, tham số hoặc actor. Phân biệt data/control/gradient/checkpoint/association nếu có. Chốt những gì có thể thu gọn.

Chọn macro layout theo câu hỏi: hai luồng căn tương ứng; overview-detail; temporal unroll; một vòng tương tác; hoặc bản đồ logic. Nêu lý do không chọn bố cục còn lại.

## AI thực hiện, bạn duyệt

AI dựng cụm đại diện cho mỗi cơ chế rồi triển khai toàn hình sau lựa chọn. Bạn xem hai hình cạnh nhau: hệ chữ/nét có cùng tinh thần không, nhưng object grammar có khác đúng không? Nếu cả hai đều thành encoder–attention–decoder thì việc transfer sai.

Yêu cầu một lượt sửa topology-free chỉ về style. Đối chiếu xem có nhánh bị mất, phép cộng bị đổi thành concat hoặc trạng thái bị hiểu sai không. Không dùng thuật ngữ “semantic invariant” như checklist trống: nêu đúng quan hệ cần giữ trong nguồn cụ thể.

## Đầu ra

Hai brief, hai nguồn tham khảo có ghi version, một style system dùng chung và lý do ngoại lệ, hai sản phẩm AI, bản critique từng hình và ghi chép transfer.

## Điều kiện hoàn thành

Bạn giải thích được phần style chuyển được (ví dụ cấp nét, type hierarchy) và phần không chuyển (glyph tensor sang graph node, khối mạng sang tài liệu). Một hình đơn giản có thể đúng hơn một hình dày nếu nhiệm vụ không cần pipeline phức tạp.
