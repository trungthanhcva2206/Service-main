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
- **[Service-StrapiCotent](https://github.com/trungthanhcva2206/Service-StrapiCotent)**
- **[Service-ChatBot](https://github.com/trungthanhcva2206/Service-ChatBot)**

### 2. Cài đặt dữ án
#### Bước 1: Tải mã nguồn từ bản phát hành
1. Truy cập trang phát hành chính thức tại: [Releases](https://github.com/trungthanhcva2206/Service-main/releases).
2. Chọn phiên bản phù hợp với nhu cầu của bạn.
3. Trong phần **Assets**, tải tệp:
   - `Source code (zip)` hoặc
   - `Source code (tar.gz)`.

#### Bước 2: Giải nén và truy cập thư mục
```bash
# Giải nén file đã tải
unzip Service-ChatBot.zip
cd Service-ChatBot
```
#### Bước 3: Import vô N8N 
1. Tạo 1 workflow trong N8N
2. Import file Agent.json, file này lấy được ở trong thư mục Service-ChatBot

#### Bước 4: Chỉnh sửa các tài khoản dịch vụ
Ở trong các node OpenAI, Pinecone sẽ có phần **Credential to connect with**, có thể chỉnh sửa các tài khoản dịch vụ của mình ở đây. 

## Tác giả
- Nguyễn Lê Trung Thành
- Trần Tuấn Anh
- Lê Văn Quang

# License
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
