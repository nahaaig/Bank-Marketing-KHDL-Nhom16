# Mid-term 2 – Project 2: Bank Marketing Dataset (Nhóm 16)

Phân tích dữ liệu tiếp thị của một ngân hàng để tìm yếu tố làm tăng khả năng khách hàng đăng ký tiền gửi kỳ hạn (`deposit`).

- **Dữ liệu:** [Bank Marketing Dataset – Kaggle (janiobachmann)](https://www.kaggle.com/datasets/janiobachmann/bank-marketing-dataset), file `bank.csv` (11.162 dòng × 17 cột).
- **Quy trình:** 4 giai đoạn: (1) thu thập và đánh giá dữ liệu, (2) tiền xử lý và làm sạch, (3) phân tích và trực quan hóa, (4) đánh giá tác động và khuyến nghị.

## Nội dung repo

| File | Mô tả |
|---|---|
| `NHOM16_PRJ2_MID_TERM_FINAL.ipynb` | Notebook chính, đã chạy sẵn kết quả (hình và bảng nằm ngay trong notebook) |
| `bank.csv` | Dữ liệu gốc |
| `NHOM16_PRJ2_BaoCao.pdf` | Báo cáo PDF |

## Cách chạy lại trên Google Colab

1. Vào [colab.research.google.com](https://colab.research.google.com), chọn **File → Upload notebook**, rồi chọn file `NHOM16_PRJ2_MID_TERM_FINAL.ipynb`.
2. Upload `bank.csv` vào Colab (biểu tượng thư mục bên trái). Nếu bỏ qua bước này, notebook sẽ tự đọc `bank.csv` từ repo GitHub này; nếu vẫn không đọc được, Colab sẽ hiện hộp chọn file để upload.
3. Chọn **Runtime → Run all**. Notebook chạy từ đầu đến cuối, không cần sửa code.

Ghi chú:
- Ô 1.2c kiểm tra dữ liệu đúng bản `bank.csv` gốc (11.162 dòng × 17 cột) trước khi phân tích. Nếu dùng nhầm file khác, notebook sẽ dừng và báo lỗi.
- Khi chạy, notebook tự tạo thư mục `figures/` (hình PNG) và `tables/` (bảng CSV). Ô cuối cùng nén chúng thành `figures.zip`, `tables.zip` và tự tải về máy khi chạy trên Colab.
