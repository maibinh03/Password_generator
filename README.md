# 🔐 Password Generator

Một chương trình tạo mật khẩu ngẫu nhiên bằng Python, kết hợp chữ cái, chữ số và ký tự đặc biệt.  
Mật khẩu được tạo bằng module `secrets`, phù hợp hơn cho các ứng dụng liên quan đến bảo mật so với bộ sinh số ngẫu nhiên thông thường.

## ✨ Features

- **Random Generation:** Tạo mật khẩu với độ dài tùy chỉnh.  
- **Character Variety:** Kết hợp chữ hoa, chữ thường, chữ số và ký tự đặc biệt.  
- **Password Strength:** Đảm bảo mật khẩu có ít nhất 2 chữ số và 1 ký tự đặc biệt.  
- **Secure Randomness:** Sử dụng `secrets.choice()` để lựa chọn ký tự ngẫu nhiên an toàn.  

## 🛠 Tech Stack

**Python** – Sử dụng các standard libraries `string` để quản lý tập ký tự và `secrets` để tạo mật khẩu ngẫu nhiên an toàn.

## 🚀 Getting Started

Không cần cài đặt thư viện bên ngoài. Chạy chương trình bằng:

```bash
python main.py
```

Mặc định chương trình tạo mật khẩu dài 12 ký tự. Có thể thay đổi độ dài thông qua tham số `gen_pw(length)`.

## 💡 What I Learned

Thông qua dự án này, mình thực hành sử dụng Python standard libraries, xử lý chuỗi, vòng lặp và kiểm tra điều kiện để đảm bảo mật khẩu đáp ứng các yêu cầu về độ phức tạp.
