# 🏥 **HealthCare**

**HealthCare** là một ứng dụng web hiện đại hỗ trợ quản lý hồ sơ bệnh nhân, lịch hẹn, và theo dõi sức khỏe. Ứng dụng được xây dựng với **React, Vite, TypeScript, Redux Toolkit, RTK Query, React Hook Form, Yup, ShadCN UI, Tailwind CSS, và Lucide React**, mang lại hiệu suất cao, UI thân thiện và dễ bảo trì.

---

## 🚀 **Công nghệ sử dụng**

- **⚛️ React + Vite** – Frontend nhanh, nhẹ, tối ưu.
- **📌 TypeScript** – Kiểm soát kiểu chặt chẽ, giúp code an toàn hơn.
- **📦 Redux Toolkit + RTK Query** – Quản lý state và gọi API tối ưu.
- **📋 React Hook Form + Yup** – Xử lý form hiệu quả và dễ dàng validate.
- **🎨 ShadCN UI + Tailwind CSS** – Giao diện hiện đại, đẹp mắt.
- **🔍 Lucide React** – Bộ icon nhẹ, dễ sử dụng.

---

## 📂 **Cấu trúc dự án**

```
/src
 ├── components/      # Component UI tái sử dụng
 ├── features/        # Chức năng chính của ứng dụng
 ├── hooks/           # Custom hooks
 ├── layouts/         # Layout (Header, Sidebar, Footer)
 ├── pages/           # Các trang chính (Dashboard, Profile, Appointments)
 ├── redux/           # Quản lý state với Redux Toolkit
 ├── types/           # Kiểu dữ liệu TypeScript
 ├── utils/           # Hàm tiện ích
 ├── App.tsx          # Component gốc
 ├── main.tsx         # Entry point của ứng dụng
```

---

## 📌 **Chức năng chính**

### 🩺 **Quản lý hồ sơ bệnh nhân**

- Lưu trữ thông tin cá nhân, tiền sử bệnh
- Theo dõi chỉ số sức khỏe: chiều cao, cân nặng, nhóm máu
- Quản lý tiền sử bệnh: dị ứng, bệnh mãn tính, tiền sử gia đình
- Thông tin lối sống: hút thuốc, uống rượu, tập thể dục, chế độ ăn

### 📅 **Đặt lịch khám và tư vấn**

- Đặt lịch khám với bác sĩ chuyên khoa
- Hỗ trợ tư vấn trực tuyến qua video call
- Đặt lịch tái khám tự động
- Mua gói dịch vụ khám bệnh với nhiều ưu đãi

### 🏥 **Các chuyên khoa y tế**

- Tim Mạch
- Nội Tổng Hợp
- Thần Kinh
- Nhãn Khoa
- Miễn Dịch & Dị Ứng
- Nhi Khoa

### 📱 **Theo dõi sức khỏe thông minh**

- Thống kê số lần khám đã sử dụng và còn lại
- Theo dõi lịch sử khám bệnh
- Đánh giá bác sĩ sau mỗi lần khám
- Nhận thông báo nhắc lịch hẹn

### 🔒 **Bảo mật thông tin**

- Hệ thống xác thực người dùng an toàn
- Bảo mật thông tin y tế cá nhân
- Quản lý quyền truy cập riêng biệt cho bệnh nhân và quản trị viên

---

## 🔄 **Quy trình sử dụng**

1. **Đặt lịch khám** - Chọn bác sĩ chuyên khoa phù hợp và đặt lịch khám trực tuyến
2. **Tư vấn trực tuyến** - Kết nối video call an toàn với bác sĩ
3. **Nhận chẩn đoán** - Tư vấn, chẩn đoán và phương pháp điều trị
4. **Tái khám** - Đặt lịch tái khám theo dõi sức khỏe định kỳ

---

## ⚡ **Cài đặt và chạy dự án**

```bash
# 1. Clone dự án
git clone https://github.com/thienmdp/healthcare.git

# 2. Cài đặt dependencies
cd healthcare
npm install

# 3. Chạy ứng dụng
npm run dev
```

Ứng dụng sẽ chạy tại **http://localhost:5173** 🚀

---

## 📝 **Hướng dẫn Commit**

Dự án sử dụng commitlint để chuẩn hóa commit message. Commit message phải tuân theo format:

```bash
type(scope): subject

# Ví dụ:
git commit -m "feat(auth): add login with google"
git commit -m "fix(ui): correct button alignment"
```

Các type hợp lệ:

- `feat`: Thêm tính năng mới
- `fix`: Sửa lỗi
- `docs`: Thay đổi tài liệu
- `style`: Thay đổi style/format code
- `refactor`: Tái cấu trúc code
- `test`: Thêm/sửa test
- `chore`: Thay đổi build process, cài đặt package

Nếu gặp vấn đề với commitlint, hãy thử:

```bash
npm uninstall husky
npm install -D husky
npm run prepare
npx husky add .husky/commit-msg "npx --no -- commitlint --edit $1"
```

---

## 🎯 **Liên hệ & Đóng góp**

Mọi đóng góp để cải thiện HealthCare đều được hoan nghênh! Hãy tạo **pull request** hoặc **issue** trên GitHub. 💙
