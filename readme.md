# Phát hiện Quả Chín trong Ảnh sử dụng K-means Clustering

Đây là một dự án nghiên cứu áp dụng thuật toán phân cụm K-means và K-means++ để phát hiện và xác định vị trí của các quả chín trong ảnh. 

## Mô tả

Dự án này sử dụng thuật toán K-means và K-means++ để phân cụm các điểm ảnh dựa trên đặc trưng màu sắc và vị trí. Sau khi phân cụm, các cụm có đặc trưng tương ứng với quả chín (như màu sắc, kích thước, hình dạng) sẽ được xác định và đánh dấu trên ảnh.

## Cấu trúc thư mục

- `image/`: Thư mục chứa dữ liệu ảnh đầu vào
- `report/`: source báo cáo latex 
- `results/`: Thư mục chứa kết quả (ảnh đầu ra)
- `Nhóm 02_Clustering.pdf`: File báo cáo
- `requirements.txt`: File liệt kê các thư viện Python cần thiết
- `Kmeans_detect_ripe_fruit.ipynb`: Tệp mã nguồn của dự án
- `README.md`: Tệp này

## Cách sử dụng

1. Clone repo:

```
git clone https://github.com/username/fruit-detection-kmeans.git
```

2. Cài đặt các thư viện cần thiết:

```
pip install -r requirements.txt
```

3. Đặt ảnh đầu vào trong thư mục `iamge/`.

4. Chạy các code trong file Kmeans_detect_ripe_fruit.ipynb

Ảnh đầu ra với các quả chín được đánh dấu sẽ được lưu trong thư mục `results/`.

## Tài liệu tham khảo

- Nguyen Duc Quy. (2021). *Thuật toán phân cụm KMeans*. Truy cập từ https://ndquy.github.io/posts/thuat-toan-phan-cum-kmeans/
- GeeksforGeeks. (2024). *ML - K-Means Algorithm*. Truy cập từ https://www.geeksforgeeks.org/ml-k-means-algorithm/



## Thông tin liên hệ
- Lê Phạm Công
- Email: lpc051002@gmail.com



Tệp README này cung cấp một tổng quan về dự án, cách sử dụng, cấu trúc thư mục, tài liệu liên quan và thông tin đóng góp. Nó giúp người dùng hiểu rõ hơn về mục đích, chức năng và cách triển khai dự án phát hiện quả chín trong ảnh sử dụng thuật toán K-means.