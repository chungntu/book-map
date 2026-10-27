# Bản đồ Hệ thống Sách Chuyên khảo & Giáo trình (Book Map)

**Cập nhật:** 27/10/2026  
**Chủ biên / Nhóm tác giả chính:** ThS. Trương Thanh Chung, GS.TS. Bùi Tiến Thành, GS.TSKH. Nguyễn Đông Anh  
**Phạm vi hệ thống:** 9 dự án sách đã có bản thảo trên ổ đĩa và 4 chuyên khảo định hướng mở rộng.  
**Bản đồ tương tác Web:** [Mở tệp index.html cục bộ](file:///E:/01%20BOOKS/Thầy%20Thành/00%20book%20map/index.html) · [book-map trực tuyến](https://chungntu.github.io/book-map/)

---

## 1. Tổng quan Kiến trúc Hệ sinh thái Tri thức

Hệ thống sách được quy hoạch thành một **chuỗi tri thức khép kín, tương hỗ chặt chẽ** phục vụ kỹ thuật công trình giao thông và xây dựng hiện đại:

```text
[ NỀN TẢNG KẾT CẤU & PHƯƠNG PHÁP TÍNH (KT) ]
  ├── B01. Động lực học công trình (Dao động & Tải trọng động)
  ├── B02. Phương pháp phần tử hữu hạn (Mô hình hóa số hóa & Digital Twin)
  ├── B03. Tối ưu hóa kết cấu (Hiệu chỉnh mô hình & Tối ưu thiết kế)
  └── B04. Tuyến tính hóa tương đương & Dao động phi tuyến (Phi tuyến, Aeroelastic Flutter)
           │
           ▼
[ ĐO ĐẠC THỰC NGHIỆM & KIỂM TRA KHÔNG PHÁ HỦY (NDT) ]
  ├── B05. Kỹ thuật kiểm tra siêu âm thực hành với Olympus EPOCH 650 (Cơ sở sóng & Quy trình chuẩn)
  └── B06. Kiểm tra siêu âm mối hàn ray đường sắt đô thị (Ứng dụng hiện trường ray 60R2)
           │
           ▼
[ NHẬN DẠNG HỆ THỐNG & GIÁM SÁT SỨC KHỎE KẾT CẤU (SHM) ]
  ├── B07. Nhận dạng hệ kết cấu từ dao động môi trường (OMA, FDD, SSI, CS)
  ├── B08. Giám sát sức khỏe kết cấu (Cảm biến, Xử lý tín hiệu, Học máy & Học sâu)
  └── B09. Giám sát cầu cạn đường sắt cao tốc (Bài toán ngược tích hợp, Mạng cảm biến thưa)
           │
           ▼
[ ĐỊNH HƯỚNG CHUYÊN SÂU MỞ RỘNG (DỰ ĐỊNH) ]
  ├── B10. Thị giác máy tính cho SHM (Computer Vision for SHM)
  ├── B11. Cảm biến ảo cho SHM (Virtual Sensing for SHM)
  ├── B12. Các phương pháp học máy cho SHM (Machine Learning for SHM)
  └── B13. Các phương pháp học sâu cho SHM (Deep Learning for SHM)
```

---

## 2. Bảng Tiến độ Chi tiết 9 Sách Hiện hữu trên Ổ đĩa

| Mã | Nhóm | Tên sách & Phụ đề | Tác giả | Quy mô & Bản thảo | Tình trạng | Đường dẫn manuscript local (PDF) | GitHub |
|:---:|:---:|:---|:---|:---:|:---:|:---|:---:|
| **B01** | **KT** | **Động lực học công trình**<br>*(Lý thuyết và ứng dụng trong kháng chấn, công trình biển, cầu ĐS và SHM)* | ThS. Trương Thanh Chung | 244 trang<br>188 hình vector/PDF | **Bản thảo đầy đủ** | [`KT - ĐỘNG LỰC HỌC KẾT CẤU\manuscript\structural_dynamics.pdf`](file:///E:/01%20BOOKS/Thầy%20Thành/KT%20-%20ĐỘNG%20LỰC%20HỌC%20KẾT%20CẤU/manuscript/structural_dynamics.pdf) | [book-dong-luc-hoc-cong-trinh](https://github.com/chungntu/book-dong-luc-hoc-cong-trinh) |
| **B02** | **KT** | **Phương pháp phần tử hữu hạn**<br>*(Bản sao số cầu đường sắt trên nền phương pháp phần tử hữu hạn)* | ThS. Trương Thanh Chung | 240 trang<br>745 tệp hình/dữ liệu | **Bản thảo đầy đủ** | [`KT - PHƯƠNG PHÁP PHẦN TỬ HỮU HẠN\manuscript\finite_element_method_book.pdf`](file:///E:/01%20BOOKS/Thầy%20Thành/KT%20-%20PHƯƠNG%20PHÁP%20PHẦN%20TỬ%20HỮU%20HẠN/manuscript/finite_element_method_book.pdf) | [finite_element_method_book](https://github.com/chungntu/finite_element_method_book) |
| **B03** | **KT** | **Tối ưu hóa kết cấu**<br>*(Lý thuyết giải tích và thuật toán ứng dụng trong công trình cầu)* | ThS. Trương Thanh Chung | 126 trang<br>70 tệp phụ trợ code/hình | **Bản thảo đầy đủ** | [`KT - TỐI ƯU HÓA KẾT CẤU\manuscript\co_hoc_ket_cau_toi_uu_book.pdf`](file:///E:/01%20BOOKS/Thầy%20Thành/KT%20-%20TỐI%20ƯU%20HÓA%20KẾT%20CẤU/manuscript/co_hoc_ket_cau_toi_uu_book.pdf) | [toi-uu-ket-cau-book](https://github.com/chungntu/toi-uu-ket-cau-book) |
| **B04** | **KT** | **Tuyến tính hóa tương đương và dao động phi tuyến**<br>*(Tuyến tính hóa đối ngẫu, trung bình có trọng số, tự kích Aeroelastic Flutter)* | GS.TSKH. Nguyễn Đông Anh,<br>GS.TS. Bùi Tiến Thành,<br>ThS. Trương Thanh Chung | 129 trang<br>+ Đề tài Flutter 8 trang | **Bản thảo đầy đủ** | [`KT - TUYẾN TÍNH HÓA TƯƠNG ĐƯƠNG VÀ DAO ĐỘNG PHI TUYẾN\manuscript\dual_linearization.pdf`](file:///E:/01%20BOOKS/Thầy%20Thành/KT%20-%20TUYẾN%20TÍNH%20HÓA%20TƯƠNG%20ĐƯƠNG%20VÀ%20DAO%20ĐỘNG%20PHI%20TUYẾN/manuscript/dual_linearization.pdf) | *Local manuscript* |
| **B05** | **NDT** | **Kỹ thuật kiểm tra siêu âm thực hành với Olympus EPOCH 650**<br>*(Cơ sở giải tích, quy trình thực hành và tiêu chuẩn quốc tế EN 12668-1, ISO 9712)* | ThS. Trương Thanh Chung | 112 trang<br>7 chương, 34 hình vector | **Bản thảo đầy đủ<br>(Camera-Ready)** | [`NDT - KIỂM TRA SIÊU ÂM THỰC HÀNH VỚI OLYMPUS EPOCH 650\manuscript\ultrasonic_testing_epoch650.pdf`](file:///E:/01%20BOOKS/Thầy%20Thành/NDT%20-%20KIỂM%20TRA%20SIÊU%20ÂM%20THỰC%20HÀNH%20VỚI%20OLYMPUS%20EPOCH%20650/manuscript/ultrasonic_testing_epoch650.pdf) | *Local manuscript* |
| **B06** | **NDT** | **Kiểm tra siêu âm mối hàn ray đường sắt đô thị**<br>*(Cơ sở khoa học và thực hành hiện trường ray rãnh 60R2)* | ThS. Trương Thanh Chung | 133 trang<br>18 tệp phụ trợ | **Bản thảo đầy đủ** | [`NDT - KIỂM TRA SIÊU ÂM MỐI HÀN RAY\manuscript\ultrasonic_rail_weld_inspection.pdf`](file:///E:/01%20BOOKS/Thầy%20Thành/NDT%20-%20KIỂM%20TRA%20SIÊU%20ÂM%20MỐI%20HÀN%20RAY/manuscript/ultrasonic_rail_weld_inspection.pdf) | [sieu-am-moi-han-ray-60r2](https://github.com/chungntu/sieu-am-moi-han-ray-60r2) |
| **B07** | **SHM** | **Nhận dạng hệ kết cấu từ dao động môi trường**<br>*(Cơ sở OMA, FDD/EFDD/FSDD, SSI dữ liệu/hiệp phương sai và Compressive Sensing)* | ThS. Trương Thanh Chung | 364 trang<br>74 tệp phụ trợ/hình | **Bản thảo đầy đủ<br>(Chuyên sâu)** | [`SHM - NHẬN DẠNG HỆ KẾT CẤU\manuscript\structural_system_identification.pdf`](file:///E:/01%20BOOKS/Thầy%20Thành/SHM%20-%20NHẬN%20DẠNG%20HỆ%20KẾT%20CẤU/manuscript/structural_system_identification.pdf) | [structural-system-identification-book](https://github.com/chungntu/structural-system-identification-book) |
| **B08** | **SHM** | **Giám sát sức khỏe kết cấu (SHM)**<br>*(Cảm biến, xử lý tín hiệu, OMA, học máy và học sâu cho công trình cầu)* | ThS. Trương Thanh Chung | 174 trang<br>294 tệp phụ trợ | **Bản thảo đầy đủ** | [`SHM - GIÁM SÁT SỨC KHỎE KẾT CẤU\manuscript\shm_book.pdf`](file:///E:/01%20BOOKS/Thầy%20Thành/SHM%20-%20GIÁM%20SÁT%20SỨC%20KHỎE%20KẾT%20CẤU/manuscript/shm_book.pdf) | [shm-book](https://github.com/chungntu/shm-book) |
| **B09** | **SHM** | **Giám sát cầu cạn đường sắt cao tốc**<br>*(Bài toán ngược, cập nhật mô hình, tối ưu hóa và học máy với dữ liệu cầu KW51)* | ThS. Trương Thanh Chung | 90 trang<br>31 tệp phụ trợ | **Đang tái cấu trúc** | [`SHM - GIÁM SÁT CẦU CẠN ĐƯỜNG SẮT CAO TỐC\manuscript\high_speed_rail_viaduct_shm.pdf`](file:///E:/01%20BOOKS/Thầy%20Thành/SHM%20-%20GIÁM%20SÁT%20CẦU%20CẠN%20ĐƯỜNG%20SẮT%20CAO%20TỐC/manuscript/high_speed_rail_viaduct_shm.pdf) | [book-shm-cau-duong-sat-cao-toc](https://github.com/chungntu/book-shm-cau-duong-sat-cao-toc) |

---

## 3. Danh mục Chuyên khảo Định hướng Mở rộng (Dự kiến triển khai)

| Mã | Nhóm | Chuyên khảo định hướng | Trọng tâm học thuật & Định vị | Tình trạng |
|:---:|:---:|:---|:---|:---:|
| **B10** | **SHM** | **Computer Vision for SHM**<br>*(Thị giác máy tính trong giám sát công trình)* | Phát hiện vết nứt, bóc tách bê tông, ăn mòn từ ảnh/video UAV; học sâu phân đoạn ngữ nghĩa và tái tạo mô hình 3D hư hỏng. *(Hiện đã có repo mã nguồn và trọng số mô hình).* | Dự định (Có code & data) |
| **B11** | **SHM** | **Virtual Sensing for SHM**<br>*(Cảm biến ảo trong giám sát công trình)* | Tái tạo chuyển vị, biến dạng tại các vị trí không đo từ mạng cảm biến thưa kết hợp mô hình phần tử hữu hạn (Kalman Filter, Physics-informed ML). | Dự định |
| **B12** | **SHM** | **Machine Learning Methods for SHM**<br>*(Học máy ứng dụng trong chẩn đoán kết cấu)* | Trích xuất đặc trưng từ dữ liệu rung động, phát hiện bất thường (Unsupervised Anomaly Detection), phân loại dạng hư hỏng và đánh giá độ tin cậy. | Dự định |
| **B13** | **SHM** | **Deep Learning Methods for SHM**<br>*(Học sâu ứng dụng trong chẩn đoán kết cấu)* | Mạng CNN 1D/2D, Transformer thời gian, Autoencoders, xử lý dữ liệu lớn dài hạn và bài toán khan hiếm mẫu hư hỏng (Domain Adaptation). | Dự định |

---

## 4. Lộ trình Ưu tiên Thực hiện Tiếp theo

1. **Nhóm hoàn thiện biên tập & đồng bộ ký hiệu (B01, B02, B03, B05, B06):**
   - Rà soát tính nhất quán của hệ ký hiệu toán học giữa các sách Kết cấu và NDT.
   - Kiểm tra chất lượng hình vẽ vector TikZ và độ phân giải hình ảnh, kiểm chứng cross-references trong LaTeX.
   - Sách **B05 (Olympus EPOCH 650)** đã hoàn thiện biên dịch 0 lỗi, sẵn sàng đóng gói xuất bản.

2. **Nhóm nâng cấp chuyên môn cùng Giáo sư (B04):**
   - Đang phối hợp cùng GS.TSKH. Nguyễn Đông Anh nâng cấp Chương 8: tích hợp phương pháp Tuyến tính hóa tương đương đối ngẫu (DEL) có trọng số vào hiện tượng Rung khí đàn hồi (Aeroelastic Flutter) cho mặt cầu nhịp lớn (thay thế mô hình Van der Pol kinh điển).

3. **Nhóm nâng cấp chuyên sâu & tái cấu trúc (B07, B09):**
   - **B07 (Nhận dạng hệ kết cấu):** Khớp nối các case study thực nghiệm đo đạc hiện trường thực tế tại Việt Nam.
   - **B09 (Cầu cạn ĐSCT):** Hoàn thiện ví dụ xuyên suốt về mô hình cầu cạn đường sắt tốc độ cao chịu tải đoàn tàu HSLM.
