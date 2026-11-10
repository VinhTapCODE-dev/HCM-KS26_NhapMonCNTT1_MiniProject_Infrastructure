# Hệ Thống Quản Lý Hạ Tầng GreenTech

Hệ thống tự động hóa quản lý hạ tầng máy chủ và đối soát tài nguyên thiết bị cho Startup GreenTech.

## 🚀 Hướng Dẫn Chạy Script Lọc Log

Để chạy script tự động lọc các dòng nhật ký nguy hiểm (`CRITICAL` và `ERROR`) từ file log và xuất báo cáo vào thư mục `backup/`, mở CMD tại thư mục `scripts/` và thực thi:

```cmd
cd scripts
auto_report.bat
```

## 📋 Checklist Kiểm Tra Thiết Bị

- [x] Kiểm tra cấu trúc cây thư mục 3 cấp chuẩn `kebab-case`.
- [x] Đã cấu hình tệp ẩn `.env` chứa thông tin kết nối bảo mật.
- [x] Chạy script `auto_report.bat` không phát sinh lỗi tràn RAM.
- [x] Kiểm tra tệp báo cáo `backup/bao-cao-su-co.txt`.
- [x] Thực hiện đối soát dữ liệu thiết bị với hàm `VLOOKUP` và `TRIM` trong Excel.

## 📊 Bảng Thông Số Phần Cứng Mẫu

| Mã Trạm | Mã Linh Kiện | Tên Thiết Bị | Dung Lượng RAM | Loại Storage | Đơn Giá (VND) |
| :--- | :--- | :--- | :--- | :--- | :--- |
| TRAM-001 | LK-CPU-01 | AMD Ryzen 5 5600X | 16GB | SSD | 3,500,000 |
| TRAM-002 | LK-RAM-02 | Kingston Fury 16GB DDR4 | 32GB | SSD | 1,200,000 |
| TRAM-003 | LK-SSD-01 | Samsung 970 EVO Plus 512GB | 8GB | SSD | 1,600,000 |
| TRAM-004 | LK-HDD-01 | Seagate Barracuda 2TB | 16GB | HDD | 1,100,000 |
