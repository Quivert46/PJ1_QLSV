I. PJ1_QLSV - Hệ thống quản lí sinh viên
Hệ thống quản lí sinh viên với cơ sở dữ liệu và phân tích dữ liệu.
II. Mục tiêu dự án 
Xây dựng hệ thống quản lí sinh viên với cơ sở dữ liệu được thiết kế chuẩn hóa nhằm phục vụ lưu trữ và phân tích kết quả học tập của sinh viên.
III. Công nghệ sử dụng
- SQL Server
- SQL Server Management Server (SSMS)
IV. Thiết kế cơ sở dữ liệu
- Hệ thống bao gồm 4 bảng chính
  + sinhvien
  + monhoc
  + dangkihoc
  + diem
được biểu diễn quan hệ theo sơ đồ sau:
sinhvien (1) ---------> (n) dangkihoc (n) <--------- (1) monhoc
                                 |
                                 |
                               diem
Cơ sở dữ liệu được thiết kế chuẩn hóa 3NF (Không dư, Không lặp, Không phụ thuộc lòng vòng) nhằm đảm bảo tính mở rộng và có khả năng mở rộng thêm.
