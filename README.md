# Phân Tích Dữ Liệu Khách Hàng

## Giới thiệu
Dự án này thực hiện phân tích dữ liệu khách hàng của một cửa hàng nhằm cung cấp các thông tin chi tiết hỗ trợ việc tăng doanh số bán hàng và tối ưu hóa chiến lược kinh doanh. Dữ liệu được lấy từ [Kaggle](https://www.kaggle.com/datasets/datascientistanna/customers-dataset) và bao gồm các thông tin như nghề nghiệp, giới tính, thu nhập hàng năm, điểm chi tiêu và quy mô gia đình của khách hàng.

## Mục tiêu phân tích
- **Hiểu rõ hành vi khách hàng:** Phân tích các yếu tố ảnh hưởng đến hành vi mua sắm.
- **Phân khúc khách hàng:** Sử dụng các phương pháp phân tích (ví dụ: clustering) để xác định các nhóm khách hàng có đặc điểm tương đồng.
- **Đề xuất chiến lược tăng doanh số:** Dựa trên kết quả phân tích, đưa ra các khuyến nghị nhằm cải thiện hiệu quả kinh doanh, tập trung vào các nhóm khách hàng có khả năng chi tiêu cao.

## Mô tả dữ liệu
Bộ dữ liệu chứa các trường chính:
- **Profession (Nghề nghiệp):** Loại hình nghề nghiệp của khách hàng.
- **Gender (Giới tính):** Giới tính của khách hàng.
- **Annual Income (Thu nhập hàng năm):** Mức thu nhập của khách hàng.
- **Spending Score (Điểm chi tiêu):** Chỉ số phản ánh mức độ chi tiêu của khách hàng.
- **Family Size (Quy mô gia đình):** Số lượng thành viên trong gia đình khách hàng.

## Quy trình phân tích
1. **Tiền xử lý dữ liệu:**
   - Kiểm tra và xử lý giá trị thiếu.
   - Định dạng lại dữ liệu cho phù hợp.
2. **Phân tích khám phá (EDA):**
   - Tính toán các số liệu thống kê mô tả.
   - Vẽ biểu đồ phân phối và quan hệ giữa các biến (ví dụ: thu nhập và điểm chi tiêu).
3. **Phân khúc khách hàng:**
   - Áp dụng các thuật toán clustering (chẳng hạn như K-Means) để phân nhóm khách hàng.
   - Đánh giá và trực quan hóa kết quả phân khúc.
4. **Phân tích sâu các nhóm khách hàng:**
   - So sánh các đặc điểm của từng nhóm.
   - Đưa ra nhận định về hành vi chi tiêu và mối liên hệ với các yếu tố nhân khẩu học.
5. **Đề xuất chiến lược kinh doanh:**
   - Xác định các nhóm khách hàng có khả năng chi tiêu cao.
   - Đưa ra các gợi ý về chiến dịch marketing và cải tiến dịch vụ dựa trên kết quả phân tích.

## Kết quả chính
- **Phân khúc khách hàng rõ ràng:** Các nhóm khách hàng được phân chia dựa trên các đặc điểm như thu nhập và điểm chi tiêu cho thấy sự khác biệt rõ rệt về hành vi mua sắm.
- **Nhóm khách hàng tiềm năng:** Một số nhóm có điểm chi tiêu cao, cho thấy khả năng đáp ứng tốt các chiến dịch khuyến mãi và quảng cáo.
- **Ảnh hưởng của các yếu tố nhân khẩu học:** Giới tính, nghề nghiệp và quy mô gia đình có tác động đáng kể đến mức độ chi tiêu, từ đó định hướng cho các chiến lược tiếp cận khách hàng cụ thể.

## Hướng dẫn chạy dự án
1. **Cài đặt môi trường:**
   - Cài đặt các thư viện cần thiết:
     ```bash
     pip install -r requirements.txt
     ```
2. **Mở và chạy notebook:**
   - Mở file `customer_analysis.ipynb` bằng Jupyter Notebook hoặc JupyterLab.
   - Chạy các cell theo trình tự để tái tạo quá trình phân tích.
3. **Khám phá kết quả:**
   - Xem các biểu đồ và nhận định được trình bày trong notebook để hiểu sâu hơn về hành vi khách hàng.

## Kết luận và khuyến nghị
- **Chiến lược tiếp cận:** Tập trung vào các nhóm khách hàng có điểm chi tiêu cao để triển khai các chiến dịch marketing cá nhân hóa.
- **Phát triển sản phẩm:** Dựa trên đặc điểm của khách hàng, cải tiến sản phẩm/dịch vụ sao cho phù hợp với nhu cầu của từng nhóm khách hàng.
- **Mở rộng phân tích:** Đề xuất nghiên cứu sâu hơn bằng cách tích hợp thêm các nguồn dữ liệu khác nhằm cải thiện khả năng dự đoán và đưa ra các quyết định chiến lược.

## Tác giả
Dự án được thực hiện bởi một Data Engineer với hơn 10 năm kinh nghiệm trong lĩnh vực phân tích dữ liệu và đưa ra quyết định dựa trên dữ liệu.

---

*Lưu ý:* Nội dung trên là tóm tắt các bước phân tích và kết quả chính dựa trên notebook **customer_analysis.ipynb**. Vui lòng kiểm tra lại chi tiết trong notebook để cập nhật thông tin chính xác và bổ sung các nhận định cụ thể từ quá trình phân tích.
