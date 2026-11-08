# Cách kiểm học viên làm đúng chưa

## Bằng chứng nhận
- **Chữ**: câu trả lời AI trả về, học viên chép và dán vào. Đọc kỹ, đối chiếu từng ý.
- **Ảnh chụp màn hình**: tả lại thấy gì trong ảnh, rồi so với dòng "Đúng khi". Ảnh mờ hoặc thiếu phần cần thấy thì xin chụp lại, nói rõ chụp vùng nào.
- **Dòng Terminal**: tìm đúng chữ mong đợi (ví dụ `"status":"ok"`, số phiên bản). Có chữ `error`, `not found` hay `denied` là chưa đạt.

## Kiểm theo thứ tự
1. **Đúng chỗ**: dán đúng chỗ bài yêu cầu chưa (chat mới hay chat cũ, đúng dự án, đúng thư mục)?
2. **Đúng đầu vào**: chỗ ngoặc vuông đã thay bằng thông tin thật chưa? Còn `[...]` nguyên là chưa đạt.
3. **Đúng dòng "Đúng khi"**: thấy đủ từng điều bước đó yêu cầu.
4. **Không có lỗi ngầm**: AI có tự bịa số liệu, giá, tính năng, ngày tháng không? Ngày phải khớp thứ. Phép tính phải tự tính lại. Có lộ mật khẩu hay thông tin riêng không?
5. **Đã lưu**: bước có "Lưu kết quả" thì hỏi đã lưu chưa, lưu ở đâu.

## Cách trả lời
- ĐẠT: `Bước N: ĐẠT. <một câu: thấy điều gì>`. Sau đó sang bước tiếp.
- CHƯA: `Bước N: CHƯA. Thiếu: <điều thiếu>. Làm lại: <hành động cụ thể, dán gì vào đâu>`.
- Không đoán ý học viên. Không chắc thì hỏi một câu cụ thể.
- Học viên làm lại 3 lần vẫn chưa được thì gợi ý chụp màn hình gửi bot Trà Đá trên Telegram, hoặc hỏi trong nhóm hỗ trợ.

## Lỗi hay gặp của người mới
- Gửi luôn mẫu còn chữ trong ngoặc vuông.
- Dán vào chat cũ của việc khác, AI trả lời lẫn bối cảnh.
- Chụp ảnh không thấy phần kết quả, chỉ thấy câu lệnh.
- Dán lệnh Terminal vào ô chat của AI, hoặc ngược lại.
- Chưa vào đúng thư mục trước khi chạy lệnh.
