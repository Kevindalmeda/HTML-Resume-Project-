# HTML-Resume-Project-
A fully responsive, simple-page resume built using semantic HTML and modern CSS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.7.2/css/all.min.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css"/>
</head>
<body>
  <style>
    * {
    margin: 0;
    padding: 0;
}
html {
    overflow-x: hidden;
    scroll-behavior: smooth;
}
body {h
  -webkit-user-select: none;
  -ms-user-select: none;
  user-select: none;
  -webkit-tap-highlight-color: transparent; 
}
body {
    font-family: "Poppins", sans-serif;
}
nav {
    height: 118.184px;
    width: 100%;
    display: flex;
    justify-content: space-evenly;
}
.navname {
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 30px;
}
.aboveoption {
    height: 100%;
    display: flex;
    align-items: center;
    justify-content: space-evenly;
}
.topbox {
    margin: 20px;
}
.under {
    text-decoration: none;
    font-size: 25px;
    color: black;
}
.under:hover {
    color: rgb(85, 85, 85);
}
section {
    height: 500px;
    width: 100%;
    display: flex;
    justify-content: center;
    /* background-color: red; */
}

.profilepic {
    height: 100%;
    width: 400px;
    margin-right: 10px;
    display: flex;
    align-items: center;
    justify-content: center;

}
.sectiontext {
    height: 100%;
    margin-left: 100px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}
.profilephoto {
    height: 80%;
    width: 100%;
    border-radius: 100%;
}
.pp {
    height: 100%;
    width: 100%;
    border-radius: 100%;
    /* filter: drop-shadow(0 0 10px black); */
}
.hello {
    height: 30px;
    color: rgb(85, 85, 85);
    font-size: 26px;
}
.name {
    height: 30px;
    margin-bottom: 25px;
    font-size: 35px;
}
.job {
    height: 30px;
    margin-bottom: 20px;
    color: rgb(120, 119, 119);
    margin-bottom: 30px;
}
.twobuttons {
    margin-bottom: 10px;
}
.samebutton {
    height: 55px;
    width: 130px;
    border-radius: 30px;
    border: none;
    font-size: 13px;
    font-weight: 550;
}
.cv {
    border: 2px solid black;  
    background-color: white;
    transition: 0.4s;
    margin-right: 10px;
}
.cv:hover {
    background-color: black;
    color: white;
}
.contact {
    background-color: black;
    color: white;
    margin-left: 10px;
}
.inandgit {
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-top: 10px;
}
.clickicons {
    font-size: 35px;
    color: black;
}
.linkedin {
    margin-right: 10px;
}
.github {
    margin-left: 10px;
}
.midabout {
    margin-top: 120px;
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    flex-direction: column;
}
.knowmore {
    color: rgb(85, 85, 85);
    font-size: 15px;
}
.aboutme {
    font-size: 48px;
}
.exedu {
    width: 100%;
    /* background-color: aqua; */
    display: flex;
    align-items: center;
    justify-content: space-evenly;
}
.sepeducontent {
    padding: 20px;
}
.midphoto {
    height: 400px;
    width: 400px;
    /* background-color: red; */
    border-radius: 30px;
    margin: 70px;
}
.topsep {
    height: 200px;
    /* background-color: green; */
    display: flex;
    align-items: center;
    justify-content: space-around;
}
.education, .experience {
    height: 90%;
    width: 40%;
    border-radius: 30px;
    border: 2px solid rgb(85, 85, 85);
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
}

/-------------Responsive part-----------------/
@media (max-width: 977px) {
    .profilephoto {
        display: flex;
        align-items: center;
        justify-content: center;
    }
    .pp {
        width: 200px;
    }
  section {
    flex-direction: column;
    align-items: center;
    height: auto;
  }
  .sectiontext {
    margin-top: 25px;
    margin-left: 0;
    text-align: center;
  }
  .aboveoption {
    display: none;
  }
  nav {
    display: flex;
    align-items: center;
  }
  .cv {
    transition: background-color 0.7s;
  }
  .cv:hover {
    background-color: white; 
    color: black;           
    pointer-events: none;     
  }
  .cv:active {
    background-color: black;
    color: white;
  }
  .name {
        font-size: 30px;
    }
    .exedu {
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: column;
    }
    .midphoto {
        height: 180px;
        width: 180px;
        margin: 0;
    }
    .sep {
        margin: 0;
    }
    .topsep {
        height: auto;
    }
}

@media (max-width: 600px) {
    .aboutme {
        font-size: 32px;
    }
    .topsep {
        height: auto;
        display: flex;
        flex-direction: column;
    }
    .education, .experience {
        margin: 10px;
        width: 90%;
    }
}

