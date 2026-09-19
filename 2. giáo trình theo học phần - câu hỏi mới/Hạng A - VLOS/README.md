# PHÂN HỆ ĐÀO TẠO UAV HẠNG A - ĐIỀU KHIỂN TRONG TẦM NHÌN TRỰC QUAN (VLOS)
### Khung chương trình đào tạo tiêu chuẩn theo Quyết định số 3906/QĐ-PKKQ

---

## 1. MỤC TIÊU ĐÀO TẠO
Trang bị cho học viên toàn bộ kiến thức pháp luật, khí tượng cơ bản, cấu trúc kỹ thuật máy bay không người lái cỡ nhỏ (dưới 25 kg), nguyên lý khí động học, quy trình vận hành bảo đảm an toàn bay và kỹ năng thao tác điều khiển phản xạ tay trong phạm vi bán kính tầm nhìn quan sát bằng mắt thường ($R \le 500\,\text{m}$, $H \le 120\,\text{m}$).

---

## 2. DANH MỤC HỌC PHẦN & TÀI LIỆU GIÁO TRÌNH

### A. KHỐI HỌC PHẦN LÝ THUYẾT
1. **HP1 - Pháp luật, khí tượng và quản lý vùng trời** (`Lý thuyết/HP1 - Pháp luật, khí tượng và quản lý vùng trời.docx`):
   - *Quy mô*: 905 đoạn văn, 25.482 từ, 187 câu hỏi trắc nghiệm & vấn đáp.
   - *Nội dung*: Luật PKND 2024, Nghị định 288/2025/NĐ-CP, Thông tư 146/2025/TT-BQP, Thông tư 78/2026/TT-BCA (đăng ký định danh phương tiện bay). Vùng cấm/vùng hạn chế bay, quy tắc an toàn khí tượng (gió giật, mây CB, tầm nhìn $\ge 5\,\text{km}$).
2. **HP2 - Kiến thức cơ bản về UAV** (`Lý thuyết/HP2 - Kiến thức cơ bản về UAV.docx`):
   - *Quy mô*: 501 đoạn văn, 10.759 từ, 16 bảng biểu kỹ thuật, 105 câu hỏi sát hạch.
   - *Nội dung*: Khí động học Multirotor/Fixed-wing, cấu tạo khung sườn Carbon, động cơ BLDC, ESC giao tiếp DShot, cấu trúc Flight Controller vi điều khiển STM32 chạy lọc Kalman 1000Hz, cảm biến IMU/La bàn từ, pin LiPo và an toàn sạc/xả.
3. **HP3 - Quy trình vận hành UAV và xử trí bất trắc** (`Lý thuyết/HP3 - Quy trình vận hành UAV và xử trí bất trắc.docx`):
   - *Quy mô*: 586 đoạn văn, 12.533 từ, 121 câu hỏi sát hạch.
   - *Nội dung*: Quy trình vận hành 3 bước (Pre-flight, In-flight, Post-flight), quy trình phối hợp CRM tổ bay, xử lý khẩn nguy mất tín hiệu điều khiển Failsafe RTH, trôi dạt do mất GPS/nhiễu La bàn (Toilet Bowl Effect), sụt áp pin đột ngột và cháy nổ pin trên không.

### B. KHỐI HỌC PHẦN THỰC HÀNH
1. **HP1 - Thực hành bay mô phỏng** (`Thực hành/HP1 - Thực hành bay mô phỏng.docx`):
   - *Quy mô*: 110 đoạn văn, 3.031 từ, 2 bảng tiêu chí đánh giá.
   - *Nội dung*: Thiết lập phần mềm mô phỏng RealFlight/PhoenixRC, điều khiển Mode 2, kỹ năng giữ thăng bằng Hovering, bài tập bay đối đầu Nose-in đón đầu hướng lái và bài tập bay hình số 8 mượt mà.
2. **HP2 - Kỹ năng điều khiển cơ bản trong VLOS** (`Thực hành/HP2 - Kỹ năng điều khiển cơ bản trong VLOS.docx`):
   - *Quy mô*: 95 đoạn văn, 2.307 từ, 2 bảng thông số sân bãi & barem điểm.
   - *Nội dung*: Thiết lập bãi cất hạ cánh mốc H ($arnothing 3\,\text{m}$) và tuyến cọc tiêu $P_1-P_7$. Kiểm tra 360 độ trước khi cất cánh. Bài bay cất cánh, Hovering 4 hướng 5 giây, bay bám tuyến đa giác và hạ cánh chính xác vào tâm điểm.
3. **HP3 - Thực hành nhiệm vụ nâng cao trong VLOS** (`Thực hành/HP3 - Thực hành nhiệm vụ nâng cao trong VLOS.docx`):
   - *Quy mô*: 91 đoạn văn, 2.430 từ, 2 bảng tiêu chuẩn kỹ thuật.
   - *Nội dung*: Phối hợp tổ bay PIC/VO điều lệnh chuẩn xác; bay thủ công hoàn toàn chế độ ATTI (tắt GPS) giữ vị trí; điều khiển Gimbal trinh sát ghi hình mục tiêu và diễn tập xử lý tình huống khẩn nguy trong thời gian dưới 90 giây.
