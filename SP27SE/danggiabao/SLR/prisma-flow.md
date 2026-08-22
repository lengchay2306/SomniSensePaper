# PRISMA Flow

## Giai đoạn 1: Nhận diện (Identification)

```mermaid
flowchart TD
    A["Paper từ database search<br/>N = 241"]
    B["Sau dedup<br/>N = 241"]
    C["Sàng lọc Title & Abstract<br/>N = 241"]
    D["Đọc full-text<br/>N = 37<br/>(35 Included + 2 Maybe từ V1)"]
    E["Final included<br/>N = 13"]

    A --> B --> C --> D --> E

    classDef stage fill:#e8f1f5,stroke:#256b82,stroke-width:1.5px,color:#102a36
    classDef final fill:#e4f3e8,stroke:#2f855a,stroke-width:1.5px,color:#173b27
    class A,B,C,D stage
    class E final
```

> `Sau dedup (N = 241)` khớp số dòng trong `01_all_records.csv`.

## Chi tiết sàng lọc

### Loại V1: 204 bài

| Mã          | Số lượng | Lý do                                        |
| ----------- | -------: | -------------------------------------------- |
| EC-O        |       96 | Ngoài phạm vi / không phải ngưng thở ban đêm |
| NO ABSTRACT |       69 | Thiếu bản tóm tắt, không đủ dữ liệu          |
| EC-N        |       17 | Bài tổng quan / review / editorial           |
| EC-W        |       11 | Thiết bị đeo / cảm biến dán tiếp xúc da      |
| EC-1        |       10 | Đối tượng trẻ em / sơ sinh                   |
| EC-S        |        1 | Báo cáo ca bệnh đơn lẻ / case study          |
| **Tổng**    |  **204** |                                              |

### Loại V2: 24 bài

| Mã        | Số lượng | Lý do                                        |
| --------- | -------: | -------------------------------------------- |
| No access |       12 | Không truy cập được bài toàn văn             |
| EC-W      |        6 | Dán máy lên người / cảm biến tiếp xúc cơ thể |
| EC-S      |        3 | Tóm tắt kỷ yếu hội nghị ngắn, thiếu thông số |
| EC-O      |        2 | Mục tiêu không khớp bài toán OSA tự nhiên    |
| EC-1      |        1 | Thực nghiệm trên trẻ nhỏ                     |
| **Tổng**  |   **24** |                                              |

> `Final included (N = 13)` khớp số dòng `Include` trong `03_final_included.csv`.
