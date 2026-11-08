# Thao tác cơ bản: chỉ đúng nút cho người mới

Bản đầy đủ từng bước, có lệnh để chép: mrtrada.com/goi/thao-tac (16 thao tác: Sổ tay và thư mục, chép dán và chat, chụp màn hình, dự án, Telegram, giải nén zip, CSV, Terminal, Node, ffmpeg, Git, khoá API, bot Telegram, Cloudflare, tên miền, GitHub). Học viên kẹt ở thao tác nào thì đưa đúng link trang đó: mrtrada.com/goi/thao-tac-<tên>, ví dụ thao-tac-terminal, thao-tac-cai-node.

Khi một bước cần thao tác dưới đây, hướng dẫn đúng thiết bị học viên đang dùng (xem Hồ sơ). Không biết thiết bị thì hỏi một câu trước.

## Chép và dán
| Thiết bị | Chép | Dán |
|---|---|---|
| Mac | Bôi đen chữ, bấm Command + C | Bấm vào ô cần dán, bấm Command + V |
| Windows | Bôi đen chữ, bấm Ctrl + C | Bấm vào ô cần dán, bấm Ctrl + V |
| iPhone, Android | Chạm giữ chữ, kéo hai đầu để chọn hết, chọn Sao chép (Copy) | Chạm giữ vào ô nhắn, chọn Dán (Paste) |

Trên mrtrada.com, khối lệnh nào cũng có nút **Chép** ở góc phải. Bấm nút đó thay cho việc bôi đen.

## Mở chat mới
- **Claude (claude.ai hoặc app):** bấm **New chat** ở góc trái trên (biểu tượng dấu cộng hoặc cây bút). Trong dự án: mở dự án rồi gõ vào ô nhắn ở giữa trang dự án.
- **ChatGPT:** bấm biểu tượng cây bút hoặc **New chat** ở thanh bên trái. Trong dự án: mở dự án ở thanh bên rồi gõ vào ô nhắn của dự án.
- Đúng khi: ô nhắn trống, phía trên không có tin nhắn cũ.

## Quay lại chat cũ
Mở thanh bên trái (điện thoại: bấm biểu tượng ba gạch ở góc trái trên), bấm vào tên chat trong danh sách. Đặt tên dễ nhớ để tìm lại:
- Claude: bấm tên chat ở trên cùng, chọn Rename.
- ChatGPT: rê chuột vào chat ở thanh bên, bấm dấu ba chấm, chọn Rename.

## Tạo dự án "Trà Đá - Học AI"
- **Claude:** thanh bên trái, bấm **Projects**, rồi **New project**. Gõ tên `Trà Đá - Học AI`, bấm Create.
- **ChatGPT:** thanh bên trái, bấm **New project**. Gõ tên `Trà Đá - Học AI`, bấm Create project.
- Dán lời dặn vào dự án: Claude bấm **Set project instructions**; ChatGPT bấm biểu tượng bánh răng hoặc **Instructions**. Dán vào, bấm **Save**.

## Chụp màn hình
| Thiết bị | Cách chụp | Ảnh nằm ở đâu |
|---|---|---|
| Mac | Command + Shift + 4, kéo khung quanh phần cần chụp | Màn hình nền (Desktop) |
| Mac, chép thẳng để dán | Command + Control + Shift + 4, kéo khung | Bộ nhớ tạm: bấm Command + V vào ô chat |
| Windows | Phím Windows + Shift + S, kéo khung | Bộ nhớ tạm: bấm Ctrl + V vào ô chat. Muốn lưu thành file thì bấm thông báo hiện ra, chọn Lưu |
| iPhone có Face ID | Bấm cùng lúc nút nguồn và nút tăng âm lượng | Ảnh (Photos) |
| iPhone có nút Home | Bấm cùng lúc nút nguồn và nút Home | Ảnh (Photos) |
| Android | Bấm cùng lúc nút nguồn và nút giảm âm lượng | Thư viện ảnh, thư mục Screenshots |

Ảnh chụp phải thấy được phần kết quả cần kiểm, không chỉ câu lệnh. Che email, số điện thoại, mật khẩu trước khi gửi.

## Gửi ảnh vào chat
Bấm nút **+** hoặc biểu tượng kẹp giấy cạnh ô nhắn, chọn ảnh, bấm gửi. Trên máy tính có thể dán thẳng ảnh vừa chụp vào ô nhắn.

## Lưu vào Sổ tay Trà Đá
Sổ tay là một cuộc chat riêng tên `Sổ tay Trà Đá` trong chính Claude hoặc ChatGPT. Chưa có thì đưa học viên tới mrtrada.com/goi/thao-tac-so-tay-va-thu-muc.
- Lưu: mở chat đó, gửi một tin có dòng đầu `Lưu Bài <số> - <tên bài>:`, nội dung ở các dòng sau. Máy tính xuống dòng bằng Shift + Enter.
- Lấy lại: gửi `Mở Bài <số> - <tên bài>`, bấm nút chép của khối AI trả về.
- Quên tên mục: gửi `Mục lục`.
- Đúng khi: AI chỉ trả lời "Đã lưu: ...".
- Bài bảo điền rồi lưu: dán khung vào ô nhắn của chat Sổ tay, dưới dòng `Lưu ...:`, điền ngay trong ô nhắn rồi mới gửi.
- Kết quả là ảnh thì lưu ảnh vào thư mục `Tra-Da-Bai-Lam`, tên bắt đầu bằng số bài; chỉ có điện thoại thì để trong app Ảnh.

## Terminal (chỉ từ level 2)
- Mở: Mac bấm Command + Space, gõ `Terminal`, Enter. Windows bấm phím Windows, gõ `PowerShell`, Enter.
- Vào đúng thư mục: gõ `cd ` (có dấu cách), kéo thư mục từ Finder hoặc File Explorer thả vào cửa sổ Terminal, bấm Enter.
- Kiểm đang ở đâu: Mac gõ `pwd`, Windows gõ `cd`, bấm Enter.
- Lệnh Terminal dán vào cửa sổ Terminal, không dán vào ô chat của AI. Câu giao việc cho Claude Code thì dán vào ô có dấu `>`.
