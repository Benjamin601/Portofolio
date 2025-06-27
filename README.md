<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Arya Nitya Kusuma Dewa-Portfolio</title>
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

    .services-section h2 {
      margin-bottom: 20px;
      font-size: 22px;
      color: #1dbf73;
    }
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

    .card img {
      width: 100%;
      border-radius: 8px;
      margin-bottom: 10px;
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

     parent {
  width: 300px;
  padding: 20px;
  perspective: 1000px;
}

.card2 {
  padding-top: 50px;
  /* border-radius: 10px; */
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
  /* border-radius: 10px 100px 10px 10px; */
  transition: all 0.5s ease-in-out;
  padding: 60px 25px 25px 25px;
  transform-style: preserve-3d;
}

.content-box .card2-title {
  display: inline-block;
  color: white;
  font-size: 25px;
  font-weight: 900;
  transition: all 0.5s ease-in-out;
  transform: translate3d(0px, 0px, 50px);
}

.content-box .card2-title:hover {
  transform: translate3d(0px, 0px, 60px);
}

.content-box .card2-content {
  margin-top: 10px;
  font-size: 12px;
  font-weight: 700;
  color: #f2f2f2;
  transition: all 0.5s ease-in-out;
  transform: translate3d(0px, 0px, 30px);
}

.content-box .card2-content:hover {
  transform: translate3d(0px, 0px, 60px);
}

.content-box .see-more {
  cursor: pointer;
  margin-top: 1rem;
  display: inline-block;
  font-weight: 900;
  font-size: 9px;
  text-transform: uppercase;
  color: #1dbf73;
  /* border-radius: 5px; */
  background: white;
  padding: 0.5rem 0.7rem;
  transition: all 0.5s ease-in-out;
  transform: translate3d(0px, 0px, 20px);
}

.content-box .see-more:hover {
  transform: translate3d(0px, 0px, 60px);
}

.date-box {
  position: absolute;
  top: 30px;
  right: 30px;
  height: 60px;
  width: 60px;
  background: white;
  border: 1px #1dbf73;
  /* border-radius: 10px; */
  padding: 5px;
  transform: translate3d(0px, 0px, 80px);
  box-shadow: rgba(100, 100, 111, 0.2) 0px 17px 10px -10px;
}

.date-box span {
  display: block;
  text-align: center;
}

.date-box .month {
  color: #1dbf73;
  font-size: 9px;
  font-weight: 700;
}

.date-box .date {
  font-size: 18px;
  font-weight: 900;
  color: #1dbf73;
}
.date-box .year {
  color: #1dbf73;
  font-size: 12px;
  font-weight: 700;
}
 
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
    <img src="foto-profil.jpg" alt="Arya's Photo" style="width:150px; border-radius: 100px; margin-top: 10px;" />
    </div>
  </nav>

<div class="parent">
  <div class="card2">
      <div class="content-box">
          <span class="card2-title">ABOUT ME</span>
          <p class="card2-content">“A graduate with a Bachelor of Science from Diponegoro University who enjoys meeting and working with new people to broaden horizons and sharpen skills. During my studies, I developed strong communication skills, the ability to work in a team, and a passion for learning new things. This is evidenced by my active involvement in various social activities. Additionally, I have experience as a laboratory assistant. I have an interest in data, research, materials and exploration, as well as a strong desire to pursue a career in the mining industry.”
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
      <div class="card">
        <h4>Thesis Title</h4>
        <h5>Synthesis of Zinc Oxide using the precipitation method and its application on cotton fabric as an antibacterial agent and to enhance the hydrophobic properties of the fabric</h5>
      </div>
      <div class="card" style="background:#f78da7;">
        <h4>A Basic Physics Laboratory Assistant</h4>
        <h5>Assisting lecturers in preparing several practicum modules, setting up the equipment used for practicum, guiding and supervising practicum participants, and also correcting practicum reports from participants</h5> 
      </div>
      <div class="card" style="background:#c5e384;">
        <h4>Materials Laboratory Assistant</h4>
        <h5>Assisting lecturers in preparing the laboratory usage schedule, preparing equipment and materials used for student research, operating sample testing instruments such as UV-Vis spectrophotometry, guiding and supervising student research, recording sample testing data for student research, and also conducting regular checks on equipment and materials in the laboratory</h5>
      </div>
      <div class="card" style="background:#74b9ff;">
        <h4>Kampus Mengajar</h4>
        <h5>The lack of teaching staff at Elementary Schools 2 and 3 in Tempurharjo Village, Eromoko District, Wonogiri Regency led me to coordinate with the school principal and obtain permission to help fill the vacant teaching schedules for grades 1, 2, and 4. My friends and I took turns filling these gaps, introducing the concept of "learning through play." In grade 4, I taught about electromagnetism, specifically the properties of magnets. The students were familiar with magnetic-based tools or objects but did not realize they were magnets. I was delighted to introduce something new and change the perception that physics is intimidating into the idea that physics is fun</h5>
      </div>
      <div class="card" style="background:#fd79a8;">
        <h4>Kampus Peduli</h4>
        <h5>My friends and I assisted the youth organization of Bokuning Village, Eromoko District, Wonogiri Regency in establishing and realizing an out-of-school learning institution for elementary school children in Bokuning Village, named "Sanggar Baca". We organized the management structure, assigned teaching staff based on age groups, selected the location, and handled the necessary permits. My role focused on developing the learning modules, which included creating the learning schedule, defining the vision and mission of "Sanggar Baca", planning future activities, and outlining the objectives of its establishment</h5>
      </div>
    </div>
  </div>

<div class="services-section">
    <h3>SKILL & PROFICIENT</h3>
    <div class="categories">
    <button>Microsoft Office (Excel, Word, PowerPoint)</button>
    <button>Graphics & Design (Photoshop, CorelDRAW, Canva)</button>
    <button>Disciplined</button>
    <button>Responsible</button>
    <button>Quickly Learn</button>
    <button>Easily adaptable</button>
    <button>Research data processing software (MDI Jade 6, ImageJ, Origin)</button>
    <button>Problem Solving</button>
    <button>Able to work in a team or individually</button>
    <button>Detail Oriented</button>
    <button>Front-End Web Development (HTML5, CSS3)</button>
  </div>
</div>

  <footer>
    <p>© 2025 Arya Nitya Kusuma Dewa</p>
    <a href="Curriculum Vitae Arya Nitya Kusuma Dewa.pdf" download style="display: inline-block; padding: 10px 20px; background: #1dbf73; color: white; text-decoration: none; border-radius: 5px;">
    Download My CV
    </a>
  </footer>
</body>
</html>
