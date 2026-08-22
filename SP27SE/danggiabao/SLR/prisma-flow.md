# PRISMA 2020 Flow Diagram

| Giai đoạn    | Nội dung                  | Số lượng | Ghi chú                                            |
| ------------ | ------------------------- | -------: | -------------------------------------------------- |
| 1. Nhận diện | Paper từ database search  |      241 |                                                    |
| 1. Nhận diện | Sau dedup                 |      241 | Khớp số dòng trong `01_all_records.csv`            |
| 2. Sàng lọc  | Sàng lọc Title & Abstract |      241 | Loại V1: 204 bài                                   |
| 2. Sàng lọc  | Đọc full-text             |       37 | Gồm 35 Included và 2 Maybe từ V1                   |
| 2. Sàng lọc  | Loại sau đọc full-text    |       24 | Loại V2                                            |
| 3. Tổng hợp  | Final included            |       13 | Khớp số dòng Include trong `03_final_included.csv` |

## Chi tiết bài bị loại

| Vòng | Mã lý do    | Số lượng | Nội dung                                     |
| ---- | ----------- | -------: | -------------------------------------------- |
| V1   | EC-O        |       96 | Ngoài phạm vi / không phải ngưng thở ban đêm |
| V1   | NO ABSTRACT |       69 | Thiếu bản tóm tắt, không đủ dữ liệu          |
| V1   | EC-N        |       17 | Bài tổng quan / Review / Editorial           |
| V1   | EC-W        |       11 | Thiết bị đeo / cảm biến dán tiếp xúc da      |
| V1   | EC-1        |       10 | Đối tượng trẻ em / sơ sinh                   |
| V1   | EC-S        |        1 | Báo cáo ca bệnh đơn lẻ / Case study          |
| V2   | No access   |       12 | Không truy cập được bài toàn văn             |
| V2   | EC-W        |        6 | Dán máy lên người / cảm biến tiếp xúc cơ thể |
| V2   | EC-S        |        3 | Tóm tắt kỷ yếu hội nghị ngắn, thiếu thông số |
| V2   | EC-O        |        2 | Mục tiêu không khớp bài toán OSA tự nhiên    |
| V2   | EC-1        |        1 | Thực nghiệm trên trẻ nhỏ                     |
