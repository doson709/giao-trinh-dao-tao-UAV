# PHÂN HỆ ĐÀO TẠO UAV HẠNG B - ĐIỀU KHIỂN NGOÀI TẦM NHÌN TRỰC QUAN (BVLOS)
### Khung chương trình đào tạo nâng cao theo Quyết định số 3906/QĐ-PKKQ

---

## 1. MỤC TIÊU ĐÀO TẠO
Đào tạo phi công UAV chuyên nghiệp đủ năng lực thực hiện các nhiệm vụ bay trinh sát tầm xa, khảo sát địa hình trắc địa, kiểm tra hạ tầng công nghiệp và tìm kiếm cứu hộ ngoài tầm quan sát bằng mắt thường ($> 500\,\text{m}$), quản lý trạm mặt đất GCS, vận hành hệ thống định vị vi sai RTK, hiệp đồng kiểm soát không lưu ATC và bảo dưỡng kỹ thuật định kỳ.

---

## 2. DANH MỤC HỌC PHẦN & TÀI LIỆU GIÁO TRÌNH

### A. KHỐI HỌC PHẦN LÝ THUYẾT
1. **HP1 - Kiến thức UAV trong BVLOS** (`Lý thuyết/HP1 - Kiến thức UAV trong BVLOS.docx`):
   - *Quy mô*: 598 đoạn văn, 12.182 từ, 2 bảng thông số kỹ thuật, tích hợp 50 câu trắc nghiệm M7 (`UAV-C-M7-001` đến `050`).
   - *Nội dung*: Kiến trúc C2 Link 3 tầng (Sóng radio số COFDM, mạng di động 4G/5G bọc VPN, kết nối vệ tinh Satcom); Công nghệ nhận diện và tránh va chạm DAA (ADS-B In/Out, Radar vi sóng AESA, LiDAR 3D, Camera quang học AI nhận diện vật cản tầm xa).
2. **HP2 - Quy trình vận hành UAV trong BVLOS** (`Lý thuyết/HP2 - Quy trình vận hành UAV trong BVLOS.docx`):
   - *Quy mô*: 827 đoạn văn, 13.539 từ, 1 bảng tiêu chuẩn, tích hợp 45 câu trắc nghiệm M6 (`UAV-C-M6-001` đến `045`).
   - *Nội dung*: Phương pháp luận đánh giá an toàn rủi ro hoạt động bay SORA của JARUS (Xác định rủi ro mặt đất GRC, rủi ro trên không ARC, mức độ an toàn và toàn vẹn SAIL I đến VI); Quy trình hiệp đồng không lưu với đài kiểm soát không lưu dân dụng và quân sự (ATC), trực canh vô tuyến tần số khẩn nguy hàng không VHF 121.5 MHz.

### B. KHỐI HỌC PHẦN THỰC HÀNH
1. **HP1 - Kỹ năng điều khiển BVLOS** (`Thực hành/HP1 - Kỹ năng điều khiển BVLOS.docx`):
   - *Quy mô*: 91 đoạn văn, 2.646 từ, 2 bảng quy chuẩn bay.
   - *Nội dung*: Cấu hình trạm mặt đất GCS, tải trước bản đồ địa hình offline map cache độ phân giải cao; Thiết lập trạm Base RTK truyền số hiệu chỉnh NTRIP đạt sai số vị trí dưới 3 cm; Lập kế hoạch bay khảo sát trắc địa tự động phủ ảnh (độ phủ dọc $\ge 80\%$, độ phủ ngang $\ge 75\%$); Thiết lập hàng rào địa lý Geo-caging; Giám sát bảng đồng hồ ảo PFD; Kỹ năng ngắt chế độ tự động gạt Override lái tay khẩn nguy và bài bay đêm thực tế có gắn đèn Strobe chống va chạm đạt chuẩn nhận diện 3 hải lý.
2. **HP2 - Công tác bảo dưỡng UAV** (`Thực hành/HP2 - Công tác bảo dưỡng UAV.docx`):
   - *Quy mô*: 608 đoạn văn, 13.441 từ, 2 bảng tiêu chuẩn kỹ thuật, tích hợp trọn bộ 90 câu trắc nghiệm M5 (`UAV-C-M5-001` đến `090`).
   - *Nội dung*: Quy trình bảo dưỡng cơ khí 360 độ sử dụng tuốc nơ vít cân lực chuyên dụng; Cân bằng động cánh quạt khử rung tần số cao; Hiệu chuẩn cảm biến IMU 6 bậc tự do và La bàn từ trường; Quy trình đo nội trở cell pin LiPo (sàng lọc loại bỏ pack pin có $\Delta IR > 5\,\text{m}\Omega$), xả bảo quản Storage về ngưỡng 3.80V - 3.85V/cell; Đọc và phân tích file log hộp đen đuôi `.bin` trên phần mềm phân tích chuyên sâu để phát hiện dao động rung cơ khí, sụt áp tải đỉnh và nhiễu từ trường.
