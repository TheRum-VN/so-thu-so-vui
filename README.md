<div align="center">

# 🦁 Sở Thú Số Vui (Little Number Zoo) 🐘

**Trò chơi giáo dục tương tác giúp trẻ mầm non (3–5 tuổi) làm quen với con số và toán học cơ bản qua hành trình khám phá sở thú đầy màu sắc!**

[![Chơi Ngay](https://img.shields.io/badge/🎮_Chơi_Trực_Tuyến-Live_Demo-2ea44f?style=for-the-badge)](https://therum-vn.github.io/so-thu-so-vui/)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github)](https://github.com/TheRum-VN/so-thu-so-vui)
[![React 19](https://img.shields.io/badge/React-19.0-61DAFB?style=for-the-badge&logo=react&logoColor=black)](https://react.dev/)
[![Vite 7](https://img.shields.io/badge/Vite-7.0-646CFF?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
[![Electron](https://img.shields.io/badge/Electron-39.8-47848F?style=for-the-badge&logo=electron&logoColor=white)](https://www.electronjs.org/)

</div>

---

## 📖 Giới thiệu

**Sở Thú Số Vui** (`little-number-zoo` — App ID: `vn.sothusovui.mathgames`) là sản phẩm giáo dục số được thiết kế chuyên biệt cho trẻ mầm non từ **3 đến 5 tuổi**. Đồng hành cùng bạn **Thỏ Bông** đáng yêu và những người bạn động vật ngộ nghĩnh, các bé sẽ tham gia vào 6 khu vực trò chơi nhỏ để rèn luyện kỹ năng đếm số, so sánh số lượng, sắp xếp dãy số và nhận biết nhóm đối tượng trong phạm vi từ **1 đến 10**.

Trò chơi hỗ trợ đa nền tảng: hoạt động mượt mà trực tiếp trên **Trình duyệt Web** và có thể đóng gói thành **Ứng dụng Máy tính Windows (Bộ cài đặt NSIS & Bản chạy ngay Portable)** thông qua Electron.

🔗 **Trải nghiệm trực tiếp trên Web:** [https://therum-vn.github.io/so-thu-so-vui/](https://therum-vn.github.io/so-thu-so-vui/)

---

## 🗺️ 6 Khu vực khám phá trong Sở Thú

Mỗi khu vực trên bản đồ bao gồm **3 vòng nhiệm vụ** liên tiếp. Hoàn thành cả 3 nhiệm vụ, bé sẽ được vinh danh trên màn hình pháo giấy và nhận ngay **3 ngôi sao (★)** vào bộ sưu tập:

1. 🦆 **Hồ Vịt Con (`ducks`):**
   - Bé chạm trực tiếp vào từng chú vịt đang bơi trên hồ sen để nghe phát âm đếm số thứ tự (`một`, `hai`, `ba`...) và chọn thẻ số màu sắc tương ứng.
2. 🐻 **Dã Ngoại Nhà Gấu (`bears`):**
   - Quan sát các giỏ táo trên bàn tiệc picnic của Gấu và tìm ra giỏ có số lượng quả **nhiều hơn** hoặc **ít hơn** theo yêu cầu.
3. 🥭 **Vườn Xoài Của Thỏ Bông (`apples`):**
   - Xem biển báo số lượng mục tiêu, sau đó **kéo thả** hoặc **chạm** vào từng quả xoài chín vàng trên cây để thu hoạch đúng số quả vào giỏ.
4. 🐒 **Xếp Số Cùng Khỉ Con (`monkeys`):**
   - Giúp bạn Khỉ chọn các thẻ số bị xáo trộn để xếp lần lượt lên 3 bậc gỗ theo đúng thứ tự dãy số.
5. 🐘 **Khu Vườn Voi Con (`elephants`):**
   - Tham gia các hoạt động chăm sóc và tương tác sinh động trong khu vườn cùng Voi Con (`GardenGame`).
6. 🎉 **Lễ Hội Sở Thú (`festival`):**
   - Quan sát và chọn nhóm đối tượng (đàn vịt hoặc nhóm quả táo) có số lượng khớp với yêu cầu của lễ hội.

---

## ✨ Tính năng nổi bật

- 🗣️ **Thuyết minh giọng đọc Tiếng Việt tự động:** Tích hợp Web Speech API (`SpeechSynthesis`), tự động nhận diện giọng Tiếng Việt (`vi-VN`) trên thiết bị để đọc to câu hỏi, hướng dẫn và đếm từng số cùng bé.
- 👩‍🏫 **Góc Giáo Viên & Phụ Huynh chuyên biệt:**
  - Tuỳ chỉnh độ tuổi của bé (**3, 4 hoặc 5 tuổi**) để hệ thống tự động điều chỉnh phạm vi con số phù hợp (`1 – max`).
  - Bật/tắt độc lập: **Âm thanh hiệu ứng**, **Nhạc nền vui nhộn** và **Giọng đọc tiếng Việt**.
  - Theo dõi tổng số ngôi sao bé đã đạt được và hỗ trợ đặt lại tiến độ để bắt đầu hành trình mới.
- 🎵 **Hệ thống âm thanh sống động (`ZooAudio`):** Nhạc nền tự động tạm dừng khi ẩn tab trình duyệt và phát lại khi quay lại; hiệu ứng âm thanh riêng cho từng thao tác chạm, tiếng vịt kêu, thả quả vào giỏ và nhận thưởng.
- 💾 **Lưu tiến độ tự động:** Mọi thiết lập độ tuổi, âm thanh và số sao tích luỹ đều được lưu trực tiếp trên thiết bị thông qua `localStorage`.
- 🖥️ **Hỗ trợ đa thiết bị & Accessibility:** Chế độ toàn màn hình (Fullscreen), nhắc xoay ngang màn hình trên thiết bị di động, hỗ trợ điều hướng bàn phím và trình đọc màn hình (`aria-label`).

---

## 🛠️ Công nghệ sử dụng

| Thành phần | Công nghệ / Thư viện | Phiên bản |
| :--- | :--- | :--- |
| **Giao diện (UI Library)** | React & React DOM | `^19.0.0` |
| **Biểu tượng (Icons)** | Phosphor Icons (`@phosphor-icons/react`) | `^2.1.7` |
| **Công cụ Build Web** | Vite + `@vitejs/plugin-react` | `^7.0.0` |
| **Ứng dụng Desktop** | Electron & Electron Builder | `^39.8.10` / `^26.15.3` |
| **Kiểm thử tự động (E2E)** | Playwright (`@playwright/test`) | `^1.56.0` |
| **Quản lý tài nguyên** | Python Scripts (`tools/*.py`) | Python 3.x |

---

## 🚀 Hướng dẫn cài đặt và chạy dự án

### 1. Yêu cầu hệ thống
- **Node.js:** Phiên bản 18.x trở lên (khuyến nghị Node 20+).
- **Python 3:** (Tùy chọn) Dùng để chạy các script xử lý hình ảnh, âm thanh và tạo icon (`tools/*.py`).

### 2. Cài đặt và chạy bản Web (Development)

```bash
# Bước 1: Clone repository về máy
git clone https://github.com/TheRum-VN/so-thu-so-vui.git

# Bước 2: Di chuyển vào thư mục dự án
cd so-thu-so-vui

# Bước 3: Cài đặt các gói phụ thuộc
npm install

# Bước 4: Khởi chạy máy chủ phát triển (mở trên toàn mạng LAN 0.0.0.0)
npm run dev
```

### 3. Các lệnh (Scripts) có sẵn trong dự án

| Lệnh | Mô tả chức năng |
| :--- | :--- |
| `npm run dev` | Chạy server phát triển Vite (`--host 0.0.0.0`). |
| `npm run build` | Đóng gói bản Web tối ưu ra thư mục `dist/`. |
| `npm run preview` | Xem thử bản Web đã build trên máy cục bộ. |
| `npm run desktop` | Tạo icon, build web và khởi chạy trực tiếp ứng dụng trên cửa sổ **Electron**. |
| `npm run dist:win` | Đóng gói bộ cài đặt Windows `.exe` (**NSIS Setup** & **Portable x64**) vào thư mục `release/`. |
| `npm test` | Chạy bộ kiểm thử tự động với **Playwright**. |
| `npm run assets:audit` | Kiểm tra tính toàn vẹn của tài nguyên đồ họa bằng Python (`tools/audit_assets.py`). |
| `npm run assets:prepare` | Chuẩn bị và tối ưu hóa tài nguyên bằng Python (`tools/prepare_assets.py`). |
| `npm run icon:create` | Tạo file biểu tượng `build/icon.ico` cho ứng dụng Windows (`tools/create_icon.py`). |

---

## 📂 Cấu trúc dự án

```text
so-thu-so-vui/
├── build/                      # Chứa icon ứng dụng (icon.ico) khi đóng gói
├── dist/                       # Thư mục đầu ra khi build bản Web
├── electron/                   # Cấu hình tiến trình chính Electron (main.cjs)
├── release/                    # Chứa file cài đặt Windows (.exe NSIS & Portable)
├── src/                        # Mã nguồn chính của trò chơi
│   ├── main.jsx                # Component trung tâm điều phối màn hình và vòng chơi
│   ├── GardenGame.jsx          # Chế độ chơi Khu Vườn Voi Con
│   ├── HarvestMango.jsx        # Component xử lý kéo thả và hái xoài
│   ├── Art.jsx                 # Component hiển thị tài nguyên hình ảnh
│   ├── assets.js               # Danh mục đường dẫn hình ảnh và cấu hình 6 khu vực
│   ├── audio.js                # Bộ điều khiển âm thanh và nhạc nền (ZooAudio)
│   ├── questions.js            # Thuật toán sinh câu hỏi theo từng độ tuổi (3-5 tuổi)
│   ├── style.css               # Giao diện và bố cục chính
│   └── refinements.css         # Hiệu ứng chuyển động và tinh chỉnh UI
├── tools/                      # Các script Python & Node.js hỗ trợ build Electron và xử lý asset
└── package.json                # Cấu hình dự án, scripts và electron-builder
```

---

## 👨‍🏫 Tác giả & Ghi công

- **Phát triển mã nguồn:** [TheRum-VN](https://github.com/TheRum-VN)
- **Hỗ trợ sản phẩm giáo dục số:** [Thầy Thành (Vũ Duy Thành)](https://web.facebook.com/vuduythanh.1205)

---

<div align="center">
  <i>🌟 Chúc các bé có những giờ phút vừa chơi vừa học thật vui tại Sở Thú Số Vui! 🌟</i>
</div>
