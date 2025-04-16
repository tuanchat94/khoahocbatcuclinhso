<!DOCTYPE html>
<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Khóa học Bát Cực Linh Số</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      margin: 0;
      padding: 0;
      background-color: #f9f9f9;
    }
    header, section, footer {
      padding: 20px;
      max-width: 800px;
      margin: auto;
    }
    header {
      background: url('https://scontent.fhan20-1.fna.fbcdn.net/v/t39.30808-6/475811028_1291962162067472_2669950216525597812_n.jpg?_nc_cat=103&ccb=1-7&_nc_sid=833d8c&_nc_eui2=AeFxqEIZIg7seng6xLQkh-jk0Oht_udpJjnQ6G3-52kmOVsPrs3DxokMUjzFmHouaMdCgzXlF7SFwnB0H_ZSeDB1&_nc_ohc=aR7a_-UvQM4Q7kNvwHZIy1r&_nc_oc=AdlJcX6GeropaVmILPwKs-XgwQnViY3pPoaDjB-DD-Mbj6vMG0RPlGsc9T0h4dmr_SV7y9_yk-btWYpkKfcbFavr&_nc_zt=23&_nc_ht=scontent.fhan20-1.fna&_nc_gid=35t1MWkLLOe94gZWkauNgg&oh=00_AfGK_4b7YwRKY2W-Cenw0_HaM2SOtSgehOPEG7NZERxozw&oe=68055682') no-repeat center center;
      background-size: cover;
      color: white;
      text-align: center;
    }
    h1 {
      margin-top: 0;
      animation: fadeInDown 2s ease;
    }
    .btn {
      background-color: #28a745;
      color: white;
      padding: 10px 20px;
      border: none;
      cursor: pointer;
      font-size: 16px;
    }
    form input, form textarea {
      display: block;
      width: 100%;
      margin-bottom: 10px;
      padding: 10px;
    }
    form {
      background-color: #fff;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    footer {
      text-align: center;
      font-size: 14px;
      color: #555;
    }
    @keyframes fadeInDown {
      from { opacity: 0; transform: translateY(-20px); }
      to { opacity: 1; transform: translateY(0); }
    }
    .countdown {
      font-size: 24px;
      color: #d9534f;
      font-weight: bold;
      text-align: center;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <header>
    <h1>KHÓA HỌC BÁT CỰC LINH SỐ</h1>
    <p>Khai mở năng lượng số - Cải biến vận mệnh</p>
    <div class="countdown" id="countdown"></div>
  </header>

  <section>
    <h2>Giới thiệu khóa học</h2>
    <p>Khóa học Bát Cực Linh Số hướng dẫn bạn ứng dụng số học cổ xưa để thấu hiểu bản thân, cải thiện vận mệnh và gia tăng tài lộc.</p>
    <ul>
      <li>Giải mã sim phong thủy, căn cước công dân</li>
      <li>Kích hoạt năng lượng tốt - hóa giải năng lượng xấu</li>
      <li>Học trực tuyến qua Zoom</li>
    </ul>
  </section>

  <section>
    <h2>Thông tin chi tiết</h2>
    <p><strong>Thời gian học:</strong> Tối Thứ 3 và Thứ 7 hàng tuần</p>
    <p><strong>Giảng viên:</strong> Vi Quyên </p>
    <p><strong>Học phí:</strong> 5.000.000đ <span style="color: red; font-weight: bold;">MIỄN PHÍ</span></p>
  </section>

  <section>
    <h2>Đăng ký ngay</h2>
    <form action="https://script.google.com/macros/s/AKfycbwzV8CbRUhIgXEj8C207mSHI6gbAYXQunp6RBstcAvrfUdJecH_qCUXhQYodOuFXCIN/exec" method="post">
      <input type="text" name="name" placeholder="Họ và tên" required>
      <input type="tel" name="phone" placeholder="Số điện thoại" required>
      <input type="email" name="email" placeholder="Email (nếu có)">
      <textarea name="note" placeholder="Ghi chú thêm (nếu có)"></textarea>
      <button type="submit" class="btn">Gửi đăng ký</button>
    </form>
  </section>

  <footer>
    <p>Liên hệ: <a href="tel:0862894913">0862.894.913</a> | <a href="https://zalo.me/0862894913" target="_blank">Zalo tư vấn</a></p>
    <p>&copy; 2025 - Bát Cực Linh Số</p>
  </footer>

  <!-- Đồng hồ đếm ngược -->
  <script>
    const countdown = document.getElementById("countdown");
    const targetDate = new Date("2025-04-19T12:00:00").getTime();

    const timer = setInterval(() => {
      const now = new Date().getTime();
      const distance = targetDate - now;

      if (distance < 0) {
        clearInterval(timer);
        countdown.innerHTML = "ĐÃ KHAI GIẢNG";
        return;
      }

      const days = Math.floor(distance / (1000 * 60 * 60 * 24));
      const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
      const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
      const seconds = Math.floor((distance % (1000 * 60)) / 1000);

      countdown.innerHTML = `Khai giảng sau: ${days} ngày ${hours} giờ ${minutes} phút ${seconds} giây`;
    }, 1000);
  </script>

  <!-- Chatbot Tawk.to -->
  <script type="text/javascript">
    var Tawk_API = Tawk_API || {}, Tawk_LoadStart = new Date();
    (function(){
      var s1 = document.createElement("script"), s0 = document.getElementsByTagName("script")[0];
      s1.async = true;
      s1.src = 'https://embed.tawk.to/661f0dd1a0c6737bd12864e3/1hri1upj1';
      s1.charset = 'UTF-8';
      s1.setAttribute('crossorigin','*');
      s0.parentNode.insertBefore(s1,s0);
    })();
  </script>
</body>
</html>
