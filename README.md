Đây là ghi chép của tôi trong quá trình tìm hiểu về telegram bot
====

*Có thể những ghi chép này được cóp nhặt vụn vặt từ nhiều nguồn, tôi sẽ để lại link gốc những nguồn mà tôi tham khảo.*

### Telegram bot là gì?

Để trả lời câu hỏi này, thì chúng ta phải trả lời câu hỏi "telegram là gì?".

Telegram là một ứng dụng cung cấp dịch vụ instance message. Đây đồng thời cũng là một ứng dụng OTT, bạn có thể gọi điện thông qua ứng dụng này.. 

Vậy telegram bot là gì? vâng, nó là một con bot kết nối tới telegram để xử lý các message một cách tự động.

### Telegram bot làm được gì?

Telegram bot làm được rất nhiều thứ. Đầu tiên bạn phải biết khái niệm về message mà tôi đề cập ở trên đã. Message nó là một chuỗi text, một file, một ảnh, một video, một poll (bầu chọn).

Bạn liên tưởng tới điều gì chưa? Bạn có thể tạo ra một bot để gửi một lời nhắc tự động về báo cáo cần làm, về deadline công việc. Cao hơn thì bạn tạo ra một chương trình 
kiểm tra trạng thái hoạt động của hệ thống máy chủ, dịch vụ, sẽ gửi lời nhắc nếu có bất thường xảy ra. Hoặc xử lý báo cáo và gửi cho bạn một file báo cáo, gửi một biểu đồ 
phân tích tình trạng hệ thống. Cao cấp hơn nữa thì bạn tương tác với bot để nó tự động gọi vào một chương trình để thực thi yêu cầu như: tắt máy, khởi tạo dịch vụ,...

Cực kỳ tiện lợi đúng không?

### Telegram bot hoạt động như thế nào?

Gọi nó là bot thì nó hoạt động như nào là do bạn điều khiển nó. Vậy làm thế nào để tương tác với bot? Nó chính là các API xử lý dữ liệu với telegram. 

Có các API như:

- Lấy tin nhắn về: getUpdates
- Gửi tin nhắn đi: sendMessage
- ...

Để tương tác với API thì bạn tạo ra một bot trước, khi đó hệ thống telegram sinh ra cho bot 1 token để làm việc với API.

Đã là API thì cực kỳ nhiều cách thức để tương tác: gọi trực tiếp trên trình duyệt, gọi qua thư viện của các chương trình lập trình.

### Kết luận

Tôi sẽ tiếp tục tìm hiểu và viết tiếp thông tin về chủ đề này.

----
Mọi ý kiến đóng góp có thể phản hồi theo địa chỉ sau:
- Skype: crazyman12487
- Gmail: nguyentrongtan124@gmail.com
