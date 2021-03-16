Đây là phần Demo của nhóm 2 cho phần Convolutional Neuron Network.

Demo này được nhóm mình chạy trên:
- Visual Studio
- Python 3.6
- Tensorflow 1.15
- h5py 2.10.0
- Matplotlib

Dữ liệu đầu vào được để trong thư mục "Hand-writing numbers(1, 2, 3)" và có cấu trúc như sau:
![image](https://user-images.githubusercontent.com/46136255/111360402-4934ba80-86bf-11eb-86e6-d5dc6742b6b7.png)
Các folder "train" và "test" chứa các hình ảnh con số(1, 2, 3) các tệp "y_train.csv" và "y_test.csv" chứa nhãn của các hình ảnh.

Công việc load dữ liệu đầu vào sẽ được thực hiện trong file "ImgData.py", việc áp dụng CNN vào dữ liệu sẽ được thực hiện trong file "CNN.py".
Nhóm có một mô hình đã được lưu sẵn nằm trong file "my_model.h5", các bạn có thể load model đó lên hoặc chạy toàn bộ lại từ đầu.
