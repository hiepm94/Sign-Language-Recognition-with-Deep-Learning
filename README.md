# Sign Language Recognition with Deep Learning
## Nội dung dự án
Ngôn ngữ ký hiệu là ngôn ngữ hình thể được sử dụng để giao tiếp với người điếc. Thông qua các thao tác, cử chỉ tay và biểu cảm gương mặt, những người điếc có thể dễ dàng truyền tải nội dung, ý muốn của mình tới người khác. 

Bài toán nhận diện ngôn ngữ ký hiệu ở đây áp dụng công nghệ Deep Learning giúp nhận diện những con số và chữ cái thông qua các hình ảnh cử chỉ bàn tay.
Chữ cái được đề cập ở đây gồm 26 chữ cái Latin gồm : a, b, c, d,..., x, y, z.
## Dataset
Dataset được thu thập trên [Kaggle](https://www.kaggle.com/datasets/ayuraj/asl-dataset), gồm 36 tập tin tương ứng với 36 số + chữ cái, mỗi tập tin có 70 bức ảnh.
## Deep Learning
Mạng nơron tích chập được xây dựng gồm các lớp 2D Convolution, MaxPooling2D, Flatten, Dense với tổng số lượng param là 582756.
Kết quả mô hình cho ra kết quả độ chính xác trên tập thử lên đến 0.9442231059074402.
## Interface Demo
Sau đây là hình ảnh demo mô tả minh họa cho dự án: 
<img width="960" alt="msedge_BhnB4GZ2FD" src="https://github.com/hiepm94/Sign-Language-Recognition-with-Deep-Learning/assets/96098339/bf50567f-c02c-441c-a911-fbe30eb98c0d">
