# Bài 7: Chuẩn hóa cú pháp Googling sửa lỗi phần mềm điều khiển Kiosk trạm sạc

## Phần 1: Phân tích sai lầm trong tư duy tìm kiếm

1\. Vì sao Query 1 là Bad Query?

Query 1 là Bad Query vì sử dụng câu văn nói dài dòng, có nhiều từ cảm thán như "thầy ơi", "tại sao", "giúp em với" mà không có từ khóa kỹ thuật cụ thể.

Điều này khiến Google khó xác định chính xác vấn đề cần tìm, dẫn đến kết quả bị nhiễu, xuất hiện nhiều bài viết không liên quan, quảng cáo và diễn đàn chung chung.

2\. Hiểm họa khi click vào kết quả của Query 3

Việc tìm kiếm phần mềm crack và công cụ fix lỗi không rõ nguồn gốc có thể dẫn đến:

- Nhiễm virus, Trojan hoặc mã độc vào máy tính.
- Bị đánh cắp mật khẩu, tài khoản và dữ liệu công ty.
- Hacker có thể kiểm soát máy tính từ xa.
- Làm gián đoạn hoạt động của hệ thống trạm sạc.

Vì vậy, không nên tải hoặc chạy phần mềm từ những trang web không đáng tin cậy.

## Phần 2: Chuẩn hóa cú pháp tìm kiếm chuyên nghiệp

3\. Bóc tách thông báo lỗi thành 3 thành phần cốt lõi

| Thành phần cốt lõi            | Nội dung trích xuất chuẩn        | Mục đích lọc tìm kiếm              |
| ----------------------------- | -------------------------------- | ---------------------------------- |
| 1. Tên phần mềm và môi trường | VoltCharge Controller Windows 11 | Tìm đúng phần mềm và hệ điều hành. |
| 2. Mã lỗi nguyên văn          | `"Access is denied"`             | Tìm chính xác thông báo lỗi.       |
| 3. Thao tác / Giao thức       | `bind OCPP port`                 | Xác định thao tác đang gây ra lỗi. |

4\. Xây dựng 3 câu lệnh tìm kiếm Google chuẩn kỹ sư

\* Cú pháp 1: Tìm lỗi trên Microsoft Community dành cho Windows 11.

```
site:learn.microsoft.com "Access is denied" "bind OCPP port" Windows 11 -win7 -win8
```

\* Cú pháp 2: Tìm tài liệu về giao thức OCPP trên trang Open Charge Alliance.

```
site:openchargealliance.org "OCPP" "Access is denied" port
```

\* Cú pháp 3: Tìm hướng dẫn sửa lỗi trên Stack Overflow, loại bỏ quảng cáo và crack.

```
site:stackoverflow.com "Access is denied" "bind OCPP port" Windows 11 -crack -quangcao -advertisement
```

Ý nghĩa các toán tử:

- `site:`: Giới hạn kết quả trong một trang web cụ thể.
- `"..."`: Tìm chính xác cụm từ được đặt trong ngoặc kép.
- `-`: Loại bỏ những kết quả chứa từ khóa không mong muốn.

## Phần 3: Kết luận

Theo em, khi tìm kiếm lỗi lập trình cần sử dụng từ khóa kỹ thuật ngắn gọn, chính xác thay vì viết câu văn nói dài dòng. Việc kết hợp các toán tử Google giúp tìm kiếm nhanh hơn, giảm kết quả không liên quan và hạn chế nguy cơ truy cập vào những trang web độc hại.
