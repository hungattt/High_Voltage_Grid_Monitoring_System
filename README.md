# Hệ Thống Giám Sát Lưới Điện Cao Thế

## Giới Thiệu
Hệ thống giám sát lưới điện cao thế với chức năng giám sát và quản lý dữ liệu điện sau giám sát.

Hệ thống bao gồm 7 tab chính:
- Đợt Bay
- Quản Lý Đợt Bay
- Quản Lý SCADA
- Quản Lý Sửa Chữa
- Thống Kê
- Hành Lang Tuyến
- Camera

## Chức Năng Chi Tiết

### 1. Tab Đợt Bay
- **Chức năng:** Phát hiện các bất thường trên đường dây truyền tải điện cao thế.
- **Đầu vào:** Video, ảnh.

#### 1.1 Phát hiện các bất thường ảnh quang
![](images/1_Tao_dot_bay_kiem_tra_import_video_quang.png)
![](images/2_Trong_qua_trinh_kiem_tra_import_video_quang.png)
#### 1.2 Phát hiện các bất thường ảnh quang trong trường hợp đặc biệt, không có dữ liệu training
![](images/dot-bay3.png)
![](images/dot-bay6.png)
![](images/dot-bay7.png)
![](images/nang-cao2.png)
#### 1.3 Phát hiện các bất thường ảnh nhiệt
![](images/7_Tao_dot_bay_kiem_tra_import_video_nhiet1.png)
![](images/8_Trong_qua_trinh_kiem_tra_import_video_nhiet.png)
### 2. Tab Quản Lý Đợt Bay
- **Chức năng:** Quản lý kết quả các đợt bay sau khi cho video, ảnh chụp từ drone về đường dây truyền tải điện cần giám sát vào module AI để phân tích các bất thường.
- Kết quả là các ảnh bình thường hoặc bất thường của từng cột.
- Sau khi xem lại kết quả, người dùng có thể xuất báo cáo tự động theo chuẩn công ty Lưới Điện Cao Thế TP Hà Nội.

#### 2.1 Xem kết quả của đợt bay với ảnh quang
![](images/1_Tat_ca_anh_cua_nhiem_vu_duoc_chon.png)
#### 2.2 Xem kết quả của đợt bay với ảnh nhiệt
![](images/5_Loc_chi_anh_bat_thuong_nhiet.png)
#### 2.3 Xuất báo cáo
![](images/6_Xuat_bao_cao.png)
![](images/7_Zoom_anh_bat_thuong_trong_phan_xuat_bao_cao.png)
![](images/8_Chinh_sua_noi_dung_bao_cao.png)
![](images/9_Chinh_sua_danh_sach_nhan_vien_kiem_tra.png)
### 3. Tab Quản Lý SCADA
- **Chức năng:** Phân tích dữ liệu time series từ SCADA tại các trạm biến áp gửi về.
- Giúp đưa ra các cảnh báo sớm nếu có bất thường về dòng điện tại các trạm biến áp.

### 4. Tab Quản Lý Sửa Chữa
- **Chức năng:** Quản lý và xem chi tiết trong một tuyến chỉ định, bao nhiêu bất thường chưa xử lý và đã xử lý.
- Nếu chưa xử lý, người dùng cần cập nhật ảnh bất thường sau xử lý để chuyển trạng thái thành đã xử lý.

#### 4.1 Bất thường chưa xử lý
![](images/sua-chua.png)
#### 4.2 Xem chi tiết bất thường chưa xử lý
![](images/sua-chua2.png)
#### 4.3 Cập nhật ảnh bất thường sau xử lý
![](images/sua-chua3.png)
#### 4.4 Bất thường đã xử lý
![](images/sua-chua4.png)
#### 4.5 Xem chi tiết bất thường đã xử lý
![](images/sua-chua5.png)
### 5. Tab Thống Kê
- **Chức năng:** Quản lý và thống kê các bất thường theo ngày và theo tuyến.
- Phần biểu đồ giúp người dùng nắm bắt nhanh số lượng bất thường chưa xử lý và đã xử lý.
- Phần bảng cung cấp thông tin chi tiết từng bất thường.
![](images/2_hover_vao_tung_block_defect_da_xu_ly_trong_chart.png)
![](images/3_hover_vao_tung_block_defect_chua_xu_ly_trong_chart.png)
### 6. Tab Hành Lang Tuyến
- **Chức năng:** Xem hành lang tuyến dưới dạng 3D cloud point.
- Giúp người dùng dễ dàng kiểm tra có vi phạm hành lang tuyến hay không, như kiểm tra chiều cao của cây dưới đường dây điện hoặc khoảng cách công trình xây dựng tới đường dây.
![](images/1_Ban_do_3D_hanh_lang_tuyen.png)
![](images/2_Xem_1_luot_ban_do_hanh_lang_tuyen.png)
### 7. Tab Camera
- **Chức năng:** Phát hiện các bất thường trên đường dây truyền tải điện cao thế tại các điểm nóng được gán camera theo dõi.
- **Đầu vào:** Luồng video RTSP.
![](images/2_Xem_camera_o_dia_diem_duoc_chon.png)

