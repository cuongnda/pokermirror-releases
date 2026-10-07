# PokerMirror

App cho Mac để xem lại và phân tích lịch sử hand tournament của chính bạn trên PokerCraft (NATURAL8 / GGPoker): leak của hero, đối thủ, Spot ICM, lãi/lỗ theo giải.

PokerMirror là công cụ độc lập, không liên kết hay được GGPoker, NATURAL8 hoặc PokerCraft bảo trợ. Điều khoản của nhà mạng poker có thể hạn chế công cụ bên thứ ba — bạn chịu trách nhiệm với tài khoản của mình.

## Tải về

Vào **[Releases → bản mới nhất](https://github.com/cuongnda/pokermirror-releases/releases/latest)** và tải file `PokerMirror-<số bản>.zip`.

- Cần macOS 13 trở lên. Chạy được trên Mac chip Apple (M1/M2/M3…) và Mac Intel.
- Không cần cài thêm gì (Python đã nằm sẵn trong app).

## Cài lần đầu

1. Giải nén file zip, kéo **PokerMirror** vào thư mục **Applications**.
2. Mở app. macOS sẽ báo không mở được vì chưa xác minh nhà phát triển → bấm **Done/Xong**.
3. Vào **System Settings → Privacy & Security**, kéo xuống, bấm **Open Anyway / Vẫn mở**, xác nhận bằng mật khẩu máy. Chỉ phải làm một lần.

## Cho app đọc lịch sử hand trong Safari

App đọc lịch sử hand của chính bạn trong tab PokerCraft đang đăng nhập trên Safari. App sẽ hướng dẫn từng bước khi cần:

- **Safari → Cài đặt… → Nâng cao** → tick “Hiển thị tính năng cho nhà phát triển web”; rồi menu **Phát triển** → tick “Cho phép JavaScript từ Apple Events”.
- Khi macOS hỏi, cho phép PokerMirror **điều khiển Safari** và cấp quyền **Trợ năng** (Accessibility) để app bấm phím tải file thay bạn.

Không muốn app tự tải? Bạn có thể tự tải file ZIP lịch sử hand từ PokerCraft rồi nhập vào app (mục **Nhập file ZIP đã tải**). App vẫn mở một hand của chính bạn trên PokerCraft (Safari đang đăng nhập) để xác nhận file là của bạn.

## Cập nhật

Trong app: **Cài đặt → Kiểm tra cập nhật → Cài và khởi động lại**. App chỉ kết nối GitHub khi bạn bấm nút này. Dữ liệu của bạn được giữ nguyên.

## Free và Premium

- **Free**: 1 tài khoản poker, tối đa 10.000 hand, đủ các thống kê chính, danh sách hand và replayer, HUD đối thủ.
- **Premium**: so sánh với bảng range, tìm leak chi tiết, hồ sơ đối thủ chi tiết, nhiều tài khoản và không giới hạn hand.

Để nhận key Premium: mở **Cài đặt → Bản quyền**, chép **mã máy** (dạng `ABCD-EFGH-IJKL`) và gửi cho người phát hành. Dán key nhận được vào cùng chỗ đó. Hết hạn key thì app trở về Free, dữ liệu không mất.

## Dữ liệu và quyền riêng tư

- Mọi dữ liệu nằm trên máy bạn: `~/Library/Application Support/com.cuong.pokermirror` (Cài đặt → **Hiện trong Finder**).
- App không gửi hand hay dữ liệu nào lên mạng. Kết nối duy nhất ngoài trang poker trong Safari là khi bạn bấm **Kiểm tra cập nhật**.
- Gỡ app: xoá PokerMirror trong Applications; muốn xoá cả dữ liệu thì xoá thêm thư mục ở trên.

## Báo lỗi

Gửi cho người phát hành: số bản (Cài đặt → Phiên bản), mô tả lỗi, và nếu được thì thư mục `logs` trong thư mục dữ liệu ở trên.
