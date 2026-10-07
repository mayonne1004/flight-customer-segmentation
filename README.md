# Phân tích phân khúc khách hàng hàng không

Trong bối cảnh cạnh tranh gay gắt của ngành hàng không, việc thấu hiểu hành vi khách hàng là yếu tố sống còn. Thay vì tiếp thị đại trà gây lãng phí, dự án này tập trung khai thác khối dữ liệu bay khổng lồ để phân tích và phân khúc khách hàng ứng dụng thuật toán K-Means và Decision Tree.

## 📂 Cấu trúc Repository
* **`Code/`**: Chứa file Jupyter Notebook (`.ipynb`) minh họa toàn bộ quá trình xử lý dữ liệu, phân tích khám phá (EDA) và huấn luyện mô hình.
* **`Data/`**: Chứa tập dữ liệu thô về hoạt động bay và lịch sử thẻ thành viên.
* **`Docs/`**: File báo cáo phân tích chi tiết.

## 🛠 Công cụ & Công nghệ
* **Ngôn ngữ:** Python (sử dụng thư viện Pandas, NumPy, Scikit-learn).
* **Mô hình thuật toán:** K-Means Clustering (phân nhóm khách hàng) và Decision Tree (trích xuất luật ra quyết định).
* **Trực quan hóa:** Matplotlib/Seaborn (và Tableau nếu có sử dụng để xây dựng dashboard báo cáo).

## 🎯 Quy trình phân tích
1. **Tiền xử lý dữ liệu:** Làm sạch các giá trị thiếu, xử lý dữ liệu ngoại lai trong các cột chi phí, khoảng cách bay.
2. **EDA (Exploratory Data Analysis):** Tìm hiểu phân phối và mối tương quan giữa hành vi đặt vé và hạng thẻ khách hàng.
3. **Phân cụm với K-Means:** Chia tệp khách hàng thành các nhóm có đặc điểm tương đồng.
4. **Phân loại với Decision Tree:** Tìm ra các nhân tố quan trọng nhất quyết định một khách hàng thuộc phân khúc nào.

## 💡 Kết quả & Đề xuất chiến lược
*(Ghi chú ngắn gọn 2-3 điểm sáng giá nhất mà nhóm bạn tìm ra từ dữ liệu để thể hiện tư duy kinh doanh)*
* **Nhóm khách hàng giá trị cao (Ví dụ):** Đặc điểm nhận diện là gì? Đề xuất chiến dịch chăm sóc khách hàng VIP để giữ chân.
* **Nhóm khách hàng có nguy cơ rời bỏ (Ví dụ):** Đặc điểm nhận diện là gì? Đề xuất các gói khuyến mãi nhắm mục tiêu để kích cầu.

## 🚀 Hướng dẫn chạy dự án
1. Clone repository về máy tính: `git clone https://github.com/mayonne1004/flight-customer-segmentation.git`
2. Cài đặt các thư viện Python cần thiết.
3. Mở file code trong thư mục `Code/` bằng Jupyter Notebook hoặc VS Code và chạy tuần tự các cell.
