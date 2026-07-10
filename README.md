# AIEC Hóa Đơn

**Phần mềm tải và quản lý hóa đơn điện tử tự động cho kế toán Việt Nam.**

AIEC Hóa Đơn đồng bộ tự động hóa đơn mua vào từ cổng Tổng cục Thuế ([hoadondientu.gdt.gov.vn](https://hoadondientu.gdt.gov.vn)), tải hóa đơn gốc (PDF/XML) từ các đơn vị cung cấp dịch vụ hóa đơn được hỗ trợ, và lưu toàn bộ dữ liệu ngay trên máy của bạn.

> **Một MST — miễn phí vĩnh viễn, không tính phí theo số lượng hóa đơn.**

[![Tải phiên bản mới nhất](https://img.shields.io/badge/T%E1%BA%A3i%20v%E1%BB%81-Windows-5c6ac4?style=for-the-badge&logo=windows)](https://github.com/longnguyen054/aiec-hoadon/releases/latest/download/aiec-hoadon-setup.exe)
[![Website](https://img.shields.io/badge/Website-hoadon.aiec.vn-0f172a?style=for-the-badge)](https://hoadon.aiec.vn)

---

## Tải về & cài đặt

1. Tải file cài đặt mới nhất: **[aiec-hoadon-setup.exe](https://github.com/longnguyen054/aiec-hoadon/releases/latest/download/aiec-hoadon-setup.exe)**
2. Chạy file `.exe`, làm theo hướng dẫn cài đặt (không cần cấu hình server, không cần IT).
3. Mở phần mềm, đăng nhập MST một lần — xong.

Phần mềm **tự động cập nhật** phiên bản mới qua GitHub Releases, bạn không cần tải lại thủ công.

**Yêu cầu hệ thống:** Windows 10/11 (64-bit).

---

## Tính năng chính

### 🔄 Đồng bộ tự động hàng ngày
Kết nối trực tiếp cổng `hoadondientu.gdt.gov.vn`. Phần mềm tự đăng nhập, tải danh sách hóa đơn mua vào, lưu cache cục bộ — không cần thao tác thủ công. Đồng bộ nền chạy 24/7, tự đăng nhập lại khi token hết hạn: **sáng mở máy là có sẵn hóa đơn mới của ngày hôm trước**.

### 📄 Tải hóa đơn gốc từ đơn vị cung cấp dịch vụ
Tự động tải hóa đơn gốc đúng định dạng do đơn vị cung cấp dịch vụ phát hành, tự retry khi lỗi mạng. Các đơn vị hiện được hỗ trợ:

- EasyInvoice (Softdreams)
- M-Invoice
- MISA meInvoice
- Viettel S-Invoice
- Petrolimex
- ABCSys
- eVat
- VIN-Hoadon
- Golden Gate Group
- … và đang tiếp tục mở rộng

> Đơn vị cung cấp của bạn chưa có trong danh sách? Gửi mẫu hóa đơn về **support@aiec.vn** — chúng tôi sẽ bổ sung trong bản cập nhật kế tiếp.

### 🏢 Quản lý nhiều MST trên một máy
Phù hợp văn phòng dịch vụ kế toán: thêm bao nhiêu MST cũng được, mỗi MST có session và hồ sơ riêng. Chuyển đổi nhanh giữa các MST, không cần đăng xuất/đăng nhập.

### 📊 Xuất Excel + bộ lọc linh hoạt
Lọc theo mã số thuế, khoảng thời gian, loại hóa đơn và trạng thái. Xuất file `.xlsx` hàng nghìn dòng trong vài giây — sẵn sàng import vào MISA, Fast, Bravo hoặc bất kỳ phần mềm kế toán nào.

### 💾 Sao lưu & khôi phục an toàn
Tự động sao lưu cơ sở dữ liệu mỗi 24 giờ, giữ lại 7 bản gần nhất. Backup đầy đủ kèm PDF gốc trong một file ZIP — chuyển dữ liệu sang máy mới chỉ mất khoảng 2 phút.

### 🔒 Chạy offline, dữ liệu là của bạn
Toàn bộ dữ liệu được lưu cục bộ trên máy của bạn, không chuyển ra ngoài hay chia sẻ cho bất kỳ bên thứ ba nào — thông tin hóa đơn và số liệu doanh nghiệp luôn được giữ an toàn, bảo mật.

---

## Triết lý giá: trả tiền cho phần mềm, không trả theo hóa đơn

Các phần mềm hóa đơn khác tính phí theo số lượng hóa đơn xử lý — doanh nghiệp càng phát triển, chi phí phần mềm càng phình ra. AIEC Hóa Đơn tính **phí cố định theo số MST**, xử lý bao nhiêu hóa đơn cũng không đổi:

| Số hóa đơn/tháng | Phần mềm khác | AIEC Hóa Đơn |
| --- | ---: | ---: |
| 500 | ~200.000đ | **0đ** |
| 2.000 | ~800.000đ | **0đ** |
| 10.000 | ~4.000.000đ | **0đ** |

- **1 MST: miễn phí vĩnh viễn** — không giới hạn số lượng hóa đơn tra cứu, lọc, xuất Excel, không khóa tính năng. Gói miễn phí cho tải tối đa 2.500 hóa đơn gốc (PDF/XML); cần nhiều hơn thì nâng lên gói Starter để tải không giới hạn.
- **Nhiều MST:** phí cố định theo gói, không tính theo lượng hóa đơn.

---

## Câu hỏi thường gặp

**Phần mềm có thật sự miễn phí không?**
Có. Với 1 mã số thuế, bạn dùng vĩnh viễn, không giới hạn hóa đơn tra cứu/lọc/xuất Excel và không khóa tính năng. Riêng tải hóa đơn gốc, gói miễn phí hỗ trợ tối đa 2.500 hóa đơn.

**Dữ liệu của tôi được lưu ở đâu?**
Chỉ trên máy của bạn. Không có dữ liệu nào được gửi lên cloud hay chia sẻ cho bên thứ ba.

**Tôi đang dùng MISA / Fast / phần mềm kế toán khác — có tương thích không?**
Có. AIEC kết xuất Excel theo định dạng chuẩn, dùng để import vào MISA, Fast, Bravo hoặc phần mềm kế toán khác.

**Phần mềm chạy trên hệ điều hành nào?**
Hiện chỉ hỗ trợ Windows.

**Chuyển sang máy mới thì làm thế nào?**
Vào tab **Sao lưu** → chọn **Backup đầy đủ** để tạo file ZIP chứa toàn bộ database và PDF gốc. Copy sang máy mới, bấm **Khôi phục** — mất khoảng 2 phút.

---

## Hỗ trợ

- 🌐 Website: **[hoadon.aiec.vn](https://hoadon.aiec.vn)** — bảng giá chi tiết, đăng ký tài khoản, quản lý license
- 📧 Email: **support@aiec.vn**

---

© AIEC Hóa Đơn
