<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>เว็บไซต์ทันสมัย</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f0f2f5;
      color: #333;
    }

    header {
      background: linear-gradient(90deg, #4facfe 0%, #00f2fe 100%);
      color: white;
      padding: 40px 20px;
      text-align: center;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }

    header h1 {
      margin: 0;
      font-size: 2.5em;
    }

    main {
      max-width: 900px;
      margin: 40px auto;
      padding: 0 20px;
    }

    section {
      background: white;
      border-radius: 12px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.05);
      padding: 30px;
      margin-bottom: 30px;
      transition: transform 0.3s;
    }

    section:hover {
      transform: translateY(-5px);
    }

    h2 {
      color: #4facfe;
      margin-top: 0;
    }

    p {
      line-height: 1.6;
    }

    .contact-info p {
      margin: 8px 0;
    }

    form input, form textarea {
      width: 100%;
      padding: 12px;
      margin: 8px 0 16px 0;
      border: 1px solid #ccc;
      border-radius: 8px;
      font-size: 1em;
    }

    form button {
      background-color: #4facfe;
      color: white;
      padding: 12px 25px;
      border: none;
      border-radius: 8px;
      font-size: 1em;
      cursor: pointer;
      transition: background 0.3s;
    }

    form button:hover {
      background-color: #00f2fe;
    }

    .social {
      margin-top: 15px;
    }

    .social a {
      margin-right: 15px;
      text-decoration: none;
      color: #4facfe;
      font-weight: bold;
    }

    footer {
      text-align: center;
      padding: 20px;
      background-color: #e0e0e0;
      margin-top: 40px;
      border-top: 1px solid #ccc;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2em;
      }
      section {
        padding: 20px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>ยินดีต้อนรับสู่เว็บไซต์ของเรา</h1>
  </header>

  <main>
    <section>
      <h2>เกี่ยวกับเรา</h2>
      <p>เว็บไซต์นี้เป็นตัวอย่างการแสดงเนื้อหาและข้อมูลติดต่อ พร้อมดีไซน์ทันสมัย เหมาะกับธุรกิจหรือบุคคลทั่วไปที่ต้องการเว็บหน้าเดียวสวยงามและใช้งานง่าย</p>
    </section>

    <section>
      <h2>ติดต่อเรา</h2>
      <div class="contact-info">
        <p>อีเมล: example@email.com</p>
        <p>โทร: 012-345-6789</p>
      </div>
      <form>
        <input type="text" placeholder="ชื่อของคุณ" required>
        <input type="email" placeholder="อีเมลของคุณ" required>
        <textarea placeholder="ข้อความของคุณ" rows="5" required></textarea>
        <button type="submit">ส่งข้อความ</button>
      </form>
      <div class="social">
        <a href="#">Facebook</a>
        <a href="#">Instagram</a>
        <a href="#">Twitter</a>
      </div>
    </section>
  </main>

  <footer>
    &copy; 2025 เว็บไซต์ทันสมัยของคุณ
  </footer>

</body>
</html>