.experience-details-container {
  width: 100%;
  padding: 40px 20px;
  box-sizing: border-box;
}

.about-containers {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 50px;
}

.details-container {
  background-color: #fff;
  padding: 20px;
  border-radius: 15px;
  width: 55%;
  max-width: 500px;
  /* box-sizing: border-box; */
  border: 2px solid rgb(85, 85, 85);
}

.experience-sub-title {
  text-align: center;
  margin-bottom: 20px;
  font-size: 28px;
  font-weight: bold;
  color: rgb(85, 85, 85);
}

.article-container {
  display: grid;
  grid-template-columns: 50% 50%;
  gap: 35px;
  margin: 20px;
}

.article-container article {
  display: flex;
  align-items: center;
  gap: 10px;
}

.icon {
  width: 20px;
  height: 20px;
}
@media screen and (max-width: 768px) {
  .details-container {
    width: 90%;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .article-container {
    grid-template-columns: 100%;
  }
}


.portfolio-container {
  padding: 40px;
  display: flex;
  justify-content: center;
}

.project-card-wrapper {
  display: flex;
  gap: 30px;
  flex-wrap: wrap;
  justify-content: center;
}

.project-card {
  background-color: #fff;
  border-radius: 20px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
  overflow: hidden;
  text-align: center;
  padding: 20px;
  max-width: 300px;
  transition: transform 0.3s ease;
  border: 2px solid rgb(85, 85, 85);
}

.project-card:hover {
  transform: translateY(-5px);
}

.project-image img {
  width: 100%;
  border-radius: 10px;
}

.project-title {
  font-size: 20px;
  font-weight: bold;
  margin: 15px 0;
}

.project-buttons {
  display: flex;
  justify-content: space-around;
  margin-top: 10px;
}

.btn {
  padding: 10px 20px;
  font-size: 14px;
  border-radius: 30px;
  cursor: pointer;
  border: none;
  transition: background-color 0.3s ease;
  font: bolder;
}

.btn-outline {
  border: 2px solid #333;
  background-color: transparent;
  color: #333;
}

.btn-outline:hover {
  background-color: #333;
  color: #fff;
}


.contact-container {
    /* background-color: rgb(0, 200, 255); */
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}
.contact-box {
    /* background-color: red; */
    padding: 20px;
    border: 2px solid rgb(85, 85, 85);
    border-radius: 30px;
    margin-top: 30px;
    margin-bottom: 30px;
}
.contact-link {
    margin: 30px;
    text-decoration: none;
    color: black;
    font-size: 20px;
}
.contact-link:hover {
    color: rgb(85, 85, 85);
}
.contact-footer {
    width: 100%;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding: 10px;
}
.botan {
    text-decoration: none;
    color: black;
    font-size: 24px;
}
.botan:hover {
    color: rgb(85, 85, 85);
}
@media screen and (max-width: 768px) {
    .footer-nav {
        height: auto;
        gap: 10px;
        display: flex;
        flex-direction: column;
        margin-bottom: 40px;
    }
}
.sam {
    text-decoration: none;
    color: white;
}

/* Hamburger Part_-------------------------- */
#toggle { 
  display: none; 
}
.hicon {
  display: none;
  width: 30px;
  cursor: pointer;
  padding: 10px;
}
.bar {
  width: 30px;
  height: 3px;
  background: #000;
  margin: 6px 0;
  transition: 0.4s;
}
#toggle:checked + label .bar1 {
  transform: rotate(45deg) translate(1.5px, 1.5px);
}
#toggle:checked + label .bar2 {
  display: none;
}
#toggle:checked + label .bar3 {
  transform: rotate(-45deg) translate(5px, -5px);
}
.leftopt {
  position: absolute;
  top: 90px;
  right: 0;
  width: 100%;
  background-color: white;
  display: none;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  font-size: 20px;
}
#toggle:checked ~ .leftopt {
  display: flex;
  transition: 0.5s;
}
.ham-opt {
  text-decoration: none;
  /* margin: 10px; */
  padding: 10px;
  color: black;
  border-bottom: 0.1px solid black;
  width: 100%;
  text-align: center;
  transition: 0.5s;
}

.ham-opt:focus {
    animation: grayFlash 0.4s forwards;
    outline: none;
  }

@keyframes grayFlash {
    0% {
      background-color: gray;
    }
    100% {
     background-color: white;
  }  
}

@media (max-width: 977px) {
  .hicon {
    position: absolute;
    right: 20px;
    display: inline-block;
  }
}

