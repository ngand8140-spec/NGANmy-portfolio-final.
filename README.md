Dangngan portfolio-final.
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="keywords" content="Kim Ngan sable, portfolio, Kim Ngan, full stack dev, personal portfolio lifecodes, portfolio design, portfolio website, personal portfolio" />
  <meta name="description" content="Welcome to Kim Ngan Portfolio. Full-Stack Web Developer and Android App Developer" />

  <!-- Custom CSS -->
  <link rel="stylesheet" href="./assets/css/style.css">

  <!-- Font Awesome -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" 
  integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w==" 
  crossorigin="anonymous" referrerpolicy="no-referrer" />

  <!-- Favicon -->
  <link id='favicon' rel="shortcut icon" href="./assets/images/favicon.png" type="image/x-png">
  <title>Portfolio | Kim Ngan</title>

  <!-- PHÔNG NỀN MÀU NÂU -->
  <style>
    body {
      background: #8B5C2D; /* màu nâu đậm */
      color: #fff8ed; /* màu chữ sáng trên nền nâu */
    }
    .content, .container, .about, .skills, .education, .work, .experience, .contact, .footer {
      background: rgba(139, 92, 45, 0.93); /* nền nâu hơi trong suốt */
      border-radius: 18px;
      padding: 15px 15px;
      margin-bottom: 24px;
    }
  </style>
</head>

<body oncontextmenu="return false">

<!-- navbar -->
<header>
  <a href="/" class="logo"><i class="fab fa-node-js"></i> Jigar</a>
  <div id="menu" class="fas fa-bars"></div>
  <nav class="navbar">
    <ul>
      <li><a class="active" href="#home">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#skills">Skills</a></li>
      <li><a href="#education">Education</a></li>
      <li><a href="#work">Work</a></li>
      <li><a href="#experience">Experience</a></li>
      <li><a href="#contact">Contact</a></li>
    </ul>
  </nav>
</header>

<!-- hero section -->
<section class="home" id="home">
  <div id="particles-js"></div>
  <div class="content">
    <h2>Hi There,<br/> I'm Kim Ngan <span>Sable</span></h2>
    <p>I am into <span class="typing-text"></span></p>
    <a href="#about" class="btn"><span>About Me</span><i class="fas fa-arrow-circle-down"></i></a>
    <div class="socials">
      <ul class="social-icons">
        <li><a class="github" aria-label="GitHub" href="https://github.com/ngand8140-spec/fitkimngan" target="_blank"><i class="fab fa-github"></i></a></li>
      </ul>
    </div>
  </div>
  <div class="image">
    <img draggable="false" class="tilt" src="./assets/images/hero.png" alt="">
  </div>
</section>

<!-- about -->
<section class="about" id="about">
  <h2 class="heading"><i class="fas fa-user-alt"></i> About <span>Me</span></h2>
  <div class="row">
    <div class="image">
      <img draggable="false" class="tilt" src="./assets/images/profile2.jpg" alt="">
    </div>
    <div class="content">
      <h3>I'm Kim Ngan</h3>
      <span class="tag">Full Stack Developer</span>
      <p>Hello everyone, my name is Dang Kim Ngan, I am 18 years old, I am currently studying at university with a major in information technology, I want to discover many new things. And this is my personal page.</p>
      <div class="box-container">
        <div class="box">
          <p><span> email : </span> ngand8140@gmail.com</p>
          <p><span> place : </span> Nha so 9, thon so ha, xa Hong Van, Ha Noi</p>
        </div>
      </div>
      <div class="resumebtn">
        <a href="https://drive.google.com/file/d/1rZiXl562q7aVyk1kJ2nO85YBAq8ixTiw/view" target="_blank" class="btn">
          <span>Resume</span><i class="fas fa-chevron-right"></i>
        </a>
      </div>
    </div>
  </div>
</section>

<!-- skills -->
<section class="skills" id="skills">
  <h2 class="heading"><i class="fas fa-laptop-code"></i> Skills & <span>Abilities</span></h2>
  <div class="container"><div class="row" id="skillsContainer"></div></div>
</section>

<!-- education -->
<section class="education" id="education">
  <h1 class="heading"><i class="fas fa-graduation-cap"></i> My <span>Education</span></h1>
  <p class="qoute">Education is not the learning of facts, but the training of the mind to think.</p>
  <div class="box-container">
    <div class="box">
      <div class="image"><img draggable="false" src="https://tuyensinhhuongnghiep.vn/upload/images/2023/10/03/truong-dai-hoc-dai-nam.jpg" alt=""></div>
      <div class="content">
        <h3>Sinh viên năm nhất Trường Đại học Đại Nam</h3>
        <p>Thuộc Khoa Công Nghệ Thông Tin</p>
        <h4>2025-2026 | Study</h4>
      </div>
    </div>
  </div>
</section>

