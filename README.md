# Tự Học Machine Learning

[![Python](https://img.shields.io/badge/Python-3.7+-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)

Đây là kho tài liệu học tập Machine Learning từ cơ bản đến nâng cao, với các bài tập và ví dụ thực hành.

## 📚 Mục Lục

- [Giới Thiệu](#giới-thiệu)
- [Cấu Trúc Thư Mục](#cấu-trúc-thư-mục)
- [Yêu Cầu Hệ Thống](#yêu-cầu-hệ-thống)
- [Cài Đặt](#cài-đặt)
- [Nội Dung Học](#nội-dung-học)
- [Cách Sử Dụng](#cách-sử-dụng)
- [Tài Liệu Tham Khảo](#tài-liệu-tham-khảo)
- [Đóng Góp](#đóng-góp)
- [Liên Hệ](#liên-hệ)

## 🎯 Giới Thiệu

Repository này chứa các tài liệu học tập, bài tập và code thực hành về Machine Learning. Mục tiêu là giúp người học:

- Hiểu các khái niệm cơ bản về Machine Learning
- Thực hành với các thuật toán phổ biến
- Xây dựng mô hình từ đầu (from scratch)
- Áp dụng vào các bài toán thực tế

## 📂 Cấu Trúc Thư Mục

```
[TỰ HỌC MACHINE LEARNING]/
├── BUỔI 1/
│   ├── Buổi 1.pdf           # Tài liệu lý thuyết
│   └── Buổi_1.ipynb         # Notebook thực hành
├── README.md                 # File này
└── requirements.txt          # Dependencies (sẽ tạo)
```

## 💻 Yêu Cầu Hệ Thống

- **Python**: 3.7 trở lên
- **Jupyter Notebook** hoặc **Google Colab**
- **RAM**: Tối thiểu 4GB (khuyến nghị 8GB+)
- **Hệ điều hành**: Windows, macOS, hoặc Linux

## 🔧 Cài Đặt

### 1. Clone Repository

```bash
git clone https://github.com/yourusername/tu-hoc-machine-learning.git
cd tu-hoc-machine-learning
```

### 2. Tạo Virtual Environment (Khuyến nghị)

**Windows:**
```bash
python -m venv venv
venv\Scripts\activate
```

**macOS/Linux:**
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Cài Đặt Dependencies

```bash
pip install -r requirements.txt
```

### 4. Khởi Động Jupyter Notebook

```bash
jupyter notebook
```

## 📖 Nội Dung Học

### Buổi 1: Hồi Quy Tuyến Tính (Linear Regression)

**Lý thuyết:**
- Giới thiệu về Machine Learning
- Khái niệm về Hồi quy tuyến tính
- Hàm mất mát (Loss Function)
- Gradient Descent

**Thực hành:**
1. **Hồi quy tuyến tính đơn biến**
   - Dự đoán giá nhà dựa trên diện tích
   - Cài đặt Gradient Descent từ đầu
   - Visualize kết quả và loss function

2. **Hồi quy tuyến tính đa biến**
   - Xây dựng class LinearRegression
   - Huấn luyện với nhiều features
   - Đánh giá mô hình

**Code highlights:**
```python
# Hồi quy đơn biến
y_pred = w * x + b
loss = (1/n) * np.sum((y_pred - y) ** 2)

# Cập nhật tham số
w -= learning_rate * dw
b -= learning_rate * db
```

## 🚀 Cách Sử Dụng

### 1. Mở Notebook

- Điều hướng đến thư mục `BUỔI 1`
- Mở file `Buổi_1.ipynb`
- Chạy từng cell theo thứ tự

### 2. Chạy Code

**Jupyter Notebook:**
- Nhấn `Shift + Enter` để chạy cell hiện tại
- Nhấn `Ctrl + Enter` để chạy mà không chuyển cell

**Google Colab:**
- Upload notebook lên Colab
- Chạy từng cell như Jupyter

### 3. Thử Nghiệm

Thay đổi các tham số để quan sát kết quả:
```python
lr = 0.0001      # Learning rate
epochs = 30      # Số vòng lặp
```

## 📊 Kết Quả Mong Đợi

Sau khi hoàn thành Buổi 1, bạn sẽ:

- ✅ Hiểu cách hoạt động của Hồi quy tuyến tính
- ✅ Biết cách cài đặt Gradient Descent
- ✅ Có thể visualize quá trình học của mô hình
- ✅ Xây dựng được class LinearRegression từ đầu

### Ví dụ Output:

```
Epoch 0: Loss = 167299.40, w = 6.5674, b = 0.0764
Epoch 5: Loss = 126.69, w = 5.0873, b = 0.0591
Epoch 29: Loss = 125.98, w = 5.0903, b = 0.0590

Kết quả cuối cùng:
w = 5.0903, b = 0.0590
```

## 📚 Tài Liệu Tham Khảo

### Sách
- **"Hands-On Machine Learning"** - Aurélien Géron
- **"Pattern Recognition and Machine Learning"** - Christopher Bishop
- **"Deep Learning"** - Ian Goodfellow

### Online Courses
- [Coursera - Machine Learning by Andrew Ng](https://www.coursera.org/learn/machine-learning)
- [Fast.ai](https://www.fast.ai/)
- [Google's Machine Learning Crash Course](https://developers.google.com/machine-learning/crash-course)

### Websites
- [Towards Data Science](https://towardsdatascience.com/)
- [Machine Learning Mastery](https://machinelearningmastery.com/)
- [Kaggle Learn](https://www.kaggle.com/learn)

## 🤝 Đóng Góp

Mọi đóng góp đều được hoan nghênh! Để đóng góp:

1. Fork repository
2. Tạo branch mới (`git checkout -b feature/AmazingFeature`)
3. Commit thay đổi (`git commit -m 'Add some AmazingFeature'`)
4. Push lên branch (`git push origin feature/AmazingFeature`)
5. Tạo Pull Request

### Các loại đóng góp:
- 🐛 Báo lỗi (Bug reports)
- 💡 Đề xuất tính năng (Feature requests)
- 📝 Cải thiện tài liệu (Documentation)
- ✨ Code mới (New code)

## 📝 License

Dự án này được phân phối dưới giấy phép MIT. Xem file `LICENSE` để biết thêm chi tiết.

## 👥 Tác Giả & Liên Hệ

**Tên:** [Tên của bạn]
- 📧 Email: your.email@example.com
- 💼 LinkedIn: [Your LinkedIn Profile]
- 🐙 GitHub: [@yourusername](https://github.com/yourusername)

## 🙏 Lời Cảm Ơn

Cảm ơn tất cả những nguồn tài liệu và cộng đồng Machine Learning đã chia sẻ kiến thức.

## ⭐ Star History

Nếu repository này hữu ích với bạn, đừng quên cho một star! ⭐

---

**Happy Learning! 🎓📊🤖**

## 📅 Lộ Trình Học Tập Dự Kiến

- [x] **Buổi 1**: Hồi quy tuyến tính cơ bản
- [ ] **Buổi 2**: Hồi quy logistic và phân loại
- [ ] **Buổi 3**: Decision Trees và Random Forest
- [ ] **Buổi 4**: Support Vector Machines (SVM)
- [ ] **Buổi 5**: Neural Networks cơ bản
- [ ] **Buổi 6**: Deep Learning
- [ ] **Buổi 7**: Xử lý ngôn ngữ tự nhiên (NLP)
- [ ] **Buổi 8**: Computer Vision
- [ ] **Buổi 9**: Dự án thực tế

## 🔗 Quick Links

- [Jupyter Notebook Cheatsheet](https://www.datacamp.com/cheat-sheet/jupyter-notebook-cheat-sheet)
- [Python Cheatsheet](https://www.pythoncheatsheet.org/)
- [NumPy Documentation](https://numpy.org/doc/)
- [Matplotlib Documentation](https://matplotlib.org/stable/index.html)

---

<div align="center">
  Made with ❤️ for Machine Learning Learners
</div>

