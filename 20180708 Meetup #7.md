# VN Machine Learning Meetup #7

Link event: https://www.facebook.com/events/1772695682776739/

## Tiêu đề: RNN và mô hình hoá ngôn ngữ
## Diễn giả: Đỗ Minh Hải
## Tóm tắt:
Các câu từ trong một văn bản không được sắp xếp một cách ngẫu nhiên mà theo trình tự văn cảnh ngữ nghĩa nhất định nào đó. Nên việc biết trước ngữ cảnh trước đó có thể giúp ta hình dung được ngữ cảnh có thể xuất hiện tiếp theo. Ví dụ, nếu ta có đoạn "Đẹp trai thì lắm", ta có thể dự đoán được từ tiếp theo có thể xuất hiện là "gái", "tiền", "trai"… Trong bài viết này, mình sẽ trình bày về lý thuyết cơ bản của mạng RNN - 1 mô hình mô phỏng sự phụ thuộc văn cảnh như vậy. Ngoài ra, mình cũng nói thêm về biến thể nổi tiếng của RNN là LSTM nhằm nâng cao hiệu quả tính toán của RNN.

※ Bonus: sẽ có 5 phút tổng quan về hội thảo JSAI 2018 vừa diễn ra ở Kagoshima tháng 6 vừa qua do 1 bạn đi thực tế về trình bày.

## Tài liệu tham khảo:
* Cơ bản về RNN

[1] Hopfield (1982). Neural networks and physical systems with emergent collective computational abilities 
https://www.ncbi.nlm.nih.gov/…/PMC34…/pdf/pnas00447-0135.pdf

[2] Rumelhart et al. (1986a). Learning representations by back-propagation errors 
https://www.iro.umontreal.ca/…/if…/lectures/backprop_old.pdf

[3] Jordan (1986). Serial order: A parallel distributed processing approach 
https://pdfs.semanticscholar.org/…/7bb8da085ec419866e0f87e4…

[4] Elman (1990). Finding structure in time 
https://crl.ucsd.edu/~elman/Papers/fsit.pdf

* Thuật toán BPPT

[5] Werbos (1990). Backpropagation Through Time: What It Does and How to Do It 
http://axon.cs.byu.edu/~martin…/…/678/Papers/Werbos_BPTT.pdf

[6] Bengio et al. (1994). Learning Long-Term Dependencies with Gradient Descent is Difficult 
http://www.iro.umontreal.ca/~lisa/pointeurs/ieeetrnn94.pdf

[7] Pascanu et al. (2013). On the difficulty of training Recurrent Neural Networks 
https://arxiv.org/pdf/1211.5063.pdf

* Cơ bản về LSTM

[8] Hochreiter et al. (1997). Long Short-Term Memory 
http://www.bioinf.jku.at/publications/older/2604.pdf

[9] Greff et al. (2017). LSTM: A search space odyssey 
https://arxiv.org/pdf/1503.04069.pdf

* Cơ bản về GRU

[10] Cho et al. (2014). Learning Phrase Representations using RNN Encoder–Decoder for Statistical Machine Translation 
https://arxiv.org/pdf/1406.1078v3.pdf

* Review về RNN, LSTM, GRU

[11] Jozefowics et al. (2015). An Empirical Exploration of Recurrent Network Architectures 
http://proceedings.mlr.press/v37/jozefowicz15.pdf
