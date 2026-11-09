# 🔒 Lockgold - Filter AI
> **Shadowrocket Module** — Mở khóa Locket Gold + AI Filters  
> **Phân phối:** Hakaiz | **Tác giả:** dinhtuan07

---

## 📋 Tính năng

| Tính năng | Trạng thái |
|---|---|
| ✅ Locket Gold (không giới hạn) | Hoạt động |
| ✅ Video 45 giây | Hoạt động |
| ✅ Upload từ Camera Roll | Hoạt động |
| ✅ Bộ lọc AI (AI Filters) | Hoạt động |
| ✅ Photobooth 4-ô liên hoàn | Hoạt động |
| ✅ Huy hiệu Gold Profile | Hoạt động |
| ✅ Mạng lưới bạn bè VIP | Hoạt động |
| ✅ Tắt quảng cáo | Hoạt động |
| ✅ Tắt Sentry tracking | Hoạt động |

---

## 📥 Cách cài đặt (Shadowrocket)

### Bước 1: Thêm Config URL
Mở **Shadowrocket** → Tab **Config** → Nhấn `+` → Dán URL:

```
https://raw.githubusercontent.com/huanhoahongso3-collab/Locket-Filter-Module/main/Lockgold-Filter-AI.conf
```

### Bước 2: Bật HTTPS Decryption (MITM)
1. Vào **Config** → Chọn config vừa import → `i`
2. Bật **HTTPS Decryption**
3. Nhấn **Generate New CA Certificate**
4. Vào `Settings (iOS) → General → VPN & Device Management` → Trust certificate

### Bước 3: Bật Shadowrocket
- Bật VPN switch → Mở Locket → Tận hưởng Gold! 🎉

---

## 🗂️ Cấu trúc repo

```
Locket-Filter-Module/
├── Lockgold-Filter-AI.conf       ← File config chính (import vào Shadowrocket)
├── js/
│   ├── deleteHeader_Firebase.js  ← Xóa cache headers Firebase
│   ├── deleteHeader_RC.js        ← Xóa cache headers RevenueCat
│   ├── revenuecat.js             ← Giả lập subscription Gold
│   ├── locketfix.js              ← Mở khóa Firebase Remote Config
│   ├── locket_pb_req.js          ← Photobooth Engine & AI Filter
│   ├── locket_change_profile.js  ← Huy hiệu Profile Gold
│   └── locket_filter_resp.js     ← Mở khóa toàn bộ response API
└── README.md
```

---

## ⚠️ Lưu ý

- Chỉ dùng cho mục đích **học tập, nghiên cứu**
- Không bán hoặc phân phối lại dưới tên khác
- Yêu cầu Shadowrocket trên iOS

---

## 📞 Liên hệ

> **Hakaiz** — by dinhtuan07
