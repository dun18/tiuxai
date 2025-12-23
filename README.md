# 🎮 Bot Dự Đoán Tài Xỉu (Demo Frontend)

> ⚠️ **Lưu ý quan trọng:**  
> Dự án này **chỉ mang tính demo / học tập / giao diện hiển thị**.  
> **KHÔNG phải tool hack game, KHÔNG đảm bảo thắng, KHÔNG can thiệp server.**

---

## ✨ Giới thiệu

Đây là một **web app thuần HTML/CSS/JavaScript** dùng để:
- Hiển thị **dự đoán Tài / Xỉu** từ các API bên ngoài
- Mô phỏng giao diện **bot dự đoán** với hiệu ứng trực quan
- Phù hợp cho:
  - Học frontend
  - Demo UI/UX
  - Vọc code cho vui 😄

---

## 🕹️ Nền tảng hỗ trợ

- SunWin  
- HitClub  
- B52  
- 789 Club  

> ⚠️ Dữ liệu dự đoán **đến từ API bên ngoài**, không phải do thuật toán trong code tự tính.

---

## 🔐 Hệ thống Key truy cập

Trang web có **popup nhập key** trước khi vào trang chính.

- ✔ Key đúng: `duongbuncha01`
- ✔ Hash SHA-256 (không lộ key plain)
- ✔ Nhập 1 lần → nhớ bằng `localStorage`
- ✔ Sai 5 lần → khóa 30 giây

👉 Mục đích: **lọc người dùng & tăng trải nghiệm**, không phải bảo mật tuyệt đối.

---

## 🧠 Cơ chế hoạt động (nói thẳng)

- ❌ Không AI
- ❌ Không machine learning
- ❌ Không đọc dữ liệu server game
- ✅ Chỉ:
  - Fetch API
  - Hiển thị dự đoán
  - So kết quả → thống kê thắng/thua

👉 **Đây là “bảng hiển thị dữ liệu”, không phải công cụ dự đoán thật.**

---

## 🛠️ Công nghệ sử dụng

- HTML5
- CSS3 (Glassmorphism, Neon UI)
- Vanilla JavaScript
- `particles.js`
- `localStorage`
- Fetch API + Proxy fallback

---

## 🚀 Cách chạy

### 1️⃣ Chạy local
```bash
# chỉ cần mở file
index.html
