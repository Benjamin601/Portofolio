<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Arya Nitya Kusuma Dewa - Portfolio</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
    }

    body {
      background: #1a1a1a;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 15px 30px;
      background: #1a1a1a;
      border-bottom: 1px solid #ddd;
      flex-wrap: wrap;
    }

    nav .logo {
      font-size: 25px;
      font-weight: bold;
      color: #1dbf73;
    }

    nav .nav-links {
      display: flex;
      gap: 20px;
      align-items: center;
      font-size: 20px;
      color: #1dbf73;
    }

    .categories {
      display: flex;
      flex-wrap: wrap;
      gap: 15px;
      padding: 20px 30px;
      background: #1a1a1a;
    }

    .categories button {
      padding: 10px 16px;
      background: #1dbf73;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      color: white;
    }

    .services-section {
      padding: 30px;
    }

    .services-section h2,
    .services-section h3 {
      margin-bottom: 20px;
      font-size: 22px;
      color: #1dbf73;
    }

    .cards {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
    }

    .card {
      min-width: 180px;
      background: #1dbf73;
      color: white;
      border-radius: 12px;
      overflow: hidden;
      padding: 15px;
      transition: 0.3s;
    }

    .card h4 {
      font-size: 16px;
      margin-top: 10px;
    }

    .card h5 {
      font-size: 12px;
      margin-top: 10px;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 5px 10px rgba(0,0,0,0.1);
    }

    .parent {
      width: 300px;
      padding: 20px;
      perspective: 1000px;
      margin: auto;
    }

    .card2 {
      padding-top: 50px;
      border: 3px solid rgb(255, 255, 255);
      transform-style: preserve-3d;
      background: linear-gradient(135deg,#0000 18.75%,#f3f3f3 0 31.25%,#0000 0),
          repeating-linear-gradient(45deg,#f3f3f3 -6.25% 6.25%,#ffffff 0 18.75%);
      background-size: 60px 60px;
      background-position: 0 0, 0 0;
      background-color: #1dbf73;
      width: 100%;
      box-shadow: rgba(142, 142, 142, 0.3) 0px 30px 30px -10px;
      transition: all 0.5s ease-in-out;
    }

    .card2:hover {
      background-position: -100px 100px, -100px 100px;
      transform: rotate3d(0.5, 1, 0, 30deg);
    }

    .content-box {
      background: #1dbf73;
      padding: 60px 25px 25px 25px;
      transform-style: preserve-3d;
    }

    .card2-title {
      display: inline-block;
      color: white;
      font-size: 25px;
      font-weight: 900;
      transform: translate3d(0px, 0px, 50px);
    }

    .card2-content {
      margin-top: 10px;
      font-size: 12px;
      font-weight: 700;
      color: #f2f2f2;
      transform: translate3d(0px, 0px, 30px);
    }

    .see-more {
      cursor: pointer;
      margin-top: 1rem;
      display: inline-block;
      font-weight: 900;
      font-size: 9px;
      text-transform: uppercase;
      color: #1dbf73;
      background: white;
      padding: 0.5rem 0.7rem;
      transform: translate3d(0px, 0px, 20px);
    }

    .date-box {
      position: absolute;
      top: 30px;
      right: 30px;
      height: 60px;
      width: 60px;
      background: white;
      padding: 5px;
      transform: translate3d(0px, 0px, 80px);
      box-shadow: rgba(100, 100, 111, 0.2) 0px 17px 10px -10px;
    }

    .date-box span {
      display: block;
      text-align: center;
    }

    .date-box .month,
    .date-box .date,
    .date-box .year {
      color: #1dbf73;
      font-weight: 700;
    }

    .date-box .month { font-size: 9px; }
    .date-box .date { font-size: 18px; }
    .date-box .year { font-size: 12px; }

    footer {
      text-align: center;
      padding: 20px;
      background: #1a1a1a;
      color: #1dbf73;
    }

    a {
      color: #1dbf73;
      text-decoration: none;
    }
  </style>
</head>
<body>

  <nav>
    <div class="logo">ARYA NITYA KUSUMA DEWA</div>
    <div class="nav-links">
      <span>BACHELOR OF SCIENCE</span>
      <span>DIPONEGORO UNIVERSITY</span>
      <img src="foto-profil.jpg" alt="Arya's Photo" style="width:100px; border-radius: 50%;" />
    </div>
  </nav>

  <div class="parent">
    <div class="card2">
      <div class="content-box">
        <span class="card2-title">ABOUT ME</span>
        <p class="card2-content">
          A graduate with a Bachelor of Science from Diponegoro University who enjoys working with people to grow and sharpen skills. Active in social programs, experienced in labs and teamwork, with a passion for data and the mining industry.
        </p>
        <span class="see-more">See More</span>
      </div>
      <div class="date-box">
        <span class="month">JUNE</span>
        <span class="date">11</span>
        <span class="year">2001</span>
      </div>
    </div>
  </div>

  <div class="services-section">
    <h2>PROJECT & EXPERIENCE</h2>
    <div class="cards">
      <!-- card list here (tidak diubah karena sudah bagus) -->
    </div>
  </div>

  <div class="services-section">
    <h3>SKILL & PROFICIENT</h3>
    <div class="categories">
      <button>HTML5, CSS3</button>
      <button>Microsoft Office</button>
      <button>CorelDRAW, Canva</button>
      <button>SQL & Data Tools</button>
      <button>Teamwork</button>
      <button>Responsibility</button>
      <button>Discipline</button>
    </div>
  </div>

  <footer>
    <p>© 2025 Arya Nitya Kusuma Dewa</p>
    <a href="Curriculum Vitae Arya Nitya Kusuma Dewa.pdf" download style="display: inline-block; padding: 10px 20px; background: #1dbf73; color: white; text-decoration: none; border-radius: 5px;">Download My CV</a>
  </footer>

</body>
</html>
