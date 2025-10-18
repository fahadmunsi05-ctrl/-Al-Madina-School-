<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Al Madina School</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      background-color: #f9fafb;
      color: #333;
    }

    header {
      background-color: #004080;
      color: white;
      text-align: center;
      padding: 25px 10px;
    }

    header h1 {
      margin: 0;
      font-size: 32px;
    }

    header p {
      margin: 5px 0;
      font-size: 16px;
    }

    nav {
      background-color: #003366;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }

    nav a {
      color: white;
      text-decoration: none;
      padding: 14px 20px;
      display: inline-block;
      transition: 0.3s;
    }

    nav a:hover {
      background-color: #0059b3;
    }

    section {
      padding: 30px;
      max-width: 900px;
      margin: auto;
    }

    h2 {
      color: #003366;
      border-bottom: 2px solid #003366;
      padding-bottom: 5px;
    }

    .about, .contact, .notice {
      background-color: white;
      border-radius: 10px;
      padding: 20px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
      margin-bottom: 30px;
    }

    footer {
      background-color: #002040;
      color: white;
      text-align: center;
      padding: 20px 10px;
      font-size: 14px;
    }

    .logo {
      width: 100px;
      border-radius: 50%;
      margin-bottom: 10px;
    }

    ul {
      text-align: left;
      line-height: 1.8em;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 24px;
      }
      nav {
        flex-direction: column;
      }
      nav a {
        border-top: 1px solid #0059b3;
      }
    }
  </style>
</head>
<body>

  <header>
    <img src="logo.png" alt="School Logo" class="logo">
    <h1>Al Madina School</h1>
    <p>আল মদিনা স্কুল</p>
    <p>স্থাপিত ১৯৮৫ সাল</p>
    <p>মোবাইল: ০১৩৩৩৬৮৪৮১৮</p>
  </header>

  <nav>
    <a href="#home">হোম</a>
    <a href="#about">আমাদের সম্পর্কে</a>
    <a href="#notice">নোটিশ</a>
    <a href="#contact">যোগাযোগ</a>
  </nav>

  <section id="home">
    <div class="about">
      <h2>স্বাগতম</h2>
      <p>
        আল মদিনা স্কুলে আপনাকে স্বাগতম। আমরা শিশুদের প্রাথমিক শিক্ষা ও নৈতিক মূল্যবোধের মাধ্যমে 
        তাদের উজ্জ্বল ভবিষ্যতের জন্য কাজ করে যাচ্ছি। মানসম্মত শিক্ষা, সুশৃঙ্খল পরিবেশ এবং অভিজ্ঞ শিক্ষকবৃন্দ আমাদের শক্তি।
      </p>
    </div>
  </section>

  <section id="about">
    <div class="about">
      <h2>আমাদের সম্পর্কে</h2>
      <p>
        আল মদিনা স্কুল ১৯৮৫ সালে প্রতিষ্ঠিত হয়। শুরু থেকেই আমাদের লক্ষ্য ছিলো 
        শিশুদের ভালোবাসা, যত্ন এবং আধুনিক শিক্ষার সমন্বয়ে গড়ে তোলা। 
        বর্তমানে স্কুলে দক্ষ শিক্ষক ও শিক্ষার্থীদের প্রাণবন্ত উপস্থিতি আমাদের গর্বের বিষয়।
      </p>
    </div>
  </section>

  <section id="notice">
    <div class="notice">
      <h2>সর্বশেষ নোটিশ</h2>
      <ul>
        <li>📢 আগামী সোমবার বার্ষিক ক্রীড়া প্রতিযোগিতা অনুষ্ঠিত হবে।</li>
        <li>📅 ভর্তি চলছে – প্লে, নার্সারি ও কেজি ক্লাসে ভর্তি প্রক্রিয়া চলছে।</li>
        <li>🎓 পরীক্ষার সময়সূচি স্কুলের নোটিস বোর্ডে টাঙানো হয়েছে।</li>
      </ul>
    </div>
  </section>

  <section id="contact">
    <div class="contact">
      <h2>যোগাযোগ</h2>
      <p>📍 ঠিকানা: গৌরীপুর পশ্চিম বাজার, গৌরীপুর, দাউদকান্দি, কুমিল্লা</p>
      <p>📞 মোবাইল: ০১৩৩৩৬৮৪৮১৮</p>
      <p>📧 ইমেইল: info@almadina-school.com</p>
    </div>
  </section>

  <footer>
    © ২০২৫ Al Madina School | Developed by Md Fahad
  </footer>

</body>
</html>
