# HƯỚNG DẪN CẤU TRÚC VÀ BẢN ĐỒ DỰ ÁN ĐÀO TẠO UAV
*Quy hoạch chuẩn hóa theo khung chương trình của Quân chủng PK-KQ*

Tài liệu này giải thích cấu trúc nhánh chính của dự án, vai trò và trách nhiệm của từng thư mục thành phần để người dùng dễ dàng quản trị, giảng dạy và sát hạch.

---

## 1. Sơ Đồ Cấu Trúc Nhánh Chính (Workspace Tree)

Dự án được phân cấp rõ ràng theo các nhóm chức năng lý thuyết, thực hành, sát hạch và cơ sở pháp lý:

```
workspace/
├── README.md                                                # Tài liệu này (Bản đồ cấu trúc dự án)
├── Giáo Trình Đào Tạo UAV (rút gọn v7) 2026.07.30.docx      # Giáo trình tổng hợp 14 chương gốc
├── Phân bổ nội dung giảng dạy 2026.07.31.docx              # Phân bổ tiết học & đối chiếu với giáo trình
├── Bảng phân chia câu hỏi theo học phần 2026.07.31.docx    # Bảng ánh xạ đề thi trắc nghiệm/vấn đáp
├── Danh mục đề xuất đầu tư CSVC đào tạo UAV 2026.08.01.xlsx # Dự toán đầu tư trang thiết bị
│
├── văn bản pháp quy/                                        # [Chi tiết tại thư mục này/README.md]
│   └── (Thông tư, quyết định chương trình khung đào tạo của Bộ Quốc phòng & PK-KQ)
│
├── quy chuẩn kỹ thuật/                                      # [Chi tiết tại thư mục này/README.md]
│   └── (Quy chuẩn kỹ thuật phát tần số vô tuyến điện, tương thích điện từ cho drone của BTTTT)
│
├── đào tạo sát hạch/                                       # [Chi tiết tại thư mục này/README.md]
│   └── (Bản quy chuẩn sân thi thực hành, bộ ngân hàng 600 câu trắc nghiệm & 49 câu vấn đáp)
│
└── giáo trình theo học phần/                                # [Chi tiết tại thư mục này/README.md]
    ├── Hạng A - VLOS/                                       # Giáo trình Hạng A (Trong tầm nhìn trực quan - 6 Tín chỉ)
    │   ├── Lý thuyết/ (HP1, HP2, HP3 lý thuyết)
    │   └── Thực hành/ (HP1, HP2, HP3 hướng dẫn thực hành bay mới biên soạn)
    └── Hạng B - BVLOS/                                      # Giáo trình Hạng B (Ngoài tầm nhìn trực quan - 7 Tín chỉ)
        ├── Lý thuyết/ (HP1, HP2 lý thuyết)
        └── Thực hành/ (HP1, HP2 hướng dẫn thực hành bay & bảo dưỡng mới biên soạn)
```

---

## 2. Vai Trò & Hướng Dẫn Truy Cập Nhanh

Mỗi thư mục trong dự án đảm nhận một vai trò chuyên biệt và đều có hướng dẫn chi tiết đính kèm:

1.  **Cơ sở pháp lý tối cao:** Xem tại [văn bản pháp quy/README.md](văn bản pháp quy/README.md) để nắm được căn cứ pháp luật của toàn bộ khóa học.
2.  **Thông số kỹ thuật & Tần số:** Xem tại [quy chuẩn kỹ thuật/README.md](quy chuẩn kỹ thuật/README.md) để tuân thủ quy định truyền thông vô tuyến cho thiết bị điều khiển và truyền hình ảnh.
3.  **Hệ thống thi & Sát hạch:** Xem tại [đào tạo sát hạch/README.md](đào tạo sát hạch/README.md) để hiểu quy chế chấm điểm trừ sa hình và ngân hàng đề thi.
4.  **Tài liệu biên soạn giảng dạy:** Xem tại [giáo trình theo học phần/README.md](giáo trình theo học phần/README.md) để bắt đầu công tác giảng dạy lý thuyết và thực hành bay.
