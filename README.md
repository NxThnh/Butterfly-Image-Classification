# 🦋 Butterfly Image Classification

## 📌 Mô tả

Notebook này xây dựng một mô hình học sâu để phân loại các loài **bướm (butterfly)** từ hình ảnh. Dự án áp dụng kỹ thuật **Image Classification** trong lĩnh vực **Computer Vision**, sử dụng mạng nơ-ron tích chập (CNN) để huấn luyện mô hình phân biệt giữa các loài bướm dựa trên dữ liệu hình ảnh.

---

## 🧠 Kiến thức sử dụng

- Xử lý và tăng cường ảnh (Image Preprocessing & Augmentation)
- Xây dựng mô hình CNN bằng TensorFlow/Keras
- Huấn luyện mô hình và theo dõi độ chính xác/loss
- Đánh giá mô hình qua confusion matrix và các chỉ số phân loại

---

## 📂 Cấu trúc nội dung

1. **Import thư viện**
2. **Chuẩn bị dữ liệu**
   - Tải dataset (gồm ảnh các loài bướm)
   - Phân chia train / test / validation
   - Tiền xử lý và tăng cường ảnh
3. **Xây dựng mô hình CNN**
   - Các tầng convolutional, pooling và dense
4. **Huấn luyện mô hình**
   - Biểu đồ loss và accuracy theo từng epoch
5. **Đánh giá mô hình**
   - Độ chính xác (accuracy)
   - Confusion matrix
   - Dự đoán ảnh mới

---

## 📊 Dataset

Dataset gồm nhiều hình ảnh bướm thuộc các loài khác nhau (thường là từ Kaggle hoặc một nguồn mở khác).

> 📝 **Lưu ý:** Dataset không được đính kèm trong repo. Hãy chắc rằng bạn tải đúng tập dữ liệu và đặt vào thư mục tương ứng trước khi chạy notebook.

---

## 🚀 Cách sử dụng

1. Clone repo:
   ```bash
   git clone https://github.com/ten-ban/butterfly-classification.git
   cd butterfly-classification
   ```

2. Chạy notebook:
   - Bằng Jupyter Notebook
   - Hoặc upload lên Google Colab

---

## 🛠️ Yêu cầu

- Python 3.x
- Thư viện:
  - `tensorflow`
  - `keras`
  - `matplotlib`
  - `numpy`
  - `scikit-learn`
  - `opencv-python` (nếu có dùng OpenCV để hiển thị ảnh)

Cài đặt nhanh:
```bash
pip install -r requirements.txt
```

---

## 📌 Ghi chú

- Hãy đảm bảo cấu trúc thư mục chứa hình ảnh đúng với cách được khai báo trong notebook.
- Nếu bạn sử dụng Colab, hãy nhớ mount Google Drive hoặc tải dataset lên Colab session trước khi chạy.

---
