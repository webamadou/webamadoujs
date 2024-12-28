<template>
  <div id="app">
    <header id="header" class="header dark-background d-flex flex-column">
    <i class="header-toggle d-xl-none bi bi-list"></i>

    <div class="profile-img"
      style="background: url('assets/img/my-profile-img.jpeg');
                background-repeat: no-repeat;
                background-position: center;
                background-size: cover;">
    </div>

    <a href="index.html" class="logo d-flex align-items-center justify-content-center">
      <!-- Uncomment the line below if you also wish to use an image logo -->
      <!-- <img src="assets/img/logo.png" alt=""> -->
      <h1 class="sitename">Papa Amadou A. BA</h1>
    </a>

    <div class="social-links text-center">
      <!-- <a href="#" class="facebook"><i class="bi bi-facebook"></i></a> -->
      <!-- <a href="#" class="google-plus"><i class="bi bi-skype"></i></a> -->
      <a href="https://x.com/webamadou" class="twitter" target="_blank"><i class="bi bi-twitter-x"></i></a>
      <a href="https://linkedin.com/in/webamadou" class="linkedin" target="_blank"><i class="bi bi-linkedin"></i></a>
      <a href="https://instagram.com/webamadou" class="instagram" target="_blank"><i class="bi bi-instagram"></i></a>
    </div>

    <nav id="navmenu" class="navmenu">
      <ul>
        <li><a href="#hero" class="active"><i class="bi bi-house navicon"></i>HOME</a></li>
        <li><a href="#about"><i class="bi bi-person navicon"></i>WHO AM I</a></li>
        <li><a href="#resume"><i class="bi bi-file-earmark-text navicon"></i>RESUME</a></li>
        <li><a href="#portfolio"><i class="bi bi-images navicon"></i> PORTFOLIO</a></li>
        <!-- <li><a href="#services"><i class="bi bi-hdd-stack navicon"></i> Services</a></li>
        <li class="dropdown"><a href="#"><i class="bi bi-menu-button navicon"></i> <span>Dropdown</span> <i class="bi bi-chevron-down toggle-dropdown"></i></a>
          <ul>
            <li><a href="#">Dropdown 1</a></li>
            <li class="dropdown"><a href="#"><span>Deep Dropdown</span> <i class="bi bi-chevron-down toggle-dropdown"></i></a>
              <ul>
                <li><a href="#">Deep Dropdown 1</a></li>
                <li><a href="#">Deep Dropdown 2</a></li>
                <li><a href="#">Deep Dropdown 3</a></li>
                <li><a href="#">Deep Dropdown 4</a></li>
                <li><a href="#">Deep Dropdown 5</a></li>
              </ul>
            </li>
            <li><a href="#">Dropdown 2</a></li>
            <li><a href="#">Dropdown 3</a></li>
            <li><a href="#">Dropdown 4</a></li>
          </ul>
        </li> -->
        <li><a href="#contact"><i class="bi bi-envelope navicon"></i> CONTACT</a></li>
      </ul>
    </nav>
  </header>

  <main class="main">
    <!-- Hero Section -->
    <section id="hero" class="hero section dark-background">
      <img src="assets/img/hero-bg.jpeg" alt="" data-aos="fade-in" class="">
      <div class="container" data-aos="fade-up" data-aos-delay="100">
        <h2>Papa Amadou A. BA</h2>
        <p>I build web applications with <span class="typed" data-typed-items="Laravel, Wordpress, VueJs, Figma, Sanity, Gasby">  </span><span class="typed-cursor typed-cursor--blink" aria-hidden="true"></span><span class="typed-cursor typed-cursor--blink" aria-hidden="true"></span></p>
      </div>
    </section>
    <!-- /Hero Section -->
    
    <!-- About Section -->
    <section id="about" class="about section">
      <!-- Section Title -->
      <div class="container section-title" data-aos="fade-up">
        <h2>About</h2>
        <p>I'm a web developer since 2012. I work mainly with PHP. I also have a solid knowledge of JavaScript and ReactJS. I am naturally curious, methodical, and ambitious.</p>
      </div><!-- End Section Title -->

      <div class="container" data-aos="fade-up" data-aos-delay="100">
        <div class="row gy-4 justify-content-center">
          <div class="col-lg-4">
            <img src="assets/img/my-profile-img.jpeg" class="img-fluid" alt="">
          </div>
          <div class="col-lg-8 content">
            <h2>Web Developer.</h2>
            <p class="fst-italic py-3">I am specialized in PHP. The tools I use the most are Laravel and WordPress. I also work with ReactJS and VueJS. </p>
            <div class="row">
              <div class="col-lg-6">
                <ul>
                  <li><i class="bi bi-chevron-right"></i> <strong>Birthday:</strong> <span>Jun 1986</span></li>
                  <li><i class="bi bi-chevron-right"></i> <strong>Website:</strong> <span>www.github.com/webamadou</span></li>
                  <li><i class="bi bi-chevron-right"></i> <strong>Phone:</strong> <span>+221 77 269 35 16</span></li>
                  <li><i class="bi bi-chevron-right"></i> <strong>City:</strong> <span>Dakar, SENEGAL</span></li>
                </ul>
              </div>
              <div class="col-lg-6">
                <ul>
                  <!-- <li><i class="bi bi-chevron-right"></i> <strong>Age:</strong> <span>30</span></li> -->
                  <li><i class="bi bi-chevron-right"></i> <strong>Degree:</strong> <span>Master</span></li>
                  <li><i class="bi bi-chevron-right"></i> <strong>Email:</strong> <span>paab26@live.fr</span></li>
                  <!-- <li><i class="bi bi-chevron-right"></i> <strong>Freelance:</strong> <span>-</span></li> -->
                </ul>
              </div>
            </div>
            <p class="py-3">
              One of the things I enjoy most about my job is the opportunity to connect with people from all over the world. I have the chance to work or interact with people in the Netherlands, France, Canada, Benin or Australia. These exchanges have always been beneficial for them and for me on a professional and human level.
            </p>
          </div>
        </div>
      </div>
    </section>
    <!-- /About Section -->


    <!-- Resume Section -->
    <section id="resume" class="resume section">
      <!-- Section Title -->
      <div class="container section-title" data-aos="fade-up">
        <h2>Resume</h2>
      </div><!-- End Section Title -->

      <div class="container">
        <div class="row">
          <div class="col-lg-8" data-aos="fade-up" data-aos-delay="200">
            <h3 class="resume-title">Sumary</h3>

            <h3 class="resume-title">Education</h3>
            <div class="resume-item">
              <h4>Professional License in Web Development &amp; Administration</h4>
              <h5>2006 - 2011</h5>
              <p><em>Univesriste Alioune Diop, Bambey, SENEGAL</em></p>
            </div><!-- Edn Resume Item -->

            <!-- <div class="resume-item">
              <h4>Bachelor of Fine Arts &amp; Graphic Design</h4>
              <h5>2010 - 2014</h5>
              <p><em>Rochester Institute of Technology, Rochester, NY</em></p>
              <p>Quia nobis sequi est occaecati aut. Repudiandae et iusto quae reiciendis et quis Eius vel ratione eius unde vitae rerum voluptates asperiores voluptatem Earum molestiae consequatur neque etlon sader mart dila</p>
            </div> --><!-- Edn Resume Item -->

            <h3 class="resume-title">Professional Experience</h3>
            <div class="resume-item">
              <H4>REMOTE PHP-LARAVEL CONSULTANT AT KYOS ENERGY CONSULTING</h4>
              <h5>2019 - Present</h5>
              <p><em>Remote</em></p>
              <ul>
                <li>Development of the PHP based SaaS product of KYOS</li>
              </ul>
            </div><!-- Edn Resume Item -->

            <div class="resume-item">
              <h4>FREELANCING</h4>
              <h5>2017 - 2019</h5>
              <p><em>FREELANCE</em></p>
              <ul>
                <li>In charge of Web programming training Offered by GALIMATECH.</li>
                <li>Build the website https://galima-academy.com.</li>
                <li>Built websites gnsafrique.com, excellenc6.com, immovirtuo.com, lagenda.quebec</li>
              </ul>
            </div><!-- Edn Resume Item -->

            <div class="resume-item">
              <h4>JUNIOR WEB PROGRAMMER AT AFRICA24 NETWORK AGENCY</h4>
              <h5>2016 - 2017</h5>
              <p><em>Point E, Dakar, SENEGAL</em></p>
              <ul>
                <li>I was part of a team that built an events management web application with silex.</li>
                <li> I also rebuild the design of the website africa24.com.</li>
                <li>I was also in charge of managing the media tech server of Africa24 channel. </li>
              </ul>
            </div><!-- Edn Resume Item -->

            <div class="resume-item">
              <h4>PHP PROGRAMMER at TRACOM-INT</h4>
              <h5>2015 - 2016</h5>
              <p><em>Mariste, Dakar, SENEGAL</em></p>
              <ul>
                <li>I entirely rebuilt the website of the company with WordPress: http://tracom-int.com creating a custom theme for that.</li>
                <li>I also redesign the web interface of the payment gateway GIM-Online.</li>
              </ul>
            </div><!-- Edn Resume Item -->

            <div class="resume-item">
              <h4>Co-Founder of elmadeal.com</h4>
              <h5>2014 - 2018</h5>
              <p><em> Dakar, SENEGAL</em></p>
              <ul>
                <li>I created and managed a web platform that allowed reservations at the beauty salons and spa in the city of Dakar.</li>
              </ul>
            </div><!-- Edn Resume Item -->

            <div class="resume-item">
              <h4>PHP PROGRAMMER SUNTELECOM</h4>
              <h5>2013 - 2014</h5>
              <p><em> Dakar, SENEGAL</em></p>
              <ul>
                <li>created an app to manage inner commands at NESTLE Senegal. I also participated in building a web application for real state management.</li>
              </ul>
            </div><!-- Edn Resume Item -->

            <div class="resume-item">
              <h4>INTERNSHIP FRONT END DEVELOPPER</h4>
              <h5>2012 - 2013</h5>
              <p><em> Dakar, SENEGAL</em></p>
              <ul>
                <li>Worked on turning PSD file into HTML-CSS and create a WordPress theme from it. In charge of creating the front-end of the website on-umami.com with RAILS</li>
              </ul>
            </div><!-- Edn Resume Item -->

          </div>

        </div>
      </div>
    </section>
    <!-- /Resume Section -->


    <!-- Contact Section -->
    <section id="contact" class="contact section">

      <!-- Section Title -->
      <div class="container section-title" data-aos="fade-up">
        <h2>Contact</h2>
        <p>Necessitatibus eius consequatur ex aliquid fuga eum quidem sint consectetur velit</p>
      </div><!-- End Section Title -->

      <div class="container" data-aos="fade-up" data-aos-delay="100">

        <div class="row gy-4">

          <div class="col-lg-8 offset-2">

            <div class="info-wrap">
              <div class="info-item d-flex" data-aos="fade-up" data-aos-delay="200">
                <i class="bi bi-geo-alt flex-shrink-0"></i>
                <div>
                  <h3>Address</h3>
                  <p>Ouakam P7, Dakar, SENEGAL</p>
                </div>
              </div><!-- End Info Item -->

              <div class="info-item d-flex" data-aos="fade-up" data-aos-delay="300">
                <i class="bi bi-telephone flex-shrink-0"></i>
                <div>
                  <h3>Call Us</h3>
                  <p>+221 77 269 35 16</p>
                </div>
              </div><!-- End Info Item -->

              <div class="info-item d-flex" data-aos="fade-up" data-aos-delay="400">
                <i class="bi bi-envelope flex-shrink-0"></i>
                <div>
                  <h3>Email Us</h3>
                  <p>paab26@live.fr</p>
                </div>
              </div><!-- End Info Item -->

              <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d978.6892855618461!2d-17.49354638004789!3d14.733389164543492!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e0!3m2!1sen!2ssn!4v1735237318278!5m2!1sen!2ssn" frameborder="0" style="border:0; width: 100%; height: 270px;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe> 
            </div>
          </div>
          <!-- End Contact Form -->

        </div>

      </div>
    </section>
    <!-- /Contact Section -->

</main>

  <footer id="footer" class="footer position-relative">
    <div class="container">
      <div class="credits">
        <a href="https://github.com/webamadou">webamadou</a>
      </div>
    </div>
  </footer>
  </div>
</template>

<script>
export default {
  name: "App",
};
</script>

<style>
/* Add some basic styles *
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

header {
  background: #333;
  color: #fff;
  padding: 1rem;
  position: sticky;
  top: 0;
}

header nav a {
  color: #fff;
  margin: 0 1rem;
  text-decoration: none;
}

main section {
  padding: 2rem;
  margin: 2rem 0;
  border: 1px solid #ddd;
}

footer {
  background: #333;
  color: #fff;
  text-align: center;
  padding: 1rem 0;
}*/
</style>
