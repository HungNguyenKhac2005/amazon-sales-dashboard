# 🛒 Amazon Sales Performance Dashboard

Dự án thiết kế và phát triển báo cáo quản trị hiệu suất kinh doanh bán hàng chuyên sâu trên sàn thương mại điện tử **Amazon** bằng công cụ **Power BI**. Báo cáo cung cấp góc nhìn toàn diện và các phân tích sâu sắc về doanh thu, chi phí, lợi nhuận, tỷ lệ trả hàng và hiệu quả vận hành theo thời gian.

---

## ✒️ Giới thiệu về tác giả

- **Tên:** Nguyễn Khắc Hưng
- **Vị trí:** BI Developer
- **Học vấn:** Đang theo học chương trình kỹ sư ngành Khoa học Dữ liệu, chuyên ngành Phân tích Dữ liệu trong Kinh tế và Tài chính, thuộc Khoa Công nghệ Thông tin, Đại học Mỏ - Địa chất.

---

## 📊 Tổng quan chỉ số KPI cốt lõi (Sales & Profit Performance)

Báo cáo tích hợp các thẻ KPI thông minh hiển thị số liệu thực tế kèm tỷ lệ tăng trưởng so với tháng trước (MoM Growth) để nhanh chóng đánh giá sức khỏe kinh doanh:

*   **Tổng doanh số (Total Sales):** `117M` (chính xác là `117,357,932`), giảm `-16.67%` so với tháng trước.
*   **Tổng số đơn hàng (Total Orders):** `100` đơn hàng, giảm `-9.09%` so với tháng trước.
*   **Tổng lợi nhuận (Total Profit):** `23.47M`, giảm `-23.08%` so với tháng trước.
*   **Tỷ lệ trả hàng (Return Rate):** `17.00%`, tăng mạnh `42.86%` so với tháng trước (chỉ số cảnh báo cần tối ưu hóa chất lượng sản phẩm/dịch vụ).
*   **Tổng chi phí (Total Cost):** `93.89M`, tăng đột biến `400.00%` so với tháng trước.

---

## 🔍 Các thành phần trực quan hóa & Phân tích chuyên sâu (Insights)

### 1. Phân tích Xu hướng theo Tháng (Monthly Sales & Profit Analysis)
*   **Biểu đồ cột:** Trực quan hóa Doanh thu (**Total Sales**) và Lợi nhuận (**Total Profit**) so sánh trực tiếp giữa Tháng 5 và Tháng 6.
*   Giúp phát hiện nhanh xu hướng tăng trưởng doanh thu vượt bậc vào Tháng 6 nhưng biên lợi nhuận thực tế bị thu hẹp do chi phí vận hành tăng cao.

### 2. Biến động Doanh thu, Chi phí & Lợi nhuận Hàng ngày (Daily Financial Trends)
*   Sử dụng biểu đồ đường liên tục (**Total Sales, Total cost and Total profit by Day**) theo chu kỳ 30 ngày.
*   Giúp doanh nghiệp theo dõi sát sao sự tương quan của 3 chỉ số tài chính cốt lõi theo thời gian thực và phát hiện kịp thời các ngày có chi phí phát sinh đột biến.

### 3. Phân tích Hàng trả lại (Returns & Return Rate)
*   Biểu đồ thanh ngang (**total returned and Count of Returned by Month**) so sánh số lượng đơn hàng bị trả lại giữa Tháng 5 và Tháng 6.
*   Đo lường trực tiếp tỷ lệ trả hàng giúp bộ phận Supply Chain kiểm soát chất lượng đóng gói và dịch vụ giao nhận của Amazon.

### 4. Bảng Tổng hợp Hiệu suất Chi tiết (Monthly Order Profit Performance Overview)
*   Bảng ma trận (Matrix Visual) hỗ trợ phân cấp thời gian từ **Năm > Quý > Tháng > Ngày** hiển thị các chỉ số chi tiết: số lượng đơn hàng, doanh số, tỷ lệ trả hàng, chi phí và tỷ lệ tăng trưởng tương ứng.
*   Cho phép người dùng thực hiện thao tác **Drill-down (Khoan sâu dữ liệu)** để kiểm tra số liệu chi tiết của từng ngày giao dịch cụ thể.

---

## 🛠️ Tính năng UI/UX nổi bật

*   **Thanh điều hướng Tab chuyên nghiệp (Sidebar Navigation):** Thiết kế nút bấm tương tác mượt mà giúp chuyển đổi nhanh chóng giữa các trang báo cáo chuyên biệt:
    *   `Overview` (Tổng quan tài chính)
    *   `Product` (Phân tích sản phẩm)
    *   `Region` (Phân tích khu vực bán hàng)
    *   `Supply Chain` (Phân tích chuỗi cung ứng)
    *   `Home` (Trang chủ báo cáo)
    *   `Forecasting` (Tính năng dự báo doanh số tương lai bằng AI)
*   **Bộ lọc động thông minh (Interactive Slicers):** Bộ lọc được thiết kế ẩn/hiện tinh tế ở thanh bên trái bao gồm: lọc theo Vùng miền (**Region**), Phương thức giao nhận (**Delivery Method**) và Tên khách hàng (**Customer Name**).

---

## 🚀 Hướng dẫn mở dự án

1.  Cài đặt ứng dụng **Microsoft Power BI Desktop** phiên bản mới nhất.
2.  Clone repository này về máy cá nhân:
    ```bash
    git clone https://github.com/HungNguyenKhac2005/Power-BI-Dashboard-Projects.git
    ```
3.  Mở file [Amazon_Sales_Dashboard.pbix](file:///C:/BI%20tool/Power%20BI/C%C3%A1c%20DashBoard%20%C4%91%C3%A3%20ho%C3%A0n%20thi%E1%BB%87n/Amazon_Sales_Dashboard.pbix).
4.  Tương tác động bằng cách sử dụng các bộ lọc ở thanh điều hướng bên trái và click chọn các nút để di chuyển giữa các trang chuyên biệt.
