# Win11Debloat

[![GitHub Release](https://img.shields.io/github/v/release/Raphire/Win11Debloat?style=for-the-badge&label=Latest%20release)](https://github.com/Raphire/Win11Debloat/releases/latest)
[![Join the Discussion](https://img.shields.io/badge/Join-the%20Discussion-2D9F2D?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Raphire/Win11Debloat/discussions)
[![Static Badge](https://img.shields.io/badge/Documentation-_?style=for-the-badge&logo=bookstack&color=grey)](https://github.com/Raphire/Win11Debloat/wiki/)

Win11Debloat là một tập lệnh PowerShell nhẹ và dễ sử dụng, cho phép bạn nhanh chóng dọn dẹp và tùy chỉnh trải nghiệm Windows của mình mà không cần cài đặt! Bạn có thể sử dụng nó để xóa các ứng dụng được cài đặt sẵn, tắt tính năng thu thập dữ liệu (telemetry), loại bỏ các thành phần giao diện gây phiền nhiễu và nhiều hơn thế nữa. Không cần phải vất vả duyệt qua tất cả các cài đặt hoặc gỡ cài đặt từng ứng dụng một. Win11Debloat giúp quá trình này trở nên nhanh chóng và dễ dàng!

Tập lệnh cũng bao gồm nhiều tính năng mà các quản trị viên hệ thống và người dùng có kinh nghiệm sẽ thích. Chẳng hạn như giao diện dòng lệnh mạnh mẽ, hỗ trợ chế độ Windows Audit và khả năng áp dụng các thay đổi cho những người dùng Windows khác. Bạn cũng có thể dễ dàng xuất và nhập các cài đặt ưa thích của mình, cho phép nhanh chóng áp dụng cùng một cấu hình trên tất cả các hệ thống. Vui lòng tham khảo [wiki](https://github.com/Raphire/Win11Debloat/wiki) của chúng tôi để biết thêm chi tiết.

![Win11Debloat Menu](/Assets/Images/menu.png)

#### Tập lệnh này có giúp ích cho bạn không? Hãy cân nhắc mời tôi một tách cà phê để ủng hộ công việc của tôi nhé

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://www.facebook.com/lethetuan.com.vn/)

## Hướng dẫn sử dụng

> [!Warning]
> Rất nhiều tâm huyết đã được đổ vào để đảm bảo tập lệnh này không vô tình làm hỏng bất kỳ chức năng nào của hệ điều hành, nhưng bạn phải tự chịu rủi ro khi sử dụng!

### Phương pháp tải ứng dụng truyền thống trên Github


  <summary>Tải xuống và chạy tập lệnh theo cách thủ công.</summary><br/>

  1. [Tải xuống phiên bản mới nhất ] và giải nén tệp .ZIP ra.
  3. Mở thư mục Win11Debloat.
  4. Nhấp đúp chuột vào tệp tin `Run.bat` để chạy tập lệnh. LƯU Ý: Nếu cửa sổ console đóng ngay lập tức và không có gì xảy ra, hãy thử phương pháp nâng cao bên dưới.
  5. Chấp nhận lời nhắc UAC của Windows để chạy tập lệnh dưới quyền quản trị viên, điều này là bắt buộc để tập lệnh hoạt động.
  6. Đọc kỹ và làm theo các hướng dẫn trên màn hình.

<img width="1919" height="975" alt="image" src="https://github.com/user-attachments/assets/b811abb2-3d9c-4f3e-8aee-4245e22506e2" />

## Tính năng

Dưới đây là tổng quan về các tính năng và chức năng chính mà Win11Debloat cung cấp. Bạn có thể truy cập [wiki](https://github.com/Raphire/Win11Debloat/wiki) để biết thêm chi tiết.

> [!Tip]
> Tất cả các thay đổi do Win11Debloat thực hiện có thể dễ dàng hoàn tác và hầu hết tất cả các ứng dụng có thể được cài đặt lại thông qua Microsoft Store. Bạn có thể truy cập [wiki](https://github.com/Raphire/Win11Debloat/wiki/Reverting-Changes) để biết thêm thông tin về cách hoàn tác các thay đổi.

#### Xóa Ứng dụng (App Removal)

- Xóa nhiều loại ứng dụng được cài đặt sẵn. Nhấp vào [đây](https://github.com/Raphire/Win11Debloat/wiki/App-Removal) để biết thêm thông tin.

#### Quyền riêng tư & Nội dung được đề xuất

- Tắt tính năng thu thập dữ liệu (telemetry), dữ liệu chẩn đoán, lịch sử hoạt động, theo dõi khởi chạy ứng dụng & quảng cáo nhắm mục tiêu.
- Tắt các mẹo, thủ thuật, đề xuất & quảng cáo trên Windows, màn hình khóa và Microsoft Edge.
- Tắt dịch vụ vị trí của Windows, quyền truy cập vị trí của ứng dụng và theo dõi vị trí Find My Device.
- Ẩn quảng cáo Microsoft 365 trên trang 'Home' của Cài đặt, hoặc ẩn hoàn toàn trang 'Home'.

#### Các tính năng AI

- Tắt & xóa Microsoft Copilot, Windows Recall và Click to Do.
- Ngăn dịch vụ AI (WSAIFabricSvc) tự động khởi chạy.
- Tắt các tính năng AI trong Edge, Paint và Notepad.

#### Hệ thống (System)

- Tắt Drag Tray (Khay kéo) để chia sẻ & di chuyển tệp.
- Khôi phục menu ngữ cảnh chuột phải kiểu cũ của Windows 10.
- Tắt Enhance Pointer Precision (gia tốc chuột).
- Tắt phím tắt Sticky Keys.
- Tắt tính năng dọn dẹp ổ đĩa tự động Storage Sense.
- Tắt khởi động nhanh (fast start-up) để đảm bảo máy tính tắt hoàn toàn.
- Tắt tính năng mã hóa thiết bị tự động BitLocker.
- Tắt kết nối mạng trong chế độ Modern Standby để giảm hao pin.

#### Cập nhật Windows (Windows Update)

- Ngăn Windows nhận các bản cập nhật ngay khi chúng có sẵn.
- Ngăn tự động khởi động lại sau khi cập nhật trong khi đang đăng nhập.
- Tắt tính năng chia sẻ các bản cập nhật đã tải xuống với các PC khác (Delivery Optimization).
- Ngăn Windows tự động cài đặt các ứng dụng đồng hành của thiết bị, như LG Monitor App, Alienware Command Center và nhiều ứng dụng khác.

#### Giao diện (Appearance)

- Bật chế độ tối (dark mode) cho hệ thống và ứng dụng.
- Tắt độ trong suốt, hình động và hiệu ứng hình ảnh.
- Ẩn phím tắt 'Learn about this picture' cho màn hình nền spotlight, hoặc tắt hoàn toàn tùy chọn hình nền Windows spotlight.

#### Start Menu & Tìm kiếm

- Tùy chỉnh Start menu bằng cách xóa các ứng dụng đã ghim, ẩn các đề xuất và tùy chỉnh phần 'All Apps' (Tất cả ứng dụng).
- Tắt tích hợp thiết bị di động Phone Link trong Start menu.
- Tắt tìm kiếm web Bing, tích hợp Copilot và các đề xuất ứng dụng Microsoft Store trong tìm kiếm của Windows.

#### Thanh tác vụ (Taskbar)

- Thay đổi căn chỉnh thanh taskbar.
- Tùy chỉnh hoặc ẩn các nút trên thanh taskbar như thanh tìm kiếm, taskview và nhiều nút khác.
- Tắt widgets trên thanh taskbar & màn hình khóa.
- Bật tùy chọn 'End Task' (Kết thúc tác vụ) trong menu chuột phải trên thanh taskbar để nhanh chóng buộc đóng ứng dụng.
- Bật thao tác 'Last Active Click' trong khu vực ứng dụng trên thanh taskbar. Điều này cho phép bạn nhấp liên tục vào biểu tượng của một ứng dụng trên thanh taskbar để chuyển đổi tiêu điểm giữa các cửa sổ đang mở của ứng dụng đó.
- Tùy chỉnh cách các nút ứng dụng hiển thị trên thanh taskbar.

#### File Explorer

- Thay đổi vị trí mặc định khi File Explorer mở lên.
- Hiển thị phần đuôi mở rộng cho các loại tệp đã biết.
- Hiển thị các tệp, thư mục và ổ đĩa bị ẩn.
- Ẩn phần Home, Gallery hoặc OneDrive khỏi ngăn điều hướng của File Explorer.
- Ẩn các mục ổ đĩa rời bị trùng lặp khỏi ngăn điều hướng của File Explorer, để chỉ giữ lại mục nằm trong 'This PC'.
- Thêm tất cả các thư mục phổ biến (Desktop, Downloads, v.v.) trở lại 'This PC' trong File Explorer.
- Thay đổi vị trí hoặc khả năng hiển thị ký tự ổ đĩa trong File Explorer.

#### Đa nhiệm (Multi-tasking)

- Tắt tính năng snapping cửa sổ (tự động gắn cửa sổ).
- Tắt các đề xuất Snap Assist và Snap Layout khi kéo hoặc chia cửa sổ.
- Thay đổi xem các tab có được hiển thị khi chia cửa sổ hoặc nhấn Alt+Tab hay không.

#### Các tính năng tùy chọn của Windows

- Bật Windows Sandbox, một môi trường máy tính để bàn nhẹ để chạy các ứng dụng một cách an toàn trong môi trường cách ly.
- Bật Windows Subsystem for Linux (WSL) cho phép bạn chạy môi trường Linux trực tiếp trên Windows.

#### Khác

- Tắt tích hợp Xbox Game Bar & quay phim màn hình/trò chơi. Điều này cũng vô hiệu hóa các cửa sổ bật lên `ms-gamingoverlay`/`ms-gamebar` nếu bạn gỡ cài đặt Xbox Game Bar.
- Tắt các tính năng rác trong trình duyệt Brave (AI, Crypto, Tin tức, v.v.)

#### Các tính năng nâng cao

- Khả năng [áp dụng các thay đổi cho một người dùng khác](https://github.com/Raphire/Win11Debloat/wiki/Advanced-Features#running-as-another-user), thay vì người dùng hiện đang đăng nhập.
- [Chế độ Sysprep](https://github.com/Raphire/Win11Debloat/wiki/Advanced-Features#sysprep-mode) để áp dụng các thay đổi cho hồ sơ người dùng Mặc định của Windows. Điều này đảm bảo tất cả người dùng mới sẽ tự động được áp dụng các thay đổi.


## Giấy phép

Win11Debloat được cấp phép theo giấy phép MIT. Xem tệp LICENSE để biết thêm thông tin.
