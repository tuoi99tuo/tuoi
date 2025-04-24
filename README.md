# 🌸 Ghibli Video Web App

Website chuyển đổi video thành phong cách Ghibli. Tính năng chính:
- Tải video gốc
- Chuyển đổi sang phong cách hoạt hình Ghibli
- Lưu lịch sử video theo người dùng

## 🚀 Cài đặt

### 1. Clone Repo
```bash
git clone https://github.com/your-username/ghibli-video-web.git
cd ghibli-video-web
```

### 2. Cài đặt thư viện
```bash
npm install
```

### 3. Tạo file `.env.local`
```bash
cp .env.example .env.local
```

### 4. Khởi chạy local
```bash
npm run dev
```

### 5. Deploy lên Vercel
- Push repo lên GitHub
- Truy cập [https://vercel.com](https://vercel.com)
- Kết nối GitHub và chọn repo
- Thêm biến môi trường từ `.env.local`
- Deploy!

## 📌 Lưu ý
- File `data/video-history.json` chỉ dùng để demo, không phù hợp cho môi trường production
- Bạn nên dùng MongoDB, Firebase hoặc Supabase để lưu dữ liệu lâu dài

---
✨ Dự án demo dành cho trải nghiệm cá nhân. Bạn có thể tùy biến hoặc thương mại hóa nếu muốn.