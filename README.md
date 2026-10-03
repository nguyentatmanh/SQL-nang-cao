# 🎓 Hệ Thống Ôn Thi Trắc Nghiệm Cơ Sở Dữ Liệu Nâng Cao (SQL Server & T-SQL)

> **Hệ thống web-app ôn luyện và thi thử trắc nghiệm 120 câu hỏi môn Cơ sở dữ liệu nâng cao (Advanced Database) với giao diện hiện đại, âm thanh sống động, tài liệu đính kèm và tối ưu đa thiết bị.**

---

### 👤 Thông Tin Tác Giả
* **Tác giả:** **Nguyễn Tất Mạnh**
* **GitHub Repository:** [nguyentatmanh/SQL-nang-cao](https://github.com/nguyentatmanh/SQL-nang-cao)
* **Demo trực tuyến (Live App):** [https://nguyentatmanh.github.io/SQL-nang-cao/](https://nguyentatmanh.github.io/SQL-nang-cao/)

---

## 🚀 Giới Thiệu Tổng Quan

Dự án được xây dựng nhằm hỗ trợ sinh viên ôn tập và kiểm tra kiến thức môn **Cơ sở dữ liệu nâng cao / SQL Server** một cách trực quan, sinh động và hiệu quả nhất. Toàn bộ 120 câu hỏi được biên soạn và phân loại bám sát ngân hàng đề thi cuối kỳ, tích hợp sẵn slide bài giảng chi tiết cho từng chuyên đề.

Ứng dụng được thiết kế theo chuẩn **Single Page Application (SPA)** hoàn toàn bằng công nghệ thuần (**HTML5, CSS3, Modern JavaScript ES6+**), không phụ thuộc vào thư viện bên ngoài, chạy cực nhanh và có thể sử dụng Offline 100%.

---

## ✨ Tính Năng Nổi Bật

### 1. 🎯 Chế Độ Học & Thi Linh Hoạt
* **Chế độ Luyện tập (Practice Mode):**
  * Hiển thị đáp án đúng/sai ngay lập tức khi người học chọn đáp án.
  * Kèm lời giải thích chi tiết, mã lệnh T-SQL minh họa và **liên kết trỏ đến trang slide tài liệu liên quan**.
* **Chế độ Thi thử (Exam Mode):**
  * Đồng hồ đếm ngược thời gian làm bài (60 phút / 90 phút).
  * Ẩn toàn bộ đáp án và giải thích trong suốt quá trình làm bài.
  * Sau khi bấm **Nộp bài**, hệ thống tự động chấm điểm, xếp loại và mở bảng tổng kết chi tiết từng câu.

### 2. 🔊 Âm Thanh & Hiệu Ứng Trực Quan Sống Động
* **Web Audio API tích hợp:** Tổng hợp âm thanh động trực tiếp từ trình duyệt (click, chọn đáp án đúng `chime`, chọn sai `buzz`, nộp bài thành công). Có nút bật/tắt âm thanh tiện lợi.
* **Micro-interactions:** Hiệu ứng gợn sóng khi nhấp (Ripple Effect), rung lắc phản hồi khi chọn sai (Shake), phóng to êm ái khi hover.
* **Hiệu ứng Pháo hoa (Confetti):** Bắn pháo hoa rực rỡ khi hoàn thành bài thi với kết quả xuất sắc.

### 3. 📱 Tối Ưu Đa Nền Tảng & Đa Thiết Bị (Fully Responsive)
* Hoạt động mượt mà trên mọi kích thước màn hình: **Desktop, Laptop, Tablet và Smartphone**.
* **Cử chỉ vuốt chạm trên thiết bị di động (Touch Swipe):** Vuốt sang trái để chuyển câu tiếp theo, vuốt sang phải để quay lại câu trước.
* **Thanh điều hướng dưới đáy (Mobile Bottom Bar):** Dễ dàng thao tác chuyển câu hoặc mở bảng danh sách bằng một tay trên điện thoại.
* **Nút cuộn nhanh lên đầu trang (Scroll-to-top):** Tiện lợi khi đọc các câu hỏi dài.

### 4. 📚 Trình Đọc Slide & Tài Liệu Thông Minh (In-App PDF.js Mobile Viewer)
* Tích hợp công cụ **Mozilla PDF.js** kết xuất slide sắc nét chuẩn Retina / High-DPI trực tiếp trên HTML5 Canvas:
  * **Trượt lướt mượt mà trên điện thoại di động:** Hỗ trợ cử chỉ vuốt chạm (Touch Swipe) sang trái/phải để chuyển slide trực tiếp mà không cần mở tab mới.
  * **Thanh điều khiển đầy đủ:** Nút lùi/tiến slide, ô nhập trang trực tiếp, phóng to thu nhỏ (`➕` / `➖`), nút căn vừa khít màn hình (`↔ Vừa khít`), và chuyển đổi chế độ xem (Lướt từng slide hoặc Cuộn dọc).
  * **Tương thích toàn diện:** Khắc phục triệt để lỗi không cuộn được của thẻ iframe trên iOS Safari và Android Chrome.
* Tích hợp sẵn 7 bộ tài liệu, slide bài giảng và đề ôn tập:
  * Slide Bài 1: Tổng quan RDBMS & Kiến trúc SQL Server.
  * Slide Bài 2: Biến, Kiểu dữ liệu & Cấu trúc điều khiển T-SQL.
  * Slide Bài 3: Hàm tích hợp (Built-in Functions) & BATCH.
  * Slide Bài 4: Stored Procedures & Quản lý Giao dịch (Transactions).
  * Slide Bài 5: Hàm người dùng định nghĩa (UDFs), Views & Triggers.
  * Đề cương & Đề ôn tập cuối kỳ HUCE.
* Hỗ trợ **xem trực tiếp bằng canvas trong modal**, **mở tab mới bằng trình đọc của máy**, **tải về** hoặc **tải lên file PDF cá nhân**.

### 5. ⚡ Tiện Ích Hỗ Trợ Học Tập
* **Tìm kiếm câu hỏi siêu tốc (`Ctrl + K`):** Tìm kiếm tức thì theo từ khóa, nội dung câu hỏi hoặc đáp án.
* **Phím tắt bàn phím tiện lợi:**
  * `A`, `B`, `C`, `D`: Chọn đáp án tương ứng.
  * `←` / `→`: Chuyển đổi qua lại giữa các câu hỏi.
  * `Esc`: Đóng các cửa sổ modal tra cứu/tài liệu.
* **Tự động lưu tiến độ:** Lưu bài làm vào `LocalStorage`, không lo mất kết quả khi vô tình tải lại trang.
* **Bộ lọc câu hỏi thông minh:** Lọc theo *Tất cả*, *Chưa làm*, *Đã làm đúng*, *Làm sai*, hoặc *Đã đánh dấu (Bookmark)*.

---

## 📊 Cấu Trúc Ngân Hàng Câu Hỏi (120 Câu)

| Chương | Chủ Đề Trọng Tâm | Nội Dung Chi Tiết |
| :---: | :--- | :--- |
| **01** | **Tổng quan RDBMS & Kiến trúc SQL Server** | Cơ chế lưu trữ, Buffer Pool, Transaction Log, ACID, Data Pages, Extents. |
| **02** | **T-SQL Cơ bản & Luồng Điều khiển** | Khai báo biến, kiểu dữ liệu, `IF...ELSE`, `WHILE`, con trỏ Cursor, `CASE WHEN`. |
| **03** | **Hàm Tích Hợp & Xử Lý Lô (Batch)** | Các hàm chuỗi, ngày tháng, toán học, chuyển đổi kiểu (`CAST`, `CONVERT`), lệnh `GO`. |
| **04** | **Stored Procedures & Quản Lý Giao Dịch** | Tham số Input/Output, `TRY...CATCH`, Giao dịch lồng, Isolation Levels, Deadlock. |
| **05** | **UDFs, Views & Triggers** | Hàm vô hướng (Scalar), hàm bảng (Inline/Multi-statement), View nâng cao, DML/DDL Triggers. |

---

## 📁 Cấu Trúc Thư Mục Dự Án

```plaintext
SQL-nang-cao/
├── index.html                           # Giao diện chính phục vụ GitHub Pages
├── OnTap_CuoiKy_SQL_NangCao_120Cau.html # File giao diện gốc đầy đủ tính năng
├── OnTap_CuoiKy_SQL_NangCao_120Cau.txt  # Ngân hàng 120 câu hỏi dạng text gốc
├── OnTap_CuoiKy_SQL_NangCao_120Cau.pdf  # Bản PDF ngân hàng câu hỏi
├── adb-lesson-01-20260804080228-e.pdf   # Slide Bài giảng Chương 1
├── adb-lesson-02-20260818082524-e.pdf   # Slide Bài giảng Chương 2
├── adb-lesson-03-20260818082341-e.pdf   # Slide Bài giảng Chương 3
├── adb-lesson-04-20260904093955-e.pdf   # Slide Bài giảng Chương 4
├── adb-lesson-05-20260908070202-e.pdf   # Slide Bài giảng Chương 5
├── Ki?m tra_ Attempt review _ HUCE LMS.pdf # Đề ôn tập kiểm tra trắc nghiệm
└── README.md                            # Tài liệu hướng dẫn dự án
```

---

## 💻 Hướng Dẫn Sử Dụng

### 1. Chạy Trực Tiếp Trên Trình Duyệt (Local)
Không cần cài đặt Node.js hay môi trường web server phức tạp:
1. Tải repository về máy tính:
   ```bash
   git clone https://github.com/nguyentatmanh/SQL-nang-cao.git
   ```
2. Mở thư mục dự án và nhấp đúp vào file `index.html` hoặc `OnTap_CuoiKy_SQL_NangCao_120Cau.html` để mở bằng bất kỳ trình duyệt nào (Chrome, Edge, Firefox, Safari,...).

### 2. Triển Khai (Deploy) Lên GitHub Pages
Dự án đã được cấu hình sẵn sàng cho GitHub Pages:
1. Đẩy mã nguồn lên nhánh `main` của repository GitHub:
   ```bash
   git add .
   git commit -m "feat: cap nhat ung dung"
   git push origin main
   ```
2. Truy cập vào kho lưu trữ trên GitHub: **Settings** > **Pages**.
3. Tại mục **Build and deployment**:
   * **Source**: Chọn `Deploy from a branch`.
   * **Branch**: Chọn `main` và thư mục `/ (root)`.
   * Bấm **Save**.
4. Sau 1 - 2 phút, trang web sẽ được kích hoạt tại:
   `https://nguyentatmanh.github.io/SQL-nang-cao/`

---

## ⌨️ Bảng Phím Tắt Tiện Ích

| Phím Tắt | Chức Năng |
| :---: | :--- |
| `A`, `B`, `C`, `D` | Chọn nhanh phương án trả lời tương ứng |
| `←` (Mũi tên trái) | Chuyển đến câu hỏi phía trước |
| `→` (Mũi tên phải) | Chuyển đến câu hỏi tiếp theo |
| `Ctrl + K` / `Cmd + K` | Mở nhanh thanh tìm kiếm câu hỏi |
| `Esc` | Đóng nhanh modal tài liệu hoặc bảng tìm kiếm |

---

## 📜 Bản Quyền & Giấy Phép

Dự án được xây dựng và chia sẻ vì mục đích học tập phi thương mại.  
Mọi đóng góp, góp ý xây dựng hoặc báo cáo lỗi xin vui lòng tạo Issue hoặc Pull Request tại repository.

**Tác giả:** [Nguyễn Tất Mạnh](https://github.com/nguyentatmanh)  
*Chúc các bạn học tập tốt và đạt điểm cao trong kỳ thi Cơ sở dữ liệu nâng cao!* 🎉
