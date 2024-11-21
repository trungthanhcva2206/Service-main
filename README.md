# Service-main
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Service dùng xây dựng giao diện và phân quyền người dùng cho ứng dụng.

Nền tảng công nghệ LCDP sử dụng: **Budibase**

## Changelog

### v1.0
- Giao diện đăng nhập
- Giao diện đăng ký bệnh nhân
- Giao diện đăng ký bác sỹ
- Giao diện cập nhật thông tin bác sỹ
- Giao diện cập nhật thông tin bệnh nhân
- Giao diện thêm mới lịch hẹn
- Giao diện cập nhật lịch hẹn
- Giao diện chat bot AI
- Chức năng đăng nhập.
- Kết nối với service [Service-StrapiCotent](https://github.com/trungthanhcva2206/Service-StrapiCotent) để hoàn thiện các chức năng đăng ký bệnh nhân, bác sỹ; cập nhật thông tin bác sỹ, bệnh nhân; thêm mới, cập nhật lịch hẹn.
- Kết nối với service [Service-ChatBot](https://github.com/trungthanhcva2206/Service-ChatBot) để hoàn thiện chức năng chat bot để hỗ trợ lễ tân có thể lựa chọn bác sỹ khám cho bệnh nhân dựa vào các mô tả về sức khỏe của bệnh nhân

## Hướng dẫn cài đặt
### 1. Yêu cầu hệ thống  
- **Budibase**: Phiên bản >=3.0
- **[Service-StrapiCotent](https://github.com/trungthanhcva2206/Service-StrapiCotent)**: Đã được cài đặt
- **[Service-ChatBot](https://github.com/trungthanhcva2206/Service-ChatBot)**: Đã được cài đặt

### 2. Cài đặt dữ án
#### Bước 1: Tải mã nguồn từ bản phát hành
1. Truy cập trang phát hành chính thức tại: [Releases](https://github.com/trungthanhcva2206/Service-main/releases).
2. Chọn phiên bản phù hợp với nhu cầu của bạn.
3. Trong phần **Assets**, tải tệp:
   - `Source code (zip)` hoặc
   - `Source code (tar.gz)`.

#### Bước 2: Import vô Budibase 
1. Truy cập vô Budibase, import tệp vừa tải vô.

#### Bước 3: Lưu ý
1. Ở phần Data: Các API BackEnd chỉnh sửa lại host theo [Service-StrapiCotent](https://github.com/trungthanhcva2206/Service-StrapiCotent) đã được cài đặt trước đó.
2. Ở phần automation: Các webhook N8N chỉnh sửa lại theo [Service-ChatBot](https://github.com/trungthanhcva2206/Service-ChatBot) đã được cài đặt trước đó.

## Tác giả
- Nguyễn Lê Trung Thành
- Trần Tuấn Anh
- Lê Văn Quang

# License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
