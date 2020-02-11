# Giới thiệu về chuỗi 3 meetups về BERT
Transfer Learning là một trong những tính năng quan trọng của Deep Learning, khi một mô hình mạng Neural có thể được huấn luyện trên một bộ dữ liệu, sau đó mô hình được chuyển sang huấn luyện tăng cường trên một bộ dữ liệu khác. Bộ tham số của mô hình mạng khi đó được tối ưu trên cả 2 tập dữ liệu. Hay nói cách khác, mô hình mạng Neural lúc này sẽ chứa đựng tri thức của cả 2 bộ dữ liệu đã được sử dụng.

Transfer Learning được sử dụng rất nhiều và gần như trở thành một tính năng không thể thiếu khi áp dụng Deep Learning để giải các bài toán thuộc Computer Vision từ khi có bộ dữ liệu ImageNet. Transfer Learning trong Computer Vision giúp cho các mô hình mạng Neural học được những đặc trưng thị giác có mức độ ngữ nghĩa ở cấp cao từ bộ dữ liệu ImageNet. 

Tuy nhiên, đối với các bài toán liên quan đến xử lý văn bản, Transfer Learning chỉ dừng ở mức tận dụng thông tin ngữ nghĩa tương đồng của các từ đơn lẻ thông qua Word Embedding. Giới hạn này tồn tại tương đối lâu, và chỉ bị gỡ bỏ khi một loạt các nghiên cứu về Transfer Learning cho ngôn ngữ được đề xuất vào năm 2018, như ELMo, ULMFiT cho tới GPT. Các mô hình này mở rộng các bộ tham số của mạng Neural được sử dụng lại khi huấn luyện từ tập dữ liệu này sang tập dữ liệu khác. 

Và gần đây nhất, vào cuối năm 2018, một mô hình có tên gọi BERT (viết tắt của cụm từ Bidirectional Encoder Representations from Transformers) được đề xuất nhằm đưa Transfer Learning tới một giới hạn mới trong xử lý các bài toán xử lý văn bản. BERT đã cho kết quả đột phá trên 11 bài toán khác nhau, và được kỳ vọng đem lại một cuộc cách mạng mới cho Transfer Learning cũng như Deep Learning trong xử lý văn bản.

Vậy thì bản chất BERT là gì, có thể ứng dụng ra sao, hay làm sao để dùng BERT trong các bài toán thực tế về văn bản mà chúng ta thường gặp? Để giải đáp những gút mắc thường gặp ấy, VJAI xin tổ chức 1 chuỗi 3 meetups liên tiếp về các chủ đề liên quan đến BERT.

Sau đây là lịch sơ bộ của 3 buổi meetups:
- Buổi 1 (VJAI Meetup #19): 14h~18h Chủ nhật - 15/12/2019: Kiến thức cơ bản về Attention, Transformer & BERT
- Buổi 2 (VJAI Meetup #20): 14h~18h Chủ nhật - 9/2/2020: Làm sao để dùng BERT trong production
- Buổi 3 (VJAI Meetup #21): 14h~18h Chủ nhật - 23/2/2020: Các ứng dụng của BERT

Với loạt meetup lần này, Ban tổ chức (BTC) hi vọng cộng đồng của chúng ta sẽ có những buổi thảo luận thật sâu, hiểu cặn kẽ và chia sẻ những kinh nghiệm thực tế đối với chủ đề BERT. Do đó, BTC rất mong các bạn tìm hiểu về chủ đề liên quan trong khả năng có thể trước khi tham gia meetup.


# VJAI Meetup #19

:clock3: Thời gian: 14h~18h Chủ nhật - 15/12/2019 (mở cửa đón khách 13h40 ~ 13h55)

:point_right: Form đăng ký tham dự: https://forms.gle/douhKZ1Mbya73bVU9
(Hạn cuối đăng ký là 23:59 thứ 6 ngày 13/12/2019)

Mở đầu loạt meetups về BERT là 1 buổi (VJAI Meetup #19) về chủ đề "Kiến thức cơ bản về Attention, Transformer & BERT". Hãy cùng đến nghe và xem các tác giả giới thiệu những kiến thức liên quan công nghệ BERT đình đám nhé.



- Địa điểm: BizReach, Inc. 渋谷363清水ビル<br>
〒150-0002, 3 Chome-6-3 Shibuya, Tokyo
https://goo.gl/maps/VbbahJ1x9152

Ai không kịp đăng ký trước thời hạn trên sẽ không được vào toà nhà nên ngoài ấn Going thì các bạn **nhớ điền vào form** trên nhé.

Việc vào toà nhà không dễ dàng nên các bạn tính toán thời gian cẩn thận để đến đúng giờ nhé.

Hẹn gặp lại cả nhà vào buổi sắp tới!

Nội dung chương trình của buổi meetup#19:

---
### Understand Transformer by going through the Annotated Transformer code
### Speaker: Nguyễn Tuấn Dương
### Abstract: 
Dive into Transformer with annotated code. We focus on discussion and Q&A on key techniques, and also introduce some interesting ideas from recent work.
- Ref:
* Annotated Transformer, https://nlp.seas.harvard.edu/2018/04/03/attention.html


---
### BERT as an application of Transformer and understanding the secret of BERT
### Speaker: Phạm Quang Khang
