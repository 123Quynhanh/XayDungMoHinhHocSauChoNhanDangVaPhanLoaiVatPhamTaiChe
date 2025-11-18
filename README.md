# ♻️ Xây dựng Mô hình Học sâu để Nhận diện và Phân loại Vật phẩm Tái chế

**Thời gian:** 17/04/2025 – 08/05/2025
**Số lượng thành viên:** 2

---

## Mô tả Dự án

Dự án tập trung vào việc phát triển một mô hình Mạng nơ-ron tích chập (**CNN**) dựa trên kiến trúc **VGG19** để phân loại rác thải thành hai loại chính: **có thể tái chế** và **không thể tái chế**, 
dựa trên dữ liệu hình ảnh thực tế. Mục tiêu là tự động hóa quy trình phân loại rác thải, từ đó **cải thiện hiệu quả thu hồi và tái chế**.

---

## Mục tiêu

* Thu thập, tiền xử lý, và gán nhãn tập dữ liệu hình ảnh rác thải.
* Xây dựng và tinh chỉnh (**fine-tune**) mô hình CNN dựa trên kiến trúc **VGG19**.
* Đánh giá hiệu suất mô hình bằng các chỉ số **độ chính xác** (**Accuracy**) và **Confusion Matrix**.
* Tối ưu hóa kết quả phân loại để đảm bảo tính ứng dụng cao.
* Thực hiện dự đoán nhãn cho các hình ảnh mới, chưa từng thấy (**unseen data**).

---

## Công cụ & Công nghệ

* **Công cụ/IDE:** **Google Colab** – Môi trường phát triển tận dụng GPU để huấn luyện mô hình học sâu.
* **Kiến trúc:** **VGG19** (Convolutional Neural Network - CNN).
* **Thư viện/Ngôn ngữ:** Python (TensorFlow/Keras, OpenCV, Scikit-learn).

---

## Vai trò của tôi

* **Thu thập & Chuẩn bị Dữ liệu:** Thu thập và chuẩn bị 2,233 hình ảnh (1,700 mẫu huấn luyện, 533 mẫu kiểm thử).
* **Gán nhãn Dữ liệu:** Gán nhãn cho hình ảnh thành hai lớp: **"Recycle"** và **"Non-Recycle"**.
* **Tiền xử lý Dữ liệu:** Thực hiện các bước tiền xử lý bao gồm **thay đổi kích thước** (**resizing**), **chuẩn hóa pixel** (**pixel normalization**), và **tăng cường dữ liệu** (**data augmentation**).
* **Xây dựng Mô hình:** Xây dựng và **tinh chỉnh** mô hình CNN dựa trên kiến trúc VGG19.
* **Đánh giá & Tối ưu hóa:** Đánh giá hiệu suất mô hình sử dụng **Accuracy** và **Confusion Matrix**; thực hiện tối ưu hóa kết quả.
* **Dự đoán:** Thực hiện dự đoán nhãn trên dữ liệu kiểm thử và hình ảnh mới.

---
