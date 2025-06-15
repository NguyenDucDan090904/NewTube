# NewTube - Nền Tảng Chia Sẻ Video (Mô Phỏng YouTube)

Dự án NewTube là một nền tảng chia sẻ video được phát triển nhằm mục đích thực hành và áp dụng các kiến thức về phát triển web full-stack. Mục tiêu là tạo ra một ứng dụng có khả năng hiển thị video, quản lý người dùng và tương tác cơ bản, mô phỏng lại một số tính năng cốt lõi của các nền tảng video lớn như YouTube.

## 🚀 Các Tính Năng Nổi Bật

* **Trang chủ:** Hiển thị danh sách các video nổi bật, video mới nhất hoặc video được đề xuất.
* **Trang xem video:** Trình phát video tích hợp, hiển thị thông tin chi tiết về video (tựa đề, mô tả, lượt xem).
* **Chức năng tìm kiếm video:** Cho phép người dùng tìm kiếm video theo từ khóa.
* **Quản lý người dùng:** Đăng ký, đăng nhập tài khoản.
* **Upload video:**  Chức năng cho phép người dùng tải lên video mới.
* **Tương tác video:**  Chức năng like/dislike, bình luận, hoặc đăng ký kênh.
* **Thiết kế đáp ứng (Responsive Design):** Giao diện thân thiện và hoạt động tốt trên các thiết bị khác nhau (máy tính, máy tính bảng, điện thoại).

## 🛠️ Công Nghệ Sử Dụng

Dự án này được xây dựng với các công nghệ chính sau:

**Front-end:**
* **HTML5, CSS3, JavaScript**: React.js
* **CSS Framework/Thư viện**: Tailwind CSS, ShadcnUI
* **Thư viện/API xử lý video**: tRCP

**Back-end:**
* **Ngôn ngữ/Môi trường**: Node.js
* **Framework**: Node.js
* **Cơ sở dữ liệu**: PostgreSQL
* **API:** RESTful API.


## ⚙️ Hướng Dẫn Cài Đặt và Chạy Dự Án

Để cài đặt và chạy dự án này trên máy cục bộ của bạn, vui lòng làm theo các bước dưới đây:

1.  **Clone repository:**
    ```bash
    git clone [https://github.com/NguyenDucDan090904/NewTube.git](https://github.com/NguyenDucDan090904/NewTube.git)
    ```
2.  **Di chuyển vào thư mục dự án:**
    ```bash
    cd NewTube
    ```
3.  **Cài đặt các dependencies cho Front-end và Back-end:**
    *(Bước này sẽ khác nhau tùy thuộc vào công nghệ bạn sử dụng. Ví dụ:)*
    ```bash
    # Trong thư mục gốc của dự án hoặc thư mục server:
    npm install
    # hoặc
    yarn install

    # Nếu có thư mục client riêng (ví dụ project React/Vue):
    cd client # hoặc frontend
    npm install
    # hoặc
    yarn install
    ```
4.  **Cấu hình biến môi trường:**
    * Tạo tệp `.env` trong thư mục gốc của dự án (hoặc thư mục back-end).
    * Thêm các biến môi trường cần thiết (ví dụ: `DATABASE_URL`, `PORT`, `JWT_SECRET`, `CLOUD_STORAGE_API_KEY`, v.v.).

5.  **Chạy database migration/seeding (nếu có):**
    *(Ví dụ nếu dùng SQL database với ORM hoặc muốn thêm dữ liệu mẫu)*
    ```bash
    # Đối với Node.js + Sequelize:
    npx sequelize db:migrate
    # Đối với Django:
    python manage.py migrate
    ```

6.  **Khởi động server và client:**
    *(Ví dụ:)*
    ```bash
    # Khởi động Back-end server:
    npm run start-server # hoặc node server.js

    # Nếu có Front-end riêng, mở terminal mới và khởi động:
    cd client # hoặc frontend
    npm run start # hoặc yarn start
    ```


## 🤝 Đóng Góp

Mọi sự đóng góp đều được hoan nghênh! Nếu bạn có bất kỳ đề xuất cải tiến nào, vui lòng tạo một issue hoặc gửi pull request.

## 📧 Liên Hệ

* **Tên:** Nguyễn Đức Dân
* **GitHub:** [NguyenDucDan090904](https://github.com/NguyenDucDan090904)
* **Email:** ducdansama@gmail.com

---

**Lưu ý:** Đây là một dự án cá nhân được phát triển với mục đích học tập và thực hành các kỹ năng phát triển web full-stack trong bối cảnh nền tảng chia sẻ video.
