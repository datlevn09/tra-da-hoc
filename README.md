# Trà Đá · Trợ lý học bài (skill `tra-da-hoc`)

Skill cho học viên khoá **Trà Đá AI** (mrtrada.com). Cài xong, bạn có một trợ lý:

- dẫn **lộ trình học** theo đúng gói bạn đã mở;
- hướng dẫn **từng bước**: chép đoạn nào, dán vào đâu, chat mới hay chat cũ, tạo dự án tên gì, lưu kết quả ở đâu;
- **kiểm bạn làm đúng chưa** ở từng bước, dựa trên kết quả bạn dán vào;
- **xuất báo cáo** mỗi bài để lưu và nộp cho bot chấm.

Skill **không chứa nội dung bài trả phí**. Bạn mở bài trên mrtrada.com, bấm **Chép bài cho trợ lý học**, rồi dán vào chat. Bài nào bạn mở được thì mới chép được bài đó.

## Lựa chọn 1: dán 1 câu vào chat AI (nên dùng)
Mở app Claude hoặc ChatGPT, bấm chat mới, dán câu này rồi gửi:

```
Cài trợ lý học bài Trà Đá cho tôi theo phần CÀI ĐẶT trong https://raw.githubusercontent.com/datlevn09/tra-da-hoc/main/PROMPT.md. Làm xong chỉ trả lời đúng câu xác nhận ghi trong đó, không liệt kê luật, chưa hỏi gì thêm.
```

Giữ cuộc chat đó làm chỗ học: bài nào cũng dán vào đó. AI không mở được link thì dán nguyên nội dung [`PROMPT.md`](PROMPT.md) thay cho câu trên.

## Lựa chọn 2: cài skill vào Claude (mọi chat đều có trợ lý)
Làm trên máy tính (claude.ai hoặc app Claude cho Mac, Windows). Tải lên một lần, app trên điện thoại cùng tài khoản dùng được.

1. Tải file https://mrtrada.com/media/tra-da-hoc.zip?v=4 về máy. Không giải nén.
2. Trên claude.ai: bấm tên bạn ở góc trái dưới, chọn **Settings**, rồi **Capabilities**, bật **Code execution and file creation**.
3. Vào **Customize**, chọn **Skills**, bấm **+** rồi **Upload a skill**, chọn file `tra-da-hoc.zip`.
4. Mở chat mới trong dự án **Trà Đá - Học AI** và gõ: `học bài`.

## Dùng với ChatGPT
ChatGPT không cài skill được. Thay vào đó, bạn dán nội dung file `CHATGPT.md` vào **Instructions** của dự án **Trà Đá - Học AI**: mở dự án, bấm biểu tượng bánh răng hoặc **Instructions**, dán, bấm **Save**. Sau đó mở chat mới trong dự án và gõ: `học bài`.

## Lựa chọn 2b: cài vào thư mục Claude Code (khi đã học bài 2.1)
Bài cơ bản chỉ cần app Claude ở trên.

Mở Claude Code, dán câu này rồi bấm Enter:

```
Cài skill Trà Đá học bài cho tôi: tải https://github.com/datlevn09/tra-da-hoc/archive/refs/heads/main.zip, giải nén, chép thư mục tra-da-hoc (thư mục có file SKILL.md) vào ~/.claude/skills/tra-da-hoc (Windows: %USERPROFILE%\.claude\skills\tra-da-hoc). Xong thì đọc SKILL.md và chạy chế độ Bắt đầu.
```

Hoặc tự chạy lệnh trong Terminal (Mac):

```
mkdir -p ~/.claude/skills && cd /tmp && curl -L -o tra-da-hoc.zip https://github.com/datlevn09/tra-da-hoc/archive/refs/heads/main.zip && unzip -o tra-da-hoc.zip && rm -rf ~/.claude/skills/tra-da-hoc && cp -R tra-da-hoc-main/tra-da-hoc ~/.claude/skills/
```

Cài xong, mở phiên Claude Code mới rồi gõ: `học bài`.

## Cách học với trợ lý
1. Lần đầu: gõ `học bài`. Trợ lý hỏi vài câu để lập hồ sơ của bạn, rồi hướng dẫn tạo **Sổ tay Trà Đá** và thư mục **Tra-Da-Bai-Lam**.
2. Lấy lộ trình: trên mrtrada.com bấm **Vào học**, mở level, bấm **Chép lộ trình cho trợ lý**, dán vào chat.
3. Học một bài: mở bài, bấm **Chép bài cho trợ lý học**, dán vào **chat mới**. Làm theo từng bước, dán kết quả hoặc gửi ảnh sau mỗi bước để trợ lý kiểm.
4. Hết bài: trợ lý xuất **báo cáo bài**. Lưu vào Sổ tay, rồi gửi cho bot Trà Đá: `/nop <số bài>`.

Giấy phép: dùng tự do cho việc học. Nguồn: Trà Đá AI, mrtrada.com.
