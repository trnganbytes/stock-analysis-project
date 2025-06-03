# 📈 Stock Analysis Project

## Mục tiêu dự án

Dự án này nhằm mục đích:

- Thu thập dữ liệu cổ phiếu từ Yahoo Finance qua thư viện `yfinance`.
- Khám phá và phân tích các chỉ số quan trọng như giá mở cửa, giá đóng cửa, khối lượng giao dịch, biến động giá.
- Trực quan hóa dữ liệu để dễ dàng quan sát xu hướng và mẫu hình.
- Học cách xử lý và phân tích dữ liệu thực tế để phát triển kỹ năng Data Analyst.
- (Mở rộng) Tìm hiểu các phương pháp dự báo giá cổ phiếu trong tương lai.

## Công nghệ sử dụng

- Python 3.8+
- Thư viện: `pandas`, `matplotlib`, `seaborn`, `yfinance`, `jupyter`
- Công cụ: Jupyter Notebook, Git và GitHub

## Cấu trúc thư mục

stock-analysis-project/
├── data/ # Chứa dữ liệu cổ phiếu (CSV)
├── notebooks/ # Notebook cho phân tích EDA và trực quan hóa
│ └── stock_eda.ipynb
├── src/ # Script Python để tải và xử lý dữ liệu
│ └── fetch_data.py
├── visualizations/ # Lưu biểu đồ, hình ảnh kết quả (nếu có)
├── requirements.txt # Danh sách thư viện cần cài đặt
├── README.md # Mô tả và hướng dẫn dự án
└── .gitignore # File cấu hình bỏ qua Git

## Hướng dẫn sử dụng

1. **Clone dự án về máy:**
    ```bash
    git clone https://github.com/trnganbytes/stock-analysis-project.git
    cd stock-analysis-project
    ```

2. **Cài đặt thư viện cần thiết:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Tải dữ liệu cổ phiếu ví dụ (AAPL):**
    ```bash
    python src/fetch_data.py
    ```

4. **Chạy phân tích dữ liệu trong Jupyter Notebook:**
    ```bash
    jupyter notebook notebooks/stock_eda.ipynb
    ```

## Các nội dung phân tích chính

- Phân tích biến động giá đóng cửa theo thời gian.
- Tính toán và trực quan hóa các đường trung bình động (MA30, MA90).
- Phân tích khối lượng giao dịch và mối liên hệ với giá cổ phiếu.
- (Mở rộng) Dự báo xu hướng giá cổ phiếu trong tương lai.

## Hướng phát triển tiếp theo

- Áp dụng các mô hình dự báo như ARIMA, Prophet.
- Tạo dashboard trực quan tương tác bằng Streamlit hoặc Tableau.
- So sánh hiệu suất giữa nhiều cổ phiếu khác nhau.
- Tự động hóa việc thu thập và cập nhật dữ liệu hàng ngày.

## Tác giả

Dự án được thực hiện bởi [trnganbytes](https://github.com/trnganbytes) nhằm mục tiêu rèn luyện kỹ năng phân tích dữ liệu thực tế với thị trường chứng khoán.

