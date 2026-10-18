# PAPER-VIZ

**Học thiết kế figure, chart, diagram và trình bày paper khoa học — từ nền tảng thị giác đến một bộ hình có thể bảo vệ trước reviewer.**

Ngôn ngữ học: tiếng Việt, giữ thuật ngữ chuyên môn tiếng Anh để tra cứu. Đối tượng: researcher đã hiểu phương pháp và dữ liệu của mình nhưng muốn tự thiết kế, thay vì phụ thuộc vào template hoặc ảnh AI sinh sẵn.

> Mục tiêu không phải làm kết quả trông tốt hơn thực tế. Mục tiêu là giúp người đọc hiểu đúng đóng góp, lần theo cơ chế và kiểm tra bằng chứng với ít công sức hơn.

## Bắt đầu

1. Đọc [START-HERE](START-HERE.md) và làm bài chẩn đoán trước khi xem thêm khóa học.
2. Chọn nhịp học trong [ROADMAP — 24 tuần](ROADMAP.md).
3. Học theo [16 module](modules/README.md), mỗi module có kiến thức, bài luyện, tài liệu và điều kiện hoàn thành.
4. Lưu bài làm theo [portfolio](portfolio/README.md), dùng [rubric](rubrics/mastery.md) và nhận phản hồi từ người chưa biết bài.
5. Dùng [catalog tài liệu](resources/README.md), [atlas paper](resources/paper-atlas.md) và [template](templates/README.md) khi thực hành.

**24 tuần × 6–8 giờ/tuần** là ngân sách khởi đầu do curriculum này đề xuất, không phải cam kết thành chuyên gia sau 144–192 giờ. Tiếp tục vòng thiết kế–đánh giá–chỉnh sửa trên nhiều paper sau khóa nền tảng. [Capstone](projects/04-paper-package/README.md) là mốc đánh giá đầu tiên, không phải chứng chỉ A*.

## Cấu trúc năng lực

| Nhánh | Bạn phải tự làm được |
|---|---|
| Visual craft | Chọn hình dạng, tỷ lệ, chữ, màu, nét và khoảng cách có chủ đích; không nhầm đẹp với nhiều trang trí. |
| Scientific diagrams | Biến nguồn phương pháp thành đối tượng, quan hệ, trạng thái, pipeline và recipe trung thành với nguồn. |
| Evidence charts | Chọn chart theo câu hỏi, giữ provenance, cấu hình so sánh, đơn vị, uncertainty và dữ liệu thật. |
| Paper presentation | Kết nối claim–evidence–figure–caption–paragraph; tổ chức cả bài, không chỉ hình riêng lẻ. |
| Production & critique | Xuất bản vector, kiểm tra kích thước cuối, tái tạo từ source và dùng phản hồi người đọc để sửa. |

## Các module

| Module | Trọng tâm |
|---|---|
| [00](modules/00-orientation/README.md) | Chẩn đoán, tiêu chuẩn đầu ra và cách luyện |
| [01](modules/01-perception-composition/README.md) | Nhận thức thị giác, grouping, hierarchy và composition |
| [02](modules/02-typography-geometry/README.md) | Typography, toán học, tỷ lệ block và hệ nét |
| [03](modules/03-color-accessibility/README.md) | Màu semantic, colormap, tương phản và accessibility |
| [04](modules/04-vector-drawio/README.md) | draw.io, Inkscape và component chỉnh sửa được |
| [05](modules/05-diagram-grammar/README.md) | Ngữ pháp diagram, nhiều kiến trúc, không mặc định attention |
| [06](modules/06-complex-pipelines/README.md) | Pipeline nhiều nhánh, training recipe và chuyển checkpoint |
| [07](modules/07-chart-choice/README.md) | Chọn chart theo tác vụ người đọc |
| [08](modules/08-uncertainty/README.md) | Uncertainty, so sánh công bằng và giới hạn suy luận |
| [09](modules/09-matplotlib/README.md) | Matplotlib và đường xuất hình tái tạo được |
| [10](modules/10-ai-results/README.md) | Pareto, scaling, ablation, latency và nhiều benchmark |
| [11](modules/11-qualitative-evidence/README.md) | Qualitative panels, heatmap, embedding và image integrity |
| [12](modules/12-paper-narrative/README.md) | Paper narrative, caption, bảng và notation |
| [13](modules/13-publication/README.md) | LaTeX, export, venue profile và kiểm tra PDF cuối |
| [14](modules/14-critique/README.md) | Đọc style từ paper, critique và thử nghiệm khả năng hiểu |
| [15](modules/15-capstone/README.md) | Portfolio, capstone, chuyển giao và lộ trình nâng cao |

`modules/` là các **submodule học tập dạng thư mục**, không phải Git submodules trỏ tới repository khác. Không cần `git submodule update` và không có khóa học trả phí được sao chép vào repo.

## Materials và công cụ

Nhánh style dùng CalArts, Bang Wong và tài liệu thiết kế figure của MIT; nhánh chart dùng Wilke, Rougier, tài liệu Matplotlib và học phần UW CSE512. Đây là tuyển chọn học liệu, không phải một khóa được các tổ chức đó chứng nhận. Xem nguồn, cách truy cập và phạm vi đã kiểm tra trong [catalog](resources/README.md).

Khởi đầu bằng **draw.io + Inkscape** cho diagram và **Python/Matplotlib** cho chart. Illustrator là lựa chọn bổ sung, không là điều kiện để học. Code không làm hình kém chuyên nghiệp; thiết kế thiếu chủ đích và biểu diễn sai mới là vấn đề.

## Thực hành có thể chạy

```bash
python scripts/check_repo.py
python -m pip install -r requirements.txt
python examples/plot_tradeoff.py --out-dir /tmp/paper-viz-demo
python -m unittest discover -s tests -v
```

Các số liệu trong `examples/data/` là **SYNTHETIC — dữ liệu luyện tập**, không phải kết quả nghiên cứu. Không có benchmark hoặc log huấn luyện được tái dựng từ paper. Không dùng file luyện tập để đưa ra claim thật.

## Quy tắc học và phát hành

- Bắt đầu bằng một câu hỏi khoa học và nguồn; không bắt đầu bằng bảng màu.
- Học từ hình gốc: phân tích rồi chuyển nguyên lý sang cơ chế khác, không đổi nhãn trên artwork của người khác.
- Phân biệt sở thích thẩm mỹ, hiểu đúng và độ trung thực; không cộng điểm đẹp để bù cho sai khoa học.
- Không gọi một paper được giải là paper có “figure score cao” khi chưa có bằng chứng riêng.
- Không đưa manuscript mật, dữ liệu nội bộ, font thương mại hay tài liệu khóa học có bản quyền vào repo công khai.
- Khi dùng AI, ghi rõ vai trò; tác giả phải kiểm tra dữ liệu, topology, notation và bản xuất cuối.

## Trạng thái và nguồn gốc

Bản khởi tạo curriculum: **2026-10-19**. Nguồn bên ngoài được truy cập để kiểm tra tiêu đề, phạm vi học và trang hướng dẫn; không có tuyên bố đã học hết các khóa hoặc kiểm chứng cải thiện điểm reviewer. Bài tập, thời lượng, thứ tự học và rubric là đề xuất biên soạn riêng cho PAPER-VIZ.

Xem [CONTRIBUTING](CONTRIBUTING.md), [RIGHTS](RIGHTS.md) và [VERIFICATION](VERIFICATION.md). Chủ repository chưa chọn giấy phép chung; việc repo công khai không tự thay thế giấy phép của từng nguồn.
