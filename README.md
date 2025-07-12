Bộ Dữ Liệu SQL Địa Giới Hành Chính Việt Nam Sau Sáp Nhập 1/7/2025 – Cập Nhật Mới Nhất
Từ ngày 1/7/2025, nhiều đơn vị hành chính tại Việt Nam chính thức được sáp nhập, giải thể, đổi tên theo Nghị quyết mới nhất của Quốc hội. Điều này ảnh hưởng trực tiếp đến:

Doanh nghiệp đang xây dựng hệ thống quản lý địa chỉ

Lập trình viên đang sử dụng dữ liệu hành chính cũ (phường/xã, quận/huyện, tỉnh/thành)

Hệ thống ERP, phần mềm quản lý bán hàng, khai báo thuế, thương mại điện tử…

👉 Để hỗ trợ cộng đồng cập nhật nhanh và chính xác, Foxi Digital đã tổng hợp & xuất bản file SQL mới nhất về hệ thống địa giới hành chính Việt Nam sau sáp nhập. Dữ liệu đã chuẩn hóa, sẵn sàng import vào MySQL/PHPMyAdmin hoặc bất kỳ hệ quản trị nào.

🚀 Tải File SQL Địa Giới Hành Chính Mới (07/2025)
Bạn có thể truy cập kho dữ liệu GitHub tại đây:

🔗 GitHub Repo: https://github.com/foxidigital/database-dia-ban-hanh-chinh-1-7-2025-sau-sat-nhap/
📁 File chính: vietnam_dvhc_2025.sql
📆 Ngày cập nhật: 1/7/2025
💼 Dạng dữ liệu: MySQL dump (.sql) – sẵn sàng import
🔗 Link bài viết: https://foxidigital.com/bo-du-lieu-sql-dia-gioi-hanh-chinh-viet-nam-sau-sap-nhap-1-7-2025-cap-nhat-moi-nhat.html

Bạn chỉ cần 1 thao tác import đơn giản là đã có đầy đủ cấp xã → huyện → tỉnh theo chuẩn mới nhất.

📌 Có Gì Trong Bộ Dữ Liệu Này?
✅ Danh sách đầy đủ các tỉnh/thành sau sáp nhập theo Quyết định 2024/QH

✅ Danh sách quận/huyện mới, huyện sáp nhập hoặc giải thể

✅ Danh sách xã/phường mới, ghi chú nơi đổi tên, sáp nhập

✅ ID định danh duy nhất cho từng cấp (province_id, district_id, ward_id)

✅ Chuẩn hóa UTF-8, không lỗi font, dễ tích hợp

✅ Cấu trúc bảng rõ ràng: provinces, districts, wards

✅ Có thể dùng ngay cho Laravel, PHP, NodeJS, WordPress, v.v.

📂 Cấu Trúc Bảng Chi Tiết
1. provinces

id – mã tỉnh (theo mã định danh quốc gia)

name – tên tỉnh/thành

2. districts

id – mã quận/huyện

name – tên quận/huyện

province_id – liên kết tỉnh/thành

3. wards

id – mã xã/phường

name – tên xã/phường

district_id – liên kết quận/huyện

⚙️ Hướng Dẫn Import File SQL Vào MySQL
Bước 1: Tải file từ GitHub về máy
Bước 2: Mở PHPMyAdmin hoặc dòng lệnh MySQL
Bước 3: Tạo CSDL mới, ví dụ vietnam_dvhc
Bước 4: Import file vietnam_dvhc_2025.sql
Bước 5: Kiểm tra bảng dữ liệu → sử dụng ngay

🎯 Ai Nên Sử Dụng Dữ Liệu Này?
💻 Lập trình viên đang xây dựng hệ thống cần chọn địa chỉ theo cấp xã → huyện → tỉnh

🏢 Doanh nghiệp TMĐT có chức năng chọn địa chỉ khi đặt hàng

🛍️ Website bán hàng cần auto fill địa chỉ theo địa bàn hành chính

📦 Hệ thống ERP/CRM, khai báo BHXH, thuế, v.v.

🏛️ Cơ quan Nhà nước, tổ chức, trường học sử dụng cho các biểu mẫu

🔥 Lý Do Nên Sử Dụng Dữ Liệu Chuẩn Hóa Từ Foxi Digital
✅ Chuẩn hóa & cập nhật mới nhất – không dùng dữ liệu cũ lệch thông tin

✅ Dễ dàng tích hợp với Laravel, WordPress, React, VueJS

✅ Dùng tốt với plugin Contact Form 7, WooCommerce cho địa chỉ tự động

✅ Không cần viết lại API – bạn đã có sẵn dữ liệu đầy đủ, chính xác

✅ Miễn phí hoàn toàn

💡 Làm Sao Để Tích Hợp Vào Website?
Với WordPress:
Dùng plugin tạo form nhập địa chỉ

Gọi dữ liệu từ bảng provinces → districts → wards bằng AJAX

Auto load địa chỉ khi người dùng chọn tỉnh/thành

Với Laravel:
Dùng Seeder để load dữ liệu

Tạo quan hệ Province → District → Ward

Tích hợp vào form đặt hàng, đăng ký, profile người dùng

Với ứng dụng riêng:
Import bảng → Viết API 3 cấp (province, district, ward)

Dùng VueJS, ReactJS để hiển thị dạng chọn địa chỉ theo cấp

👉 Nếu bạn cần file mẫu hoặc hướng dẫn tích hợp cụ thể, hãy liên hệ ngay đội ngũ Foxi Digital.

🌐 Về Foxi Digital – Đơn Vị Phát Triển Dữ Liệu & Thiết Kế Website
Chúng tôi là đơn vị chuyên thiết kế website chuyên nghiệp, lập trình hệ thống web/app, phát triển plugin WordPress & tích hợp dữ liệu cho doanh nghiệp vừa và nhỏ.

Thiết kế website bán hàng, dịch vụ, doanh nghiệp

Tối ưu tốc độ, giao diện chuẩn SEO

Tích hợp hệ thống địa chỉ hành chính đầy đủ 3 cấp

Plugin riêng hỗ trợ chọn địa chỉ, import dữ liệu, đồng bộ hệ thống

📞 Liên hệ hỗ trợ miễn phí

🌐 Website: https://foxidigital.com

☎️ Zalo / Hotline: 038 9690 222

📩 Fanpage: facebook.com/foxidigital

📥 Tải File Ngay – Không Cần Đăng Ký
👉 Xem và tải file tại GitHub

Lưu ý: Dữ liệu được cập nhật chính xác theo các quyết định sáp nhập hành chính mới nhất 2025.
Vui lòng dẫn nguồn Foxi Digital khi sử dụng cho dự án công khai.
