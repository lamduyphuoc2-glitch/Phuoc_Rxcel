# Excel Reader App

Ứng dụng Streamlit đơn giản giúp đọc, khám phá và xuất dữ liệu từ các tệp Excel.

## Tính năng chính
- Upload tệp Excel (`.xlsx`, `.xls`) và tự động đọc tất cả các sheet.
- Hiển thị số dòng/cột, thống kê mô tả và thông tin chi tiết từng cột.
- Tìm kiếm theo từ khóa trên toàn bộ bảng dữ liệu.
- Xuất sheet đang xem sang định dạng CSV hoặc Excel.

## Yêu cầu hệ thống
- Python 3.9+ (khuyến nghị 3.11).
- Các thư viện trong `requirements.txt`.

## Cách cài đặt
```bash
python -m venv .venv
.venv\Scripts\activate  # Trên Windows
pip install -r requirements.txt
```

## Chạy ứng dụng
```bash
streamlit run app.py
```

## Demo dữ liệu
Tệp `demo_data.xlsx` cung cấp dữ liệu mẫu để bạn thử nghiệm nhanh ứng dụng.

## Ghi chú
- Khi upload tệp lớn, hãy bật tùy chọn chỉ xem 100 dòng đầu để tối ưu hiệu năng.
- Nút 🔄 trong phần tùy chọn hiển thị sẽ tải lại toàn bộ dữ liệu từ file gốc.


