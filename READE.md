# Đồ Án: Phát Hiện Ung Thư Vú

## Mục Tiêu
Xây dựng mô hình học máy để phát hiện ung thư vú dựa trên các đặc trưng được trích xuất từ dữ liệu y tế, hỗ trợ chẩn đoán sớm và nâng cao hiệu quả điều trị.

## Mô Tả Dữ Liệu
- **Nguồn dữ liệu:** data/data.csv
- **Đặc trưng:** Các thông số liên quan đến tế bào vú (ví dụ: radius, texture, perimeter, area, smoothness, ...)
- **Nhãn:** 0 (Lành tính), 1 (Ác tính)

## Các Bước Thực Hiện
1. **Tiền xử lý dữ liệu:** Làm sạch, chuẩn hóa dữ liệu, xử lý giá trị thiếu.
2. **Trích xuất đặc trưng:** Lựa chọn các đặc trưng quan trọng.
3. **Huấn luyện mô hình:** Sử dụng các thuật toán học máy (Logistic Regression, SVM, Random Forest, ...).
4. **Đánh giá mô hình:** Sử dụng các chỉ số như Accuracy, Precision, Recall, F1-score.
5. **Triển khai mô hình:** Lưu mô hình đã huấn luyện và xây dựng giao diện dự đoán.

## Công Nghệ Sử Dụng
- Python (pandas, numpy, scikit-learn, matplotlib, joblib)
- Jupyter Notebook
- Flask (nếu có giao diện web)

## Hướng Dẫn Chạy Project
1. Cài đặt các thư viện cần thiết:
   ```bash
   pip install -r requirements.txt
   ```
2. Huấn luyện mô hình (nếu cần):
   - Mở file `model/Train_Breast_Cancer_Detection.ipynb` và chạy các cell.
3. Chạy ứng dụng dự đoán:
   - Chạy file `app/main.py`:
     ```bash
     python app/main.py
     ```


## Tác Giả
- Nguyễn Mạnh Tuấn
## Cộng sự
- Phạm Tuấn Anh
- Nguyễn Minh Thái