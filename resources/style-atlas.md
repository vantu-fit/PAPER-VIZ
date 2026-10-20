# Style atlas — học nhìn từ paper, không sưu tầm template

[Materials](README.md) · [Reference card](../templates/reference-card.md) · [M06](../modules/06-art-direction/README.md)

## Phạm vi

Đây là **danh mục bài quan sát** trên nhiều cơ chế, không phải bảng xếp hạng đẹp hoặc danh sách đã xác nhận figure score cao. Đã kiểm tra trang metadata/abstract chính thức của tám nguồn dưới đây. Curriculum chưa làm close-reading mới cho mọi figure: người học phải mở đúng hình và caption, ghi version/figure/page, rồi mới điền observation. Không giả là đã xem ảnh khi chỉ đọc abstract.

Không có artwork của tác giả khác được sao chép vào repo. Lưu URL/locator và nhận xét do bạn viết; kiểm tra quyền trước khi chia sẻ bản crop hoặc bản dựng lại.

## Tám bài để bắt đầu

| Paper | Trang nguồn | Câu hỏi thiết kế dành cho bạn — chưa phải kết luận về hình |
|---|---|---|
| U-Net: Convolutional Networks for Biomedical Image Segmentation | [arXiv](https://arxiv.org/abs/1505.04597) | Hình học của contracting/expanding paths có giải thích scale? Nét nào cần mạnh để lần được skip? |
| Mamba: Linear-Time Sequence Modeling with Selective State Spaces | [arXiv](https://arxiv.org/abs/2312.00752) | Có thể phân biệt state, operator và tính lặp bằng hình thức nào? Đừng mang Q/K/V từ reference khác vào. |
| Graph Attention Networks | [arXiv](https://arxiv.org/abs/1710.10903) | Cấu trúc lân cận và nhiều head được nhóm như thế nào? Màu có theo vai trò hay chỉ trang trí? |
| NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis | [arXiv](https://arxiv.org/abs/2003.08934) | Phần hình học, sampling và phép xử lý khác nhau về silhouette và annotation ra sao? |
| Efficient Memory Management for Large Language Model Serving with PagedAttention | [arXiv](https://arxiv.org/abs/2309.06180) | Cách biểu diễn địa chỉ, ownership và memory block khác gì với diagram layer neural? |
| BLIP-2 | [arXiv](https://arxiv.org/abs/2301.12597) | Nhóm lớn, module chính, layer nhỏ và mask có cùng mức nhấn không? Phần nào có viền, phần nào không? |
| STORM: Assisting in Writing Wikipedia-like Articles From Scratch with Large Language Models | [NAACL Anthology](https://aclanthology.org/2024.naacl-long.347/) | Actor, hội thoại và tài liệu có hình thức riêng không? Vòng phản hồi được tổ chức thành cụm hay thành đường đi quanh toàn trang? |
| Training language models to follow instructions with human feedback | [arXiv](https://arxiv.org/abs/2203.02155) | Các stage, con người, dữ liệu và model có thể được đọc đúng mà không cần cùng một dạng hộp không? |

Các câu hỏi do PAPER-VIZ biên soạn. Không chuyển kết quả, số liệu hoặc cơ chế của paper tham khảo sang phương pháp của bạn.

## Cách close-read một hình trong 30–45 phút

**Lượt 1 — chưa đọc AI critique.** Xem toàn hình ở kích thước gần trang paper. Ghi nơi mắt dừng đầu tiên, đường đọc và điều bạn chưa hiểu. Không dùng tên tác giả/giải thưởng làm lý do chọn.

**Lượt 2 — mức cụm.** Chọn một vùng: ghi số cấp phân nhóm, phần nào được thể hiện bằng glyph, phần nào bằng chữ, quan hệ khoảng trống trong/ngoài nhóm, và cách edge đi vào/ra. Không đoán số pixel hoặc họ font như sự thật.

**Lượt 3 — mức chi tiết.** So chữ với chiều cao block; nét viền với connector; màu nền với đối tượng chính; góc bo với kích thước component. Nêu một lựa chọn bạn thích và một lựa chọn bạn sẽ không học.

**Lượt 4 — đọc nguồn/caption.** Kiểm tra cách hiểu ban đầu. Chỗ nào mơ hồ do bạn thiếu kiến thức, chỗ nào do hình? Không bắt figure giải thích chi tiết nằm ngoài vai trò của nó.

**Lượt 5 — transfer.** Giao AI thể hiện một cơ chế khác bằng 2–3 nguyên lý vừa học. Giữ nội dung mới độc lập. Duyệt lại trong toàn hình: một cụm đẹp riêng có thể trở thành một bức tường thẻ khi lặp.

## Mẫu ghi một observation đúng

“Vùng [locator] dùng [thuộc tính nhìn thấy]. Tôi diễn giải nó là [ý nghĩa]; caption [xác nhận/chưa rõ]. Tôi muốn học [quan hệ], không sao chép [cơ chế/artwork]. AI cần tạo một đối chiếu [thay đổi duy nhất].”

## Chống quá khớp vào một gu

Mỗi ba bản phân tích thêm một counter-reference: một hình tối giản mà hiệu quả, một hình dày nhưng có tổ chức, hoặc một hình bạn không thích nhưng người đọc hiểu đúng. Không kết luận mọi paper phải dùng serif, màu nhạt, viền đen dày hay cấu trúc nhiều panel.

Khi đánh giá hai style, giữ tương đối giống complexity, kích thước đọc và thông tin. So một poster lớn với một hình một cột rồi kết luận style nào đẹp hơn sẽ trộn nhiều yếu tố.
