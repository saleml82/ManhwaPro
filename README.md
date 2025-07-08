# ManhwaPro<!DOCTYPE html><html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>مانهوا بالعربي</title>
  <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Cairo', sans-serif;
      margin: 0;
      background-color: #f9f9f9;
      color: #222;
    }
    header {
      background-color: #222;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    nav {
      background-color: #444;
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 10px 0;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      font-weight: bold;
    }
    .hero {
      background: url('https://i.imgur.com/WjZkPWB.jpeg') center/cover no-repeat;
      height: 300px;
      display: flex;
      align-items: center;
      justify-content: center;
      color: white;
      text-shadow: 1px 1px 5px black;
      font-size: 2rem;
    }
    .section {
      padding: 30px;
      max-width: 1000px;
      margin: auto;
    }
    .manhwa-list {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
      gap: 20px;
    }
    .card {
      background-color: white;
      border-radius: 10px;
      overflow: hidden;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      text-align: center;
    }
    .card img {
      width: 100%;
      height: 200px;
      object-fit: cover;
    }
    .card h3 {
      padding: 10px;
      font-size: 1rem;
    }
    .card a {
      display: inline-block;
      margin-bottom: 10px;
      color: #0077cc;
      text-decoration: none;
    }
    footer {
      background-color: #222;
      color: #ccc;
      text-align: center;
      padding: 20px;
      margin-top: 40px;
    }
  </style>
</head>
<body>
  <header>
    <h1>مانهوا بالعربي</h1>
    <p>ترجمة ونشر أحدث المانهوا الكورية</p>
  </header>  <nav>
    <a href="index.html">الرئيسية</a>
    <a href="manhwa.html">المانهوا</a>
    <a href="#">الفصول</a>
    <a href="#">من نحن</a>
    <a href="#">اتصل بنا</a>
  </nav>  <div class="hero">
    <div>مرحبًا بك في عالم المانهوا</div>
  </div>  <section class="section">
    <h2>أحدث الإضافات</h2>
    <div class="manhwa-list">
      <div class="card">
        <img src="https://i.imgur.com/lKJiT77.jpeg" alt="مانهوا 1">
        <h3>مانهوا الأكشن الرائعة</h3>
        <a href="manhwa.html">قراءة</a>
      </div>
      <div class="card">
        <img src="https://i.imgur.com/jxWqIBf.jpeg" alt="مانهوا 2">
        <h3>قصة حب مدرسية</h3>
        <a href="manhwa.html">قراءة</a>
      </div>
      <div class="card">
        <img src="https://i.imgur.com/F0p4WbN.jpeg" alt="مانهوا 3">
        <h3>العالم الآخر</h3>
        <a href="manhwa.html">قراءة</a>
      </div>
    </div>
  </section>  <footer>
    &copy; 2025 جميع الحقوق محفوظة - مانهوا بالعربي
  </footer>
</body>
</html>
