---
title: "Tra cứu thông tin thiết bị: cấu hình, điểm benchmark, tốc độ mạng, dòng chip"
source_url: "https://flowin.cn/publish/c3ab35aafc9442a08cd78f700c6a02f3/7bb4bec0c7e348889d69535d4cd456a9"
depth: 3
section: "ClassIn"
language: "vi"
---

# Tra cứu thông tin thiết bị: cấu hình, điểm benchmark, tốc độ mạng, dòng chip

Hướng dẫn sử dụng (bản tiếng Anh)

# I. Tra cứu cấu hình thiết bị

## Trường hợp áp dụng

Xem cấu hình máy tính là kiểm tra thông số phần cứng và hệ thống của máy, để đảm bảo đáp ứng yêu cầu của phần mềm cụ thể. Người dùng máy tính có thể tham khảo các thông số phần cứng trong 《Yêu cầu cấu hình máy tính》, sau đó so sánh với cấu hình máy của mình để xác nhận máy có chạy được ClassIn không.

## Các bước thực hiện

### (1) Máy tính Windows

Nhấn chuột phải vào "This PC" (Máy tính này) trên desktop

Chọn "Properties" (Thuộc tính)

Trong mục "Device specifications" (Thông số thiết bị), xem dung lượng RAM và dòng CPU của máy

![Xem cấu hình Windows](https://cofile.eeo.cn/res-store%2F207d74d5f0e039ef1498ace4e289f42cb4e480653d840eb3c47df6733319d61b_254401?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=82c2969925bd7134ba35e3fb67c100d9ed687e63)

### (2) Máy Mac

Mở "Launchpad"

Trong ô tìm kiếm, gõ "Terminal" (Thiết bị đầu cuối), rồi mở ứng dụng Terminal

Trong cửa sổ Terminal, ở phía sau dòng nhắc lệnh (ví dụ tên máy $), gõ: `sysctl machdep.cpu.brand_string`

Sau khi gõ xong, nhấn phím Enter

Xem thông tin dòng CPU của máy trong kết quả hiện ra sau khi chạy lệnh

![Xem cấu hình Mac](https://cofile.eeo.cn/res-store%2Fd8e2f7bd40c5df5a8612c7bb3e852b5d2fe0243d74dcf5560cb1859dd34fcea5_361026?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=24d5c2fa2a2f9e340e6f51170e22071a2f610772)

# II. Kiểm tra tốc độ mạng

Để đảm bảo có kết nối mạng ổn định khi dạy/học trực tuyến trên ClassIn, hãy kiểm tra tình trạng mạng trước khi bắt đầu. Kiểm tra và tối ưu thiết lập mạng trước sẽ giúp ClassIn chạy mượt, hỗ trợ tốt cho việc giảng dạy trực tuyến.

## Hướng dẫn sử dụng

Dưới đây là các chỉ số quan trọng cần chú ý trong kết quả kiểm tra: tốc độ upload, tốc độ download, độ trễ (ping), độ rung (jitter) và tỷ lệ mất gói. Nếu mạng của bạn không đáp ứng đủ các yêu cầu dưới đây, có thể gặp tình trạng kết nối không ổn định, rớt mạng liên tục khi dùng ClassIn, ảnh hưởng đến hiệu quả giảng dạy.

| Yêu cầu mạng tối thiểu |
| --- |
| Tốc độ upload: từ 2Mbps trở lên |
| Tốc độ download: từ 2Mbps trở lên |
| Độ trễ: trong nước Trung Quốc không quá 50ms, khu vực nước ngoài không quá 300ms |
| Tỷ lệ mất gói: phải bằng 0% |

Mở trình duyệt

Nhập vào thanh địa chỉ: https://www.speedtest.cn (hoặc dùng công cụ đo tốc độ mạng khác phù hợp với khu vực của bạn)

Nhấn "Đo tốc độ"

![Kiểm tra tốc độ mạng](https://cofile.eeo.cn/res-store%2F46e397fb953659ed33b6119718556f27b879769eae8acb042399cad96d359215_366221?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=1c368b8a4de4a408039fe6447a6a79dccd3d22eb)

# III. Tra cứu điểm benchmark thiết bị

### Trường hợp áp dụng

Người dùng có thể dựa vào dòng CPU của máy tính, tra cứu điểm hiệu năng CPU trên trang web benchmark chuyên dụng, để xác định máy có đủ đáp ứng để chạy ClassIn hay không.

### Hướng dẫn sử dụng

Điểm CPU của máy giáo viên cần đạt 6000 điểm trở lên.

Điểm CPU của máy học sinh cần đạt 4000 điểm trở lên.

### Các bước thực hiện

Nhập vào thanh địa chỉ trình duyệt: https://www.cpubenchmark.net/cpu_list.php

Trong ô tìm kiếm, nhập dòng CPU của máy bạn

Nhấn "Find CPU" để tìm kiếm

Tìm dòng CPU trùng khớp hoàn toàn với CPU máy bạn trong vùng màu vàng bên trái

Xem giá trị ở cột "CPU Mark" bên phải — đây chính là điểm hiệu năng CPU của máy bạn

![Tra cứu điểm CPU](https://cofile.eeo.cn/res-store%2F57ebd37b9391dcc022dca39ec54aa02be8efe5a589e51f54dec7efb985ed1179_379263?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=a6179c425172f8f5c7289fccf95558b10e6f3f36)

# IV. Tra cứu dòng chip máy Mac

ClassIn cung cấp 2 loại bộ cài cho máy Mac: một cho Mac chip Intel, một cho Mac chip Apple (như M1, M2...). Vì vậy, trước khi tải bộ cài, cần xác nhận trước loại chip máy tính của mình để chọn đúng bộ cài phù hợp.

Di chuột vào biểu tượng Apple ở góc trên bên trái màn hình

Nhấn "About This Mac" (Giới thiệu về máy Mac này)

Trong màn hình giới thiệu, xem dòng chip CPU ở mục "Chip" hoặc "Processor"

![Tra cứu dòng chip Mac](https://cofile.eeo.cn/res-store%2Fa123ab72dc9c959fe87db4f2f7e97e2c25cae4e4e015a92b5a98d9815a6cfc25_461854?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=9a884733f148e07102c7b71df32b6837e017f04e)
