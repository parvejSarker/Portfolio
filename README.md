Portfolio 
<html lang="en" dir="ltr">
  <head>     
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Responsive Personal Portfolio Website - HTML, CSS</title>
    <link rel="stylesheet" href="style1.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.2/css/all.min.css">
  </head>
  <body>

    <div class="scrollToTop-btn">
      <i class="fas fa-angle-up"></i>
    </div>

    <header>
      <a href="#" class="brand">Parvej</a>
      <div class="menu-btn"></div>
      <div class="navigation">
        <a href="#main">Home</a>
        <a href="#about">About</a>
        <a href="#skills">Skills</a>
        <a href="#services">Services</a>
        <a href="#work">Work</a>
        <a href="#contact">Contact</a>
      </div>
    </header>

    <section class="main" id="main">
      <div class="content">
        <h2>Hello, I'm<br><span>Parvej Sarker</span></h2>
        <div class="animated-text">
          <h3>Web Designer</h3>
          <h3>Web Developer</h3>
          <h3>Motion Graphic Designer</h3>
        </div>
        <a href="#" class="btn">See My Work</a>
        <div class="media-icons">
          <a href="#"><i class="fab fa-facebook-f"></i></a>
          <a href="#"><i class="fab fa-instagram"></i></a>
          <a href="#"><i class="fab fa-twitter"></i></a>
        </div>
      </div>
    </section>

    <section class="about" id="about">
      <div class="title reveal">
        <h2 class="section-title">About Me</h2>
      </div>
      <div class="content">
        <div class="column col-left reveal">
          <div class="img-card">
            <img src="parvej2.jpg" alt="">
          </div>
        </div>
        <div class="column col-right reveal">
          <h2 class="content-title">Hey There! I'm Parvej Sarker</h2>
          <p class="paragraph-text">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.<br><br>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          <a href="#" class="btn">See More</a>
        </div>
      </div>
    </section>

    <section class="skills" id="skills">
      <div class="title reveal">
        <h2 class="section-title">My Skills</h2>
      </div>
      <div class="content">
        <div class="column col-left reveal">
          <h2 class="content-title">My Skills and Experiences</h2>
          <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
          <a href="#" class="btn">See More</a>
        </div>
        <div class="column col-right reveal">
          <div class="bar">
            <div class="info">
              <span>HTML</span>
              <span>95%</span>
            </div>
            <div class="line html"></div>
          </div>
          <div class="bar">
            <div class="info">
              <span>CSS</span>
              <span>85%</span>
            </div>
            <div class="line css"></div>
          </div>
          <div class="bar">
            <div class="info">
              <span>Javascript</span>
              <span>80%</span>
            </div>
            <div class="line javascript"></div>
          </div>
          <div class="bar">
            <div class="info">
              <span>JQuery</span>
              <span>80%</span>
            </div>
            <div class="line jquery"></div>
          </div>
          <div class="bar">
            <div class="info">
              <span>PHP</span>
              <span>75%</span>
            </div>
            <div class="line php"></div>
          </div>
        </div>
      </div>
    </section>

    <section class="services" id="services">
      <div class="title reveal">
        <h2 class="section-title">My Services</h2>
        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
      </div>
      <div class="content">
        <div class="card reveal">
          <div class="service-icon">
            <i class="fas fa-palette"></i>
          </div>
          <div class="info">
            <h3>Web Design</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
          </div>
        </div>
        <div class="card reveal">
          <div class="service-icon">
            <i class="fas fa-file-code"></i>
          </div>
          <div class="info">
            <h3>Web Development</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
          </div>
        </div>
        <div class="card reveal">
          <div class="service-icon">
            <i class="fas fa-object-group"></i>
          </div>
          <div class="info">
            <h3>Motion Graphic Design</h3>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
          </div>
        </div>
      </div>
    </section>

    <section class="work" id="work">
      <div class="title reveal">
        <h2 class="section-title">My Work</h2>
      </div>
      <div class="content">
        <div class="card reveal">
          <div class="card-img">
            <img src="parvej1.jpg" alt="">
          </div>
        </div>
        <div class="card reveal">
          <div class="card-img">
            <img src="parvej1.jpg" alt="">
          </div>
        </div>
        <div class="card reveal">
          <div class="card-img">
            <img src="parvej1.jpg" alt="">
          </div>
        </div>
        <div class="card reveal">
          <div class="card-img">
            <img src="parvej1.jpg" alt="">
          </div>
        </div>
        <div class="card reveal">
          <div class="card-img">
            <img src="parvej1.jpg" alt="">
          </div>
        </div>
        <div class="card reveal">
          <div class="card-img">
            <img src="parvej1.jpg" alt="">
          </div>
        </div>
        <div class="title reveal">
          <a href="#" class="btn">See All</a>
        </div>
      </div>
    </section>

    <section class="contact" id="contact">
      <div class="title reveal">
        <h2 class="section-title">Contact Me</h2>
      </div>
      <div class="content">
        <div class="row">
          <div class="card reveal">
            <div class="contact-icon">
              <i class="fas fa-map-marker-alt"></i>
            </div>
            <div class="info">
              <h3>Address</h3>
              <span>Narsingdi,Dhaka </span>
            </div>
          </div>
          <div class="card reveal">
            <div class="contact-icon">
              <i class="fas fa-phone"></i>
            </div>
            <div class="info">
              <h3>Phone</h3>
              <span>+34566-839754</span>
            </div>
          </div>
          <div class="card reveal">
            <div class="contact-icon">
              <i class="fas fa-envelope"></i>
            </div>
            <div class="info">
              <h3>Email Address</h3>
              <span>parvejsarker@email.com</span>
            </div>
          </div>
          <div class="card reveal">
            <div class="contact-icon">
              <i class="fas fa-globe"></i>
            </div>
            <div class="info">
              <h3>Website</h3>
              <span>mywebsite.com</span>
            </div>
          </div>
        </div>
        <div class="row">
          <div class="contact-form reveal">
            <h3>Send Message</h3>
            <div class="input-box">
              <input type="text" name="" value="" placeholder="Name">
            </div>
            <div class="input-box">
              <input type="text" name="" value="" placeholder="Email">
            </div>
            <div class="input-box">
              <textarea name="name" rows="8" cols="80" placeholder="Message"></textarea>
            </div>
            <div class="input-box">
              <input type="submit" class="send-btn" name="" value="Send">
            </div>
          </div>
        </div>
      </div>
    </section>

    <footer class="footer">
      <span class="footer-title">Parvej Sarker</span>
      <p>Copyright @2021 <a href="#">Parvej Sarker</a>. All Rights Reserved.</p>
    </footer>

    <script>
        //javascript for navigation bar effects on scroll
