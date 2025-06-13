# 🪨 Crack Detection on Natural Stone Surface using CNN (LeNet)

## 📌 Mô tả dự án

Dự án này thực hiện bài toán **phân loại vết nứt (crack detection)** trên bề mặt đá tự nhiên (như granite, marble) bằng cách sử dụng mô hình **Convolutional Neural Network (CNN)**. Cụ thể, nhóm lựa chọn kiến trúc **LeNet** – một mô hình nhẹ, đơn giản nhưng hiệu quả – để huấn luyện và đánh giá trên bộ dữ liệu **Concrete-Crack Image Dataset**.

Dự án bao gồm các bước:
- Tiền xử lý và tăng cường dữ liệu
- Xây dựng và huấn luyện mô hình LeNet bằng TensorFlow
- Triển khai mô hình qua API RESTful sử dụng **FastAPI**
- Xây dựng giao diện người dùng với **Streamlit**

---

## 🧠 Kiến trúc mô hình

Mô hình LeNet bao gồm:

- 2 lớp Convolution (ReLU)  
- 2 lớp Pooling  
- 2 lớp Fully Connected  
- 1 lớp đầu ra Sigmoid (phân loại nhị phân)

> ✅ Accuracy trên tập test: **98.6%**

---

## 📂 Cấu trúc thư mục

