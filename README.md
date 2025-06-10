# 📋 Task Management - Hệ thống Quản lý Công việc

Một ứng dụng web quản lý công việc được xây dựng bằng Node.js và Express.js, giúp bạn tổ chức và theo dõi các nhiệm vụ một cách hiệu quả.

## 🌟 Tính năng

- ✅ Tạo, chỉnh sửa và xóa công việc
- 📊 Theo dõi trạng thái công việc
- 🔔 Gửi email thông báo
- 💾 Lưu trữ dữ liệu với MongoDB
- 🚀 Giao diện web thân thiện
- 📱 Responsive design

## 🛠️ Công nghệ sử dụng

- **Backend**: Node.js, Express.js
- **Cơ sở dữ liệu**: MongoDB với Mongoose
- **Email**: Nodemailer
- **Bảo mật**: MD5 hash
- **CORS**: Hỗ trợ cross-origin requests
- **Dev tools**: Nodemon

## 🚀 Demo

Xem demo tại: [https://task-management-omega-ten.vercel.app](https://task-management-omega-ten.vercel.app)

## 📦 Cài đặt

### Yêu cầu hệ thống
- Node.js (phiên bản 14 trở lên)
- MongoDB
- npm hoặc yarn

### Các bước cài đặt

1. **Clone repository**
```bash
git clone https://github.com/QuyDatSadBoy/Task-Management.git
cd Task-Management
```

2. **Cài đặt dependencies**
```bash
npm install
```

3. **Cấu hình môi trường**
Tạo file `.env` trong thư mục gốc và thêm các biến môi trường:
```env
PORT=3000
MONGODB_URI=mongodb://localhost:27017/task_management
EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_app_password
```

4. **Khởi chạy ứng dụng**
```bash
# Chế độ development
npm start

# Hoặc chạy trực tiếp
node index.js
```

5. **Truy cập ứng dụng**
Mở trình duyệt và truy cập: `http://localhost:3000`

## 📁 Cấu trúc dự án

```
Task-Management/
├── index.js              # File chính của ứng dụng
├── package.json          # Thông tin dự án và dependencies
├── .env                  # Biến môi trường (cần tạo)
├── models/               # Models cho MongoDB
├── routes/               # Định tuyến API
├── controllers/          # Logic xử lý
├── middleware/           # Middleware functions
├── public/               # Static files
└── views/                # Template files
```

## 🔧 Scripts

```bash
# Khởi chạy server với nodemon (auto-reload)
npm start

# Chạy tests
npm test
```

## 🌐 API Endpoints

| Method | Endpoint | Mô tả |
|--------|----------|-------|
| GET | `/api/tasks` | Lấy danh sách tất cả công việc |
| POST | `/api/tasks` | Tạo công việc mới |
| PUT | `/api/tasks/:id` | Cập nhật công việc |
| DELETE | `/api/tasks/:id` | Xóa công việc |
| POST | `/api/auth/login` | Đăng nhập |
| POST | `/api/auth/register` | Đăng ký |

## 📧 Cấu hình Email

Để sử dụng tính năng gửi email, bạn cần:

1. Bật 2-Factor Authentication cho Gmail
2. Tạo App Password
3. Cập nhật file `.env` với thông tin email

## 🤝 Đóng góp

1. Fork dự án
2. Tạo feature branch (`git checkout -b feature/TinhNangMoi`)
3. Commit thay đổi (`git commit -m 'Thêm tính năng mới'`)
4. Push lên branch (`git push origin feature/TinhNangMoi`)
5. Tạo Pull Request

## 📄 License

Dự án này sử dụng license ISC. Xem file [LICENSE](LICENSE) để biết thêm chi tiết.

## 👨‍💻 Tác giả

**QuyDatSadBoy**
- GitHub: [@QuyDatSadBoy](https://github.com/QuyDatSadBoy)
- Website: [Task Management Demo](https://task-management-omega-ten.vercel.app)

## 🐛 Báo lỗi

Nếu bạn gặp lỗi hoặc có đề xuất, vui lòng tạo issue tại [GitHub Issues](https://github.com/QuyDatSadBoy/Task-Management/issues).

## 📊 Thống kê

![GitHub stars](https://img.shields.io/github/stars/QuyDatSadBoy/Task-Management?style=social)
![GitHub forks](https://img.shields.io/github/forks/QuyDatSadBoy/Task-Management?style=social)
![GitHub issues](https://img.shields.io/github/issues/QuyDatSadBoy/Task-Management)

---

⭐ Nếu dự án này hữu ích với bạn, hãy cho một star nhé!