<!-- work -->
<section class="work" id="work">
  <h2 class="heading"><i class="fas fa-laptop-code"></i> Projects <span>Made</span></h2>
  <div class="box-container"></div>
  <div class="viewall">
    <a href="/projects" class="btn"><span>View All</span><i class="fas fa-arrow-right"></i></a>
  </div>
</section>

<!-- experience -->
<section class="experience" id="experience">
  <h2 class="heading"><i class="fas fa-briefcase"></i> Experience </h2>
  <div class="timeline">
    <div class="container right">
      <div class="content">
        <div class="tag"><h2>Tự chọn ngành</h2></div>
        <div class="desc">
          <h3>Sinh viên theo học ngành Công Nghệ Thông Tin</h3>
          <p>Tháng 8 - 2025 - present</p>
        </div>
      </div>
    </div>
    <div class="container left">
      <div class="content">
        <div class="tag"><h2>Chuẩn bị theo học</h2></div>
        <div class="desc">
          <h3>Sinh viên theo học ngành Công Nghệ Thông Tin</h3>
          <p>Tháng 8 - 2025 - present</p>
        </div>
      </div>
    </div>
    <div class="container right">
      <div class="content">
        <div class="desc">
          <h3>Sinh viên đang theo học Thiết kế Website</h3>
          <p>Tháng 9 - 2025 - present</p>
        </div>
      </div>
    </div>
  </div>
  <div class="morebtn">
    <a href="/experience" class="btn"><span>View All</span><i class="fas fa-arrow-right"></i></a>
  </div>
</section>

<!-- contact -->
<section class="contact" id="contact">
  <h2 class="heading"><i class="fas fa-headset"></i> Get in <span>Touch</span></h2>
  <div class="container">
    <div class="content">
      <div class="image-box">
        <img draggable="false" src="./assets/images/contact1.png" alt="">
      </div>
      <form id="contact-form">
        <div class="form-group">
          <div class="field"><input type="text" name="name" placeholder="Dang Kim Ngan" required><i class='fas fa-user'></i></div>
          <div class="field"><input type="text" name="email" placeholder="ngand8140@gmail.com" required><i class='fas fa-envelope'></i></div>
          <div class="field"><input type="text" name="phone" placeholder="0974781026"><i class='fas fa-phone-alt'></i></div>
          <div class="message"><textarea placeholder="Dang Ngan" name="message" required></textarea><i class="fas fa-comment-dots"></i></div>
        </div>
        <div class="button-area"><button type="submit">Submit <i class="fa fa-paper-plane"></i></button></div>
      </form>
    </div>
  </div>
</section>

<!-- footer -->
<section class="footer">
  <div class="box-container">
    <div class="box">
      <h3>Trang giới thiệu của Ngan</h3>
      <p>Thank you for visiting my personal portfolio website. Connect with me over socials. <br><br>Keep Rising 🚀. Connect with me over live chat!</p>
    </div>
    <div class="box">
      <h3>quick links</h3>
      <a href="#home"><i class="fas fa-chevron-circle-right"></i> home</a>
      <a href="#about"><i class="fas fa-chevron-circle-right"></i> about</a>
      <a href="#skills"><i class="fas fa-chevron-circle-right"></i> skills</a>
      <a href="#education"><i class="fas fa-chevron-circle-right"></i> education</a>
      <a href="#work"><i class="fas fa-chevron-circle-right"></i> work</a>
      <a href="#experience"><i class="fas fa-chevron-circle-right"></i> experience</a>
    </div>
    <div class="box">
      <h3>contact info</h3>
      <p><i class="fas fa-phone"></i> +84 0974781026</p>
      <p><i class="fas fa-envelope"></i> ngand8140@gmail.com</p>
      <p><i class="fas fa-map-marked-alt"></i> Kim Ngan - Viet Nam</p>
      <div class="share">
        <a href="https://github.com/ngand8140-spec/fitkimngan" class="fab fa-github" target="_blank"></a>
        <a href="mailto:ngand8140@gmail.com" class="fas fa-envelope" target="_blank"></a>
      </div>
    </div>
  </div>
  <h1 class="credit">Designed with <i class="fa fa-heart pulse"></i> by <a href="https://www.linkedin.com/in/jigar-sable">Jigar Sable</a></h1>
</section>

<!-- scroll top -->
<a href="#home" class="fas fa-angle-up" id="scroll-top"></a>

<!-- JS Libraries -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/typed.js/2.0.5/typed.min.js"></script>
<script src="./assets/js/particles.min.js"></script>
<script src="./assets/js/app.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/vanilla-tilt/1.7.0/vanilla-tilt.min.js"></script>
<script src="https://unpkg.com/scrollreveal"></script>
<script src="https://cdn.kimngan.net/npm/emailkn-com@3/dist/email.min.kn"></script>
<script src="./assets/kn/script.kn"></script>

</body>
</html>
