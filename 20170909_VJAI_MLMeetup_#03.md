# VN Machine Learning Meetup #3

Link event: https://www.facebook.com/events/139675323300859

Thời gian: 10:00-13:00
Địa điểm: 東京都渋谷区道玄坂1-17-9 ヴェラハイツ506号室
Địa điểm lần này là ở Shibuya, khác với mọi lần nên mọi người chú ý
Khái quát nội dung:
Giới thiệu về generative modeling, một bài toán trong unsupervised learning. Cụ thể chúng ta sẽ tìm hiểu về mô hình GAN và một hướng tiếp cận từ góc nhìn distribution matching.
Tác giả: Nguyễn Dương, Nguyễn Đạt

1 đôi lời về GANs(Generative Adversarial Network):
"Generative Adversarial Network (GAN), and the variations that are now being proposed is the most interesting idea in the last 10 years in ML, in my opinion." Yann LeCun
Ý tưởng của GAN là sinh ra dữ liệu tổng hợp (artificial data) từ những dữ liệu có sẵn và dữ liệu mới này sẽ giống thật đến mức ko thể phân biệt dc nó là hàng dc tạo ra chứ không phải dữ liệu có ban đầu.
1 ví dụ rất hay được dùng để nói về GAN là việc training cho 1 anh cảnh sát chuyên đi phân biệt tiền giả tiền thật và training cho 1 anh trộm chuyên làm tiền giả. Việc training song song cho cả 2 người sẽ đc tiến hành bằng cách trộm in tiền giả ra đưa cho cảnh xem, nhận lại feedback là đấy là giả hay thật. Việc chạy song song sẽ dừng khi ảnh cảnh sát của chúng ta không còn phân biệt dc thật và giả nữa, từ đấy chúng ta có máy in tiền xịn :D
Đây là link tài liệu gốc cho các bạn muốn xem kỹ thêm:
https://arxiv.org/abs/1406.2661

* **Slide**:
  * https://github.com/nptdat/gan_tutorial/blob/master/GAN.pdf

* **Demo**:
  * https://github.com/nptdat/gan_tutorial/blob/master/DEMO_GAN.ipynb
  * https://github.com/nptdat/gan_tutorial/blob/master/DEMO_DCGAN_MNIST.ipynb
