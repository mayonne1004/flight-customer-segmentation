# Phân tích phân khúc khách hàng hàng không ứng dụng K-Means & Decision Tree

Dự án này thuộc về nhóm sinh viên Trường Đại học Kinh tế - Đại học Đà Nẵng. Mục tiêu của dự án là khai phá dữ liệu khách hàng hàng không, ứng dụng học máy để gom cụm và phân lớp nhằm thấu hiểu hành vi, dự đoán xu hướng và đề xuất chiến lược Marketing cá nhân hóa.

## Author
* Thiều Anh Thư
* Nguyễn Văn Thái Bảo
* Bùi Thành Anh
* Nguyễn Đức Khánh Toàn

**Giảng viên hướng dẫn:** Lê Diên Tuấn

## Cấu trúc Repository
* **`Code/`**: Chứa file Jupyter Notebook minh họa quá trình xử lý dữ liệu, phân tích khám phá và huấn luyện mô hình.
* **`Data/`**: Chứa tập dữ liệu thô về hoạt động bay và lịch sử thẻ thành viên.
* **`Docs/`**: File báo cáo phân tích chi tiết.

## Công nghệ & Thuật toán
* **Ngôn ngữ:** Python
* **Thuật toán:** K-Means Clustering, Fuzzy C-Means, Decision Tree, PCA
* **Kiểm định thống kê:** Shapiro-Wilk, Kruskal-Wallis, Mann-Whitney U

## Kết quả chính
* **Cụm 0 (Khách VIP):** Chiếm 65.3% số lượng khách hàng nhưng đóng góp tới 86.89% tổng điểm tích lũy của toàn hệ thống. Tần suất bay rất cao và tỷ lệ hủy thẻ cực thấp.
* **Cụm 1 (Khách Ngủ đông):** Chiếm 14.1% số lượng, chỉ đóng góp 2.06% giá trị. Tỷ lệ hủy thẻ lên tới 75% và thời gian không bay kéo dài.
* **Cụm 2 (Khách Tiềm năng):** Chiếm 20.6% số lượng, là khách hàng mới gia nhập nhưng hoạt động sôi nổi và có dư địa phát triển lớn.
* **Mô hình dự đoán:** Cây quyết định phân loại tự động khách hàng mới đạt độ chính xác (Accuracy) 98%.