@media (max-width: 520px) {
  .navname {
    position: absolute;
    left: 20px;
    font-size: 25px;
  }
}
  </style>
    <nav>
        <div class="navname">
           Kevin Paul D Almeda
        </div>
        <div class="aboveoption">
            <div class="topbox"><a href="#mabout" class="under">About</a></div>
            <div class="topbox"><a href="#mexp" class="under">Experience</a></div>
            <div class="topbox"><a href="#mproj" class="under">Projects</a></div>
            <div class="topbox"><a href="#mcont" class="under">Contact</a></div>
        </div>

        <input type="checkbox" id="toggle">
        <label for="toggle" class="hicon">
            <div class="bar bar1"></div>
            <div class="bar bar2"></div>
            <div class="bar bar3"></div>
        </label>
        <span class="leftopt">
          <a href="#mabout" class="ham-opt">About</a>
          <a href="#mexp" class="ham-opt">Experience</a>
          <a href="#mproj" class="ham-opt">Projects</a>
          <a href="#mcont" class="ham-opt">Contact</a>
      </span>
    </nav>




    <section>
        <div class="profilepic">
            <div class="profilephoto">
                <img class="pp" src="C:\Users\admin\OneDrive\Desktop\df.jpg"alt="profile photo" style="border-radius: 10px;" height="40%">
            </div>
        </div>
        <div class="sectiontext">
            <h4 class="hello">Hello, I am</h4>
            <h1 class="name">Kevin Paul D Almeda</h1>
            <h2 class="job">Frontend Developer</h2>
            <div class="twobuttons">
                <button class="samebutton cv">Download CV</button>
                <button class="samebutton contact"><a href="#mcont" class="sam">Contact info</a></button>
            </div>
            <div class="inandgit">
                <a href="https://in.linkedin.com/"><i class="fa-brands fa-linkedin-in clickicons linkedin"></i></a>
                <a href="https://github.com/Kevin Paul D Almeda"><i class="fa-brands fa-github clickicons github"></i></a>
            </div>
        </div>
    </section>
    <div class="midabout" id="mabout">
        <p class="knowmore">Get To Know More</p>
        <h1 class="aboutme">About Me</h1>
    </div>
    <div class="exedu">
        <div class="midphoto">
            <img src="C:\Users\admin\OneDrive\Desktop\df.jpg" style="border-radius: 50px;" height="100%">
        </div>
        <div class="sep">
            <div class="topsep">
                <div class="experience">
                        <img src="https://tangerine-hummingbird-1479b6.netlify.app/assets/experience.png" alt="Experience icon" class="icon" height="50px">
                        <h3>Experience</h3>
                        <p>2+ years <br>Frontend Development</p>
                </div>
                <div class="education">
                    <img src="https://tangerine-hummingbird-1479b6.netlify.app/assets/education.png" alt="Experience icon" class="icon" height="50px">
                        <h3>Education</h3>
                        <p>Bachelor Of Computer Applications</p>
                </div>
            </div>
            <p class="sepeducontent">
                Hi, I'm a passionate and curious web developer currently pursuing my studies in web development. I specialize in building responsive, user-friendly websites using HTML, CSS, JavaScript, and modern frameworks like React.
                I enjoy turning ideas into functional and visually appealing digital experiences. Whether it's a small project or a full website, I approach each challenge with a strong problem-solving mindset and a desire to learn and grow.
                Right now, I’m focused on expanding my skills in full-stack development and working on real-world projects to strengthen my portfolio. I'm always open to collaboration, feedback, and new learning opportunities.
                Let’s build something great together!
            </p>
        </div>
    </div>

    <div class="midabout" id="mexp">
        <p class="knowmore">Explore My</p>
        <h1 class="aboutme">Experience</h1>
    </div>

    <div class="experience-details-container">
        <div class="about-containers">
          <div class="details-container">
            <h2 class="experience-sub-title">Frontend Development</h2>
            <div class="article-container">
              <article>
                <img src="C:\Users\admin\OneDrive\Desktop\images.png" alt="Experience icon" class="icon">
                <div>
                  <h3>HTML</h3>
                  <p>Experienced</p>
                </div>
              </article>
              <article>
                <img src="C:\Users\admin\OneDrive\Desktop\images.png" alt="Experience icon" class="icon">
                <div>
                  <h3>CSS</h3>
                  <p>Experienced</p>
                </div>
              </article>
              <article>
                <img src="C:\Users\admin\OneDrive\Desktop\images.png" alt="Experience icon" class="icon">
                <div>
                  <h3>React</h3>
                  <p>Intermediate</p>
                </div>
              </article>
              <article>
                <img src="C:\Users\admin\OneDrive\Desktop\images.png" alt="Experience icon" class="icon">
                <div>
                  <h3>JavaScript</h3>
                  <p>Basic</p>
                </div>
              </article>
              <article>
                <img src="C:\Users\admin\OneDrive\Desktop\images.png" alt="Experience icon" class="icon">
                <div>
                  <h3>TypeScript</h3>
                  <p>Basic</p>
                </div>
              </article>
              <article>
                <img src="C:\Users\admin\OneDrive\Desktop\images.png" alt="Experience icon" class="icon">
                <div>
                  <h3>Material UI</h3>
                  <p>Intermediate</p>
                </div>
              </article>
            </div>
          </div>
          <div class="details-container">
            <h2 class="experience-sub-title">Frontend Development</h2>
            <div class="article-container">
              <article>
                <img src="C:\Users\admin\OneDrive\Desktop\images.png" alt="Experience icon" class="icon">
                <div>
                  <h3>PostgreSQL</h3>
                  <p>Basic</p>
                </div>
              </article>
              <article>
                <img src="C:\Users\admin\OneDrive\Desktop\images.png" alt="Experience icon" class="icon">
                <div>
                  <h3>Node JS</h3>
                  <p>Intermediate</p>
                </div>
              </article>
              <article>
                <img src="C:\Users\admin\OneDrive\Desktop\images.png" alt="Experience icon" class="icon">
                <div>
                  <h3>Express JS</h3>
                  <p>Intermediate</p>
                </div>
              </article>
              <article>
                <img src="C:\Users\admin\OneDrive\Desktop\images.png" alt="Experience icon" class="icon">
                <div>
                  <h3>Git</h3>
                  <p>Intermediate</p>
                </div>
              </article>
            </div>
          </div>

        </div>
      </div>

    <div class="midabout" id="mproj">
        <p class="knowmore">Browse My Recent</p>
        <h1 class="aboutme">Projects</h1>
    </div>

    <div class="portfolio-container">
  <div class="project-card-wrapper">
    <div class="project-card">
      <div class="project-image">
        <img src="C:\Users\admin\OneDrive\Desktop\mobile-chat-app-online-communication-social-networking-messages-speech-bubbles-tiny-people-chatting-in-mobile-smartphone-screen-modern-flat-cartoon-style-illustration-on-white-background-vector.jpg"alt="Project One" widith="60%">
      </div>
      <h2 class="project-title">TalkChat App</h2>
      <div class="project-buttons">
        <button class="btn btn-outline" onclick="location.href='https://github.com/'">GitHub</button>
        <button class="btn btn-outline" onclick="location.href='https://github.com/'">Live Demo</button>
      </div>
    </div>

    <div class="project-card">
      <div class="project-image">
        <img src="C:\Users\admin\OneDrive\Desktop\stock-vector-to-do-reminder-app-cartoon-smartphone-interface-vector-templates-set-mobile-app-screen-page-day-1785961055.jpg" alt="Project Two">
      </div>
      <h2 class="project-title">Reminder App</h2>
      <div class="project-buttons">
        <button class="btn btn-outline" onclick="location.href='https://github.com/'">GitHub</button>
        <button class="btn btn-outline" onclick="location.href='https://github.com/'">Live Demo</button>
      </div>
    </div>

    <div class="project-card">
      <div class="project-image">
        <img src="C:\Users\admin\OneDrive\Desktop\images.jpeg" alt="Project Three">
      </div>
      <h2 class="project-title">Food Ordering App</h2>
      <div class="project-buttons">
        <button class="btn btn-outline" onclick="location.href='https://github.com/'">GitHub</button>
        <button class="btn btn-outline" onclick="location.href='https://github.com/'">Live Demo</button>
      </div>
    </div>
  </div>
