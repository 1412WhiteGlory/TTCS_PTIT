# TTCS_PTIT
Thực tập cơ sở thầy Nguyễn Tất Thắng

****ĐỀ TÀI: SỬ DỤNG MÔ HÌNH CNN VÀO VIỆC PHÂN LOẠI CHÓ, MÈO****

**Công nghệ chính:**
1. Mô hình CNN
2. Tensorflow
3. Python
4. Google Colab hoặc Jupyter Notebook

**Giới thiệu**
1. Mô hình CNN:
  - Mạng nơ-ron tích chập (CNN), một kỹ thuật trong lĩnh vực Deep-learning, đã trở thành một cuộc cách mạng trong các ứng dụng Nhận dạng Hình ảnh, đặc biệt trong khoảng 5 năm trở lại đây. Một ứng dụng chính của nó là phân loại hình ảnh, ví dụ như xác định xem một bức ảnh là của chó hay mèo.

  - Tất nhiên, bạn không phải giới hạn mình chỉ với một bộ phân loại nhị phân; các mạng nơ-ron tích chập (CNN) hoàn toàn có thể mở rộng để phân loại hàng nghìn lớp khác nhau, như trong bộ dữ liệu nổi tiếng ImageNet với 1000 lớp, được sử dụng để đánh giá hiệu suất các thuật toán nhận dạng hình ảnh.

  - Trong vài năm gần đây, các kỹ thuật tiên tiến này đã bắt đầu trở nên dễ tiếp cận với cộng đồng phát triển phần mềm rộng lớn hơn. Các gói phần mềm mạnh mẽ như Tensorflow đã mang đến cho chúng ta những công cụ tương tự mà Google sử dụng để viết các ứng dụng học sâu cho thiết bị nhúng, di động và các cụm máy tính đám mây có thể mở rộng — mà không cần phải tự viết tay các phép toán ma trận trên GPU, đạo hàm riêng phần, và các bộ tối ưu ngẫu nhiên giúp các ứng dụng hoạt động hiệu quả.

Ngoài tất cả những điều này, còn có các API thân thiện với người dùng như Keras, giúp ẩn đi những chi tiết cấp thấp và cho phép chúng ta tập trung vào việc nhanh chóng tạo mẫu một đồ thị tính toán học sâu.

**MÔ TẢ DỰ ÁN**
Sử dụng mô hình CNN để phân biệt hình ảnh chó và mèo. Số lượng hình ảnh dùng cho dự án như sau:
- Tổng số ảnh mèo dùng để huấn luyện: 8750
- Tổng số ảnh chó dùng để huấn luyện: 8750
- Tổng số ảnh mèo dùng để kiểm tra: 3750
- Tổng số ảnh chó dùng để kiểm tra: 3750
- Bộ dữ liệu này được lấy từ Kaggle

**MỤC TIÊU CHÍNH DỰ ÁN**
- Làm quen với môn Trí tuệ nhân tạo
- Làm quen với Tensorflow và các cú pháp.

**PHƯƠNG PHÁP**
- Mô hình CNN sử dụng các hàm kích hoạt 'relu' và 'sigmoid'
- Phân loại và hàm mất mát là 'binary-crossentropy'.

**KHỞI CHẠY CHƯƠNG TRÌNH**
- Để chạy mô hình trên thiết bị của bạn, mở mã nguồn trong trình biên dịch Python (Jupyter Notebook/Colab). Sau đó chạy phần dự đoán trong mã và tải lên ảnh từ thiết bị của bạn hoặc từ URL.

**KẾT QUẢ**
- Sau khi tinh chỉnh mô hình được mã hóa cứng, độ chính xác của mô hình trên bộ kiểm tra đạt tới 85%.
- Mô hình và dự án hiện tại vẫn chưa được tối ưu hoàn toàn và công việc vẫn đang được tiếp tục. Chắc chắn sẵn sàng đón nhận sự giúp đỡ và ý tưởng mới!