window.addEventListener("scroll", function(){
  const header = document.querySelector("header");
  header.classList.toggle('sticky', window.scrollY > 0);
});

//javascript for responsive navigation sidebar menu
const menuBtn = document.querySelector(".menu-btn");
const navigation = document.querySelector(".navigation");
const navigationItems = document.querySelectorAll(".navigation a")

menuBtn.addEventListener("click",  () => {
  menuBtn.classList.toggle("active");
  navigation.classList.toggle("active");
});

navigationItems.forEach((navigationItem) => {
  navigationItem.addEventListener("click", () => {
    menuBtn.classList.remove("active");
    navigation.classList.remove("active");
  });
});

//javascript for scroll to top button
const scrollBtn = document.querySelector(".scrollToTop-btn");

window.addEventListener("scroll", function(){
  scrollBtn.classList.toggle("active", window.scrollY > 500);
});

//javascript for scroll back to top on click scroll-to-top button
scrollBtn.addEventListener("click", () => {
  document.body.scrollTop = 0;
  document.documentElement.scrollTop = 0;
});

//javascript for reveal website elements on scroll
window.addEventListener("scroll", reveal);

function reveal(){
  var reveals = document.querySelectorAll(".reveal");

  for(var i = 0; i < reveals.length; i++){
    var windowHeight = window.innerHeight;
    var revealTop = reveals[i].getBoundingClientRect().top;
    var revealPoint = 50;

    if(revealTop < windowHeight - revealPoint){
      reveals[i].classList.add("active");
    }
  }
}
    </script>

  </body>
</html>
