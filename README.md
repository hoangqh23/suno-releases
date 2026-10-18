# Suno Studio Releases

Kênh phân phối và cập nhật ứng dụng chính thức của **Suno Studio** (Android Native).

### Bản phát hành mới nhất: [v0.5.11](https://github.com/hoangqh23/suno-releases/releases/tag/v0.5.11)
- 🚀 **[Tải Bản Cài Đè Không Gỡ (Khuyên Dùng)](https://github.com/hoangqh23/suno-releases/releases/download/v0.5.11/SunoUpload-0.5.11-inplace-update.apk)**
- 📦 **[Tải Bản Official Release (Ký Chuẩn)](https://github.com/hoangqh23/suno-releases/releases/download/v0.5.11/SunoUpload-0.5.11-official-release.apk)**

### Nhật ký thay đổi (Changelog):
• Khắc phục triệt để lỗi 'Permission denied [Errno 13]' trên Android 10, 11, 12, 13, 14, 15 khi tải nhạc YouTube/Suno qua yt-dlp.
• Cơ chế lưu trữ 3 tầng Scoped Storage an toàn: Tự động staging qua cacheDir nội bộ và commit ra MediaStore.Downloads (Tải về/SunoMusic) không cần cấp quyền đặc quyền.
• Bổ sung tham số trích xuất youtube:player_client=android,web vượt qua cơ chế giới hạn SABR streaming từ máy chủ YouTube.
• Tự động tải ngầm và nạp sẵn lõi yt-dlp/ffmpeg ngay từ khi mở app, thao tác phân tích và tải tức thì không có độ trễ.
