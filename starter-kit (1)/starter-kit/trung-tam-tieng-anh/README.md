# Website Trung tâm Tiếng Anh (TTA)

## Giới thiệu
*Dự án website này được xây dựng nhằm **quản lý thông tin học viên** và hỗ trợ quá trình đăng ký khóa học trực tuyến tại Trung tâm Tiếng Anh (TTA).*

## Cấu trúc thư mục
| Thư mục | Nội dung |
| :--- | :--- |
| `archive/` | Lưu trữ các tài liệu cũ và dữ liệu lưu trữ |
| `data/` | Chứa các file Excel quản lý học viên và học phí |
| `logs/` | Chứa các file log hệ thống (access, payment) |

## Quy trình đăng ký học tại TTA
1. Tra cứu thông tin khóa học và học phí mong muốn.
2. Điền thông tin cá nhân và chọn khóa học vào phiếu đăng ký.
3. Hoàn tất thanh toán học phí qua hệ thống thanh toán trực tuyến.

## Lệnh liệt kê nội dung dự án
```powershell
# Trên Windows (PowerShell)
Get-ChildItem -Recurse -Force
```
[x] Tạo cấu trúc thư mục dự án và các file log ban đầu

[ ] Hoàn thiện bảng tính Excel quản lý học phí tháng 10

[ ] Kiểm tra và bảo mật file cấu hình hệ thống

**Lưu ý quan trọng:** *Tuyệt đối giữ file .env trên máy cục bộ, không mở nội dung để chụp ảnh và không được upload lên GitHub dưới mọi hình thức!*