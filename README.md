# Phân nhóm các trường Trung học phổ thông (THPT)

## 📌 Tổng quan dự án
Dự án phân khúc trường học dựa trên đặc điểm tương đồng nhằm tối ưu hóa chiến lược tuyển sinh, hỗ trợ hoạch định chính sách giáo dục và cung cấp thông tin tư vấn chọn trường cho học sinh.

## 🛠 Tech Stack
* **Ngôn ngữ:** Python
* **Thư viện:** Pandas, Seaborn, Scikit-learn, Streamlit
* **Thuật toán cốt lõi:** K-Means Clustering

## 🚀 Quy trình thực hiện
1. **Tiền xử lý dữ liệu:** Làm sạch, xử lý missing values và outliers bằng Box plots cho tập dữ liệu thô của 341 trường.
2. **Chuẩn hóa biến số:** Xử lý các biến số học trọng tâm bao gồm Tỷ lệ chọi, Điểm chuẩn, Học phí, Diện tích, Số tuyến và Khoảng cách trạm xe buýt.
3. **Mô hình hóa:** Ứng dụng K-Means Clustering để phân cụm đặc điểm trường học.
4. **Triển khai ứng dụng (Deployment):** Thiết kế Web App bằng Streamlit cho phép người dùng nhập dữ liệu đầu vào, chuẩn hóa tức thì và trích xuất danh sách trường đề xuất phù hợp nhất.
