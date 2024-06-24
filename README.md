# Wither Anti Cheat

**Wither Anti Cheat** là một plugin chống gian lận dành cho Minecraft Bedrock Edition (BE) và Minecraft Pocket Edition (PE). Plugin được thiết kế để bảo vệ máy chủ Minecraft của bạn khỏi các hành vi gian lận như sử dụng hack, cheat và các phương pháp không công bằng khác.

## Các tính năng chính

### **Phát hiện, sử lý hack và cheat**
- **Anti Flying**: Ngăn chặn hack bay
- **Anti Speed**: Ngăn chặn người chơi chạy quá nhanh
- **Quản lý các vụ nổ**
>- **Chặn toàn bộ vụ nổ**: Toàn bộ các vụ nổ sẽ không ảnh hưởng đến khối, người chơi.
>
>- **Ngăn chặn TNT nổ hàng loạt**: Giới hạn các TNT trong thế giới. Tối đa mặc định là 3, nếu vượt quá 3 thì TNT khác sẽ không bị kích hoạt. Thay vào đó sẽ chờ đến khi số lượng TNT thấp hơn mới kích hoạt

### **Giao diện người dùng**
- **Giao diện thành viên**: Giao diện với một số tính năng cho người chơi.
  + **Cho phép người chơi**:
    - Tố cáo người chơi
    - Dịch chuyển đến các điểm dịch chuyển hoặc tạo các điểm dịch chuyển(nếu cho phép)
    - Sử dụng các tiện ích được hỗ trợ bởi Wither Anti Cheat

- **Giao diện người hỗ trợ**: Giao diện này cho phép các người chơi được cấp quyền (đổi chế độ chơi, chỉnh thời gian,...). Nhưng vẫn bị hạn chế một vài tính năng nguy hiểm.
  Cho phép người chơi:
   Sử dụng toàn bộ chức năng của **Giao diện thành viên**
   - Thay đổi thời gian
   - Thay đổi thời tiết
   - Lấy vật phẩm
   - Đổi chế độ chơi
   - Dịch chuyển
  
- **Giao diện quản trị viên**: Không bị hạn chế bởi bất kỳ chức năng nào.
  Cho phép:
   Sử dụng toàn bộ chức năng.
   - Tạo điểm dịch chuyển cho tất cả người chơi.
   - Tạo văn bản nổi.
   - Quản lý người chơi.
   - Quản lý rankTag.
   - Tạo khu vực (có thể giới hạn quyền của mỗi khu vực)
    
### **Hệ thống cảnh báo và xử lý**:
- Thông báo các lỗi đã xảy ra trong quá trình chạy.
- Cung cấp các cảnh báo chi tiết về hành vi nghi ngờ và có thể tự động xử lý các trường hợp để đảm bảo sự ổn định cho máy chủ.

## Hướng dẫn cài đặt
**Tải xuống**: Hãy tệp xuống từ trang Web chính thức của [Wither Anti Cheat](https://sites.google.com/view/wither-anti-cheat/wither-anti-cheat)

**Nhập vào Minecraft**
### **Android**
1. Sao chép thư mục gốc của Wither Anti Cheat
2. Di chuyển đến `Android/data/com.mojang.minecraftpe/files/games/com.mojang/behavior_packs/`
3. Dán thư mục vừa sao chép tại đó.

>🔰 **Nếu truy cập bị từ chối** 🔰
> - Nén thư mục gốc của Wither Anti Cheat thành tệp [.zip] sau đó đổi đuôi [.zip] thành [.mcpack]
> - Sử dụng ứng dụng có hỗ trợ nhập tệp [Đề xuất: "Zarchiver"] và nhập vào Minecraft;

### **IOS**
  1. Ấn giữ và chọn di chuyển thư mục gốc của Wither Anti Cheat
  2. Chọn `Trên iPhone`.
  3. Chọn `Minecraft/games/com.mojang/behavior_pack`
  4. Chọn Sao chép

## Cấu hình
- **Giải nén tệp**
- **Mở thu mục và di chuyển đến `.../scripts/$Data/`**
- **Mở tệp `Config.js`**
- **Bây giờ bạn đã có thể cấu hình**
## Đóng góp

Nếu bạn có ý tưởng hoặc phát hiện lỗi, xin vui lòng mở một issue trên GitHub hoặc đóng góp bằng cách gửi pull request. Chúng tôi rất hoan nghênh sự đóng góp của bạn để cải thiện plugin.

## Giấy phép

This project is licensed under the MIT License - see the LICENSE file for details.
