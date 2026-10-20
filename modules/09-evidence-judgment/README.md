# M09 — Duyệt bằng chứng: đẹp nhưng không làm sai cách hiểu

[Mục lục](../README.md)

## Quyết định cần làm chủ

Biết thông tin nào phải kiểm tra sau khi AI xử lý dữ liệu hoặc tạo qualitative panel. Không tự triển khai thống kê, nhưng phải biết khi nào yêu cầu tính lại, bổ sung nguồn hoặc ngừng kết luận.

## Kiến thức cần học

**Nguồn và phạm vi:** mỗi point hoặc ảnh phải có cấu hình và điều kiện. Số được công bố trong paper khác với số bạn mới đo; aggregate khác với raw runs. Matching metadata không chứng minh thí nghiệm thật, nhưng thiếu metadata ngăn đối chiếu.

**Uncertainty:** SD, SE, CI và range không cùng nghĩa. Cần biết đơn vị lặp là seed, task, episode hay subject; mẫu số của phép tổng hợp là gì. Không yêu cầu AI tạo error bar từ mean khi thiếu dữ liệu. Kiểm tra khoảng của hai phương pháp riêng không tự thay cho uncertainty của chênh lệch.

**Qualitative fairness:** giữ sample, crop, scale và xử lý hiển thị tương ứng. Công bố curated hay representative. Không duyệt ảnh dự đoán tự sinh chỉ vì giống kỳ vọng. Một attention map phải có đại lượng, query/reference và cách normalize.

**Interpretation:** quan sát được chênh lệch không tự chứng minh cơ chế gây ra chênh lệch. Ablation cũng cần xem yếu tố khác có thay đổi không. Hình causal cần nguồn về quan hệ, không phải chỉ một mũi tên đẹp.

**Reviewer task:** người duyệt không kiểm tra bằng cách nhìn pixels và đoán số. Yêu cầu AI bảng đối chiếu data–marks, sample IDs và các phép biến đổi; chọn vài mục quan trọng kiểm tra lại ở nguồn. Khi không đủ hiểu thống kê, chuyển phần đó cho người có chuyên môn thay vì ký pass.

## Materials

[Wilke — Uncertainty](https://clauswilke.com/dataviz/visualizing-uncertainty.html); [Crameri et al.](https://www.nature.com/articles/s41467-020-19160-7) cho màu số đo; [Nature Figure Guide](https://research-figure-guide.nature.com/) cho yêu cầu sản phẩm có thể kiểm tra. Các khuyến nghị trong module là quy trình duyệt của PAPER-VIZ, không phải một kiểm định tự động.

## Bài tập

Cho AI dựng hai chart và một grid qualitative từ nguồn bạn cấp. Trong một bản luyện tập riêng, yêu cầu cố ý tạo một lỗi đã khai báo: đổi nhãn SD thành CI, trộn config, hoặc crop không tương ứng. Bản lỗi phải có nhãn TRAINING EXERCISE và không được đưa vào paper.

Bạn kiểm tra mà chưa đọc danh sách lỗi, ghi lý do nghi ngờ và dữ liệu cần xác minh. Sau đó mở đáp án, sửa và ghi trường hợp mình bỏ sót. Không tính tỷ lệ phát hiện trên vài bài tự tạo thành benchmark năng lực chung.

## Đầu ra và điều kiện hoàn thành

Một evidence review: giữ, yêu cầu sửa hoặc chưa đủ căn cứ; mỗi quyết định gắn nguồn và phạm vi. Đạt khi bạn sẵn sàng từ chối một hình hấp dẫn nhưng không thể diễn giải trung thực.

**Counterexample:** không phải mọi số đều cần error bar; deterministic count không được gán uncertainty giả để trông khoa học.
