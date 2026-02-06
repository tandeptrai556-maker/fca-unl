
-   🔄 **Tự Động Đăng Nhập:** Khi `appState` hết hạn hoặc tài khoản bị đăng xuất, bot sẽ tự động đăng nhập lại bằng email, mật khẩu và mã 2FA.
-   🛡️ **Xử Lý Checkpoint:** Tự động gửi cảnh báo khi tài khoản bị checkpoint và hỗ trợ quá trình khôi phục.
-   💾 **Tự Động Lưu `appState`:** Sau mỗi lần đăng nhập thành công, `appState` mới sẽ được tự động lưu lại để sử dụng cho các phiên tiếp theo.
-   ⚡ **Tự Động Khởi Động Lại:** Khi mất kết nối hoặc gặp lỗi, bot sẽ tự khởi động lại mà không cần can thiệp thủ công.

---

## 📂 Cấu Trúc Thư Mục Dự Án

```yaml
/filebot
├── fca-autologin/              # Thư viện FCA-HZI (Horizon)
├── main.js          # File khởi động bot
├── FastConfigFca.json       # File cấu hình (bao gồm bật/tắt AutoLogin)
└── appstate.json     # File appState được lưu và cập nhật tự động
