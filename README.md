<!DOCTYPE html>
<html lang="fa" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>کلن RK Family | کالاف دیوتی موبایل</title>
  <style>
    body {
      font-family: 'Tahoma', sans-serif;
      background-color: #0a0a0a;
      color: #ffffff;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #001f3f;
      padding: 20px;
      text-align: center;
      border-bottom: 2px solid #0074D9;
    }
    header h1 {
      margin: 0;
      color: #0074D9;
    }
    nav {
      background-color: #001f3f;
      padding: 10px;
      text-align: center;
    }
    nav a {
      color: #ffffff;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }
    nav a:hover {
      color: #0074D9;
    }
    section {
      padding: 40px;
      max-width: 1000px;
      margin: auto;
    }
    .gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }
    .gallery img {
      width: 200px;
      margin: 10px;
      border-radius: 10px;
      transition: 0.3s;
    }
    .gallery img:hover {
      transform: scale(1.1);
    }
    form {
      display: flex;
      flex-direction: column;
      gap: 15px;
    }
    input, textarea {
      padding: 10px;
      border-radius: 5px;
      border: none;
      font-size: 16px;
    }
    button {
      background-color: #0074D9;
      color: white;
      padding: 10px;
      border: none;
      border-radius: 5px;
      font-weight: bold;
      cursor: pointer;
    }
    button:hover {
      background-color: #005fa3;
    }
    footer {
      background-color: #001f3f;
      text-align: center;
      padding: 20px;
      font-size: 14px;
      color: #bbbbbb;
    }
    @media (max-width: 600px) {
      .gallery {
        flex-direction: column;
        align-items: center;
      }
      .gallery img {
        width: 80%;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>RK Family - کالاف دیوتی موبایل</h1>
    <p>به کلن حرفه‌ای RK Family خوش آمدید!</p>
  </header>

  <nav>
    <a href="#about">درباره کلن</a>
    <a href="#gallery">گالری</a>
    <a href="#join">عضویت</a>
    <a href="#contact">تماس با ما</a>
  </nav>

  <section id="about">
    <h2>درباره RK Family</h2>
    <p>
      RK Family یک کلن حرفه‌ای و قدرتمند در بازی Call of Duty Mobile است که با افتخار جزو بهترین تیم‌های رقابتی ایران قرار دارد. اعضای ما بازیکنان حرفه‌ای با هماهنگی بالا هستند که در مودهای مختلف مانند Multiplayer و Battle Royale عملکرد درخشانی دارند.
    </p>
  </section>

  <section id="gallery">
    <h2>تصاویر کلن</h2>
    <div class="gallery">
      <img src="https://via.placeholder.com/200x120.png?text=DK+Team+1" alt="کلن 1">
      <img src="https://via.placeholder.com/200x120.png?text=DK+Team+2" alt="کلن 2">
      <img src="https://via.placeholder.com/200x120.png?text=Victory+Screenshot" alt="برد تیم">
    </div>
  </section>

  <section id="join">
    <h2>عضویت در کلن</h2>
    <p>اگر حس می‌کنید بازیکن خوبی هستید و می‌خواهید عضو تیم شوید، فرم زیر را پر کنید تا با شما تماس بگیریم.</p>
    <form onsubmit="handleSubmit(event)">
      <input type="text" placeholder="نام و نام خانوادگی" required>
      <input type="text" placeholder="آی‌دی بازی شما (Call of Duty ID)" required>
      <textarea placeholder="توضیح کوتاه درباره خودتان و تجربه بازی..." rows="4" required></textarea>
      <button type="submit">ارسال درخواست</button>
    </form>
  </section>

  <section id="contact">
    <h2>تماس با ما</h2>
    <p>برای ارتباط مستقیم با لیدر کلن، به آی‌دی تلگرام زیر پیام دهید:</p>
    <p><strong><a href="https://t.me/ARtore_h" target="_blank">@ARtore_h</a></strong></p>
  </section>

  <footer>
    © 2025 کلن RK Family. تمام حقوق محفوظ است.
  </footer>

  <script>
    function handleSubmit(event) {
      event.preventDefault();
      alert('درخواست شما با موفقیت ارسال شد! به زودی با شما تماس خواهیم گرفت.');
    }
  </script>

</body>
</html>