</div>

    <div class="midabout" id="mcont">
        <p class="knowmore">Get in Touch</p>
        <h1 class="aboutme">Contact Me</h1>
    </div>

    <div class="contact-container">
        <div class="contact-box">
            <a href="https://mail.google.com/" class="contact-link">
                <i class="fas fa-envelope"></i>
                <span>kevinpauldalmeda@gmail.com</span>
            </a>
            <a href="https://in.linkedin.com/" class="contact-link">
                <i class="fab fa-linkedin"></i>
                <span>LinkedIn</span>
            </a>
        </div>

        <footer class="contact-footer">
            <nav class="footer-nav">
                <a href="#mabout" class="botan">About</a>
                <a href="#mexp" class="botan">Experience</a>
                <a href="#mproj" class="botan">Projects</a>
                <a href="#mcont" class="botan">Contact</a>
            </nav>
            <p class="footer-copy">Copyright © 2025 Kevin Paul D Almeda . All Rights Reserved.</p>
        </footer>
    </div>

    <script>

  const hamLinks = document.querySelectorAll('.ham-opt');
  const toggleCheckbox = document.getElementById('toggle');

  hamLinks.forEach(link => {
    link.addEventListener('click', () => {
      toggleCheckbox.checked = false;
    });
  });
</script>
</body>
</html>
