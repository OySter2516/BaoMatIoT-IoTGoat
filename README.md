# ĐỀ TÀI 30: LỖ HỔNG FIRMWARE THIẾT BỊ IoT QUA OWASP IoTGoat

---

## 1. Mô tả đề tài

Đề tài tập trung nghiên cứu và triển khai môi trường firmware OWASP IoTGoat nhằm phục vụ việc học tập và đánh giá các lỗ hổng bảo mật trên thiết bị Internet of Things (IoT). OWASP IoTGoat là một firmware được xây dựng có chủ đích chứa các điểm yếu bảo mật, giúp người học thực hành phân tích và đánh giá an toàn thông tin trong môi trường giả lập.

Trong quá trình thực hiện, nhóm tiến hành triển khai firmware trên nền tảng Docker kết hợp QEMU, khảo sát cấu trúc hệ thống, thu thập các tệp cấu hình, phân tích dịch vụ đang hoạt động và đánh giá một số lỗ hổng phổ biến theo phương pháp **OWASP Firmware Security Testing Methodology (FSTM)**.

Các nội dung chính của đề tài gồm:

- Triển khai môi trường OWASP IoTGoat.
- Thu thập thông tin firmware và hệ thống.
- Phân tích cấu hình mạng, Web Server và các dịch vụ.
- Đánh giá các lỗ hổng bảo mật phổ biến.
- Đề xuất các biện pháp giảm thiểu rủi ro.

---

## 2. Thành viên thực hiện

- Họ và tên: Châu Nhật Hào
- MSSV: 231A010504
- Học phần: Bảo Mật trong IoT
- Lớp học phần: 253INT441001
- Giảng viên hướng dẫn: Hồ Nhựt minh

---

## 3. Tài liệu tham khảo

1. OWASP IoTGoat  
   https://github.com/OWASP/IoTGoat

2. OWASP Firmware Security Testing Methodology (FSTM)  
   https://github.com/scriptingxss/owasp-fstm

3. OWASP IoT Security Testing Guide (ISTG)  
   https://github.com/OWASP/owasp-istg

4. OpenWrt Documentation  
   https://openwrt.org/

5. Docker Documentation  
   https://docs.docker.com/

6. QEMU Documentation  
   https://www.qemu.org/docs/

---

## 4. Nội dung Repository

```text
report/        : Báo cáo tiểu luận
slides/        : Slide trình bày
src/           : Thông tin về mã nguồn sử dụng
configs/       : Các tệp cấu hình thu thập từ firmware
data/          : Dữ liệu thu thập trong quá trình phân tích
results/       : Hình ảnh, log và kết quả triển khai
references/    : Tài liệu tham khảo
```

---

## 5. Giới hạn an toàn và phạm vi thực hiện

Đề tài được triển khai hoàn toàn trong môi trường giả lập OWASP IoTGoat nhằm mục đích học tập và nghiên cứu.

Phạm vi thực hiện bao gồm:

- Triển khai firmware trên Docker và QEMU.
- Thu thập thông tin firmware và cấu hình hệ thống.
- Đánh giá các lỗ hổng bảo mật dựa trên môi trường thực nghiệm.
- Không khai thác hoặc tấn công bất kỳ hệ thống thực tế nào.
- Không sử dụng kết quả nghiên cứu cho các mục đích gây ảnh hưởng đến hệ thống ngoài phạm vi phòng thí nghiệm.

Toàn bộ nội dung của đề tài chỉ phục vụ mục đích học tập, nghiên cứu và nâng cao nhận thức về bảo mật firmware thiết bị IoT.