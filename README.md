my-simple-website/
│
├── index.html
├── styles.css
└── script.js
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trang Web Đơn Giản</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Chào Mừng Đến Với Trang Web Đơn Giản</h1>
        <nav>
            <ul>
                <li><a href="#home">Trang Chủ</a></li>
                <li><a href="#about">Giới Thiệu</a></li>
                <li><a href="#contact">Liên Hệ</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="home">
            <h2>Trang Chủ</h2>
            <p>Đây là phần nội dung của trang chủ.</p>
        </section>

        <section id="about">
            <h2>Giới Thiệu</h2>
            <p>Đây là phần nội dung của trang giới thiệu.</p>
        </section>

        <section id="contact">
            <h2>Liên Hệ</h2>
            <form id="contact-form">
                <label for="name">Họ và Tên:</label>
                <input type="text" id="name" name="name" required>
                <br>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <br>
                <label for="message">Tin Nhắn:</label>
                <textarea id="message" name="message" required></textarea>
                <br>
                <button type="submit">Gửi</button>
            </form>
        </section>
    </main>

    <footer>
        <p>&copy; 2024 Trang Web Đơn Giản. Tất cả quyền được bảo lưu.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
