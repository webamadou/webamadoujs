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
      <h1 class="sitename">Papa Amadou A. BA</h1>
    </a>

    <div class="social-links text-center">
      <a href="https://x.com/webamadou" class="twitter" target="_blank"><i class="bi bi-twitter-x"></i></a>
      <a href="https://linkedin.com/in/webamadou" class="linkedin" target="_blank"><i class="bi bi-linkedin"></i></a>
      <a href="https://github.com/webamadou" class="github" target="_blank"><i class="bi bi-github"></i></a>
    </div>

    <nav id="navmenu" class="navmenu">
      <ul>
        <li><a href="#hero" class="active"><i class="bi bi-house navicon"></i> HOME</a></li>
        <li><a href="#about"><i class="bi bi-person navicon"></i> WHO AM I</a></li>
        <li><a href="#resume"><i class="bi bi-file-earmark-text navicon"></i> RESUME</a></li>
        <li><a href="#portfolio"><i class="bi bi-images navicon"></i> PORTFOLIO</a></li>
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
        <p>I am a <span class="typed" data-typed-items="Laravel / PHP Developer,SaaS Application Developer,API &amp; Backend Developer,Remote Software Consultant,Product-minded Web Developer"></span></p>
      </div>
    </section>
    <!-- /Hero Section -->

    <!-- About Section -->
    <section id="about" class="about section">
      <div class="container section-title" data-aos="fade-up">
        <h2>About</h2>
        <p>I am a Laravel / PHP developer with more than 10 years of experience building web applications, APIs and business platforms. I mainly work with Laravel, PHP, JavaScript, Vue.js and React, with a strong focus on clean code, reliability and practical product delivery.</p>
      </div>

      <div class="container" data-aos="fade-up" data-aos-delay="100">
        <div class="row gy-4 justify-content-center">
          <div class="col-lg-4">
            <img src="assets/img/my-profile-img.jpeg" class="img-fluid" alt="Papa Amadou A. BA">
          </div>
          <div class="col-lg-8 content">
            <h2>Senior Laravel / PHP Developer.</h2>
            <p class="fst-italic py-3">
              I specialize in Laravel, PHP, APIs and SaaS platforms. I also work with JavaScript, Vue.js, React and WordPress when needed.
            </p>
            <div class="row">
              <div class="col-lg-6">
                <ul>
                  <li><i class="bi bi-chevron-right"></i> <strong>Experience:</strong> <span>10+ years</span></li>
                  <li><i class="bi bi-chevron-right"></i> <strong>GitHub:</strong> <span>github.com/webamadou</span></li>
                  <li><i class="bi bi-chevron-right"></i> <strong>Phone:</strong> <span>+221 77 269 35 16</span></li>
                  <li><i class="bi bi-chevron-right"></i> <strong>City:</strong> <span>Dakar, Senegal</span></li>
                </ul>
              </div>
              <div class="col-lg-6">
                <ul>
                  <li><i class="bi bi-chevron-right"></i> <strong>Availability:</strong> <span>Remote / Freelance</span></li>
                  <li><i class="bi bi-chevron-right"></i> <strong>GitLab:</strong> <span>gitlab.com/webamadou</span></li>
                  <li><i class="bi bi-chevron-right"></i> <strong>Email:</strong> <span>paab26@live.fr</span></li>
                </ul>
              </div>
            </div>
            <p class="py-3">
              I have worked remotely with international teams, including teams in the Netherlands, France, Canada, Benin and Australia. I enjoy building useful products, improving existing systems and turning complex business needs into simple, maintainable web applications.
            </p>
          </div>
        </div>
      </div>
    </section>
    <!-- /About Section -->

    <!-- Resume Section -->
    <section id="resume" class="resume section">
      <div class="container section-title" data-aos="fade-up">
        <h2>Resume</h2>
      </div>

      <div class="container">
        <div class="row">
          <div class="col-lg-8" data-aos="fade-up" data-aos-delay="200">

            <h3 class="resume-title">Summary</h3>
            <div class="resume-item pb-0">
              <p>
                Experienced Laravel / PHP developer focused on building reliable web applications, APIs and SaaS platforms. I have worked remotely with international teams and contributed to products in the energy, education, real estate and comparison sectors. I care about clean architecture, maintainability, performance and delivering practical features that solve real business problems.
              </p>
            </div>

            <h3 class="resume-title">Education</h3>
            <div class="resume-item">
              <h4>Professional Licence in Web Development and Administration</h4>
              <h5>2006 – 2011</h5>
              <p><em>Université Alioune Diop, Bambey, Senegal</em></p>
            </div>

            <h3 class="resume-title">Professional Experience</h3>

            <div class="resume-item">
              <h4>Remote PHP / Laravel Consultant — KYOS Energy Consulting</h4>
              <h5>2019 – Present</h5>
              <p><em>Remote</em></p>
              <ul>
                <li>Develop and maintain PHP / Laravel features for SaaS products used in the energy sector.</li>
                <li>Build and integrate APIs, data workflows and backend services.</li>
                <li>Contribute to the modernization of legacy PHP / CodeIgniter systems.</li>
                <li>Improve application reliability, maintainability and performance.</li>
                <li>Work remotely with an international team using modern development workflows.</li>
              </ul>
            </div>

            <div class="resume-item">
              <h4>Freelance Web Developer</h4>
              <h5>2017 – 2019</h5>
              <p><em>Freelance</em></p>
              <ul>
                <li>Built websites and custom web applications for clients across different sectors.</li>
                <li>Delivered web programming training for GALIMATECH.</li>
                <li>Built and maintained the Galima Academy website (galima-academy.com).</li>
                <li>Worked with PHP, WordPress, JavaScript and frontend technologies.</li>
              </ul>
            </div>

            <div class="resume-item">
              <h4>Junior Web Programmer — Africa24 Network Agency</h4>
              <h5>2016 – 2017</h5>
              <p><em>Point E, Dakar, Senegal</em></p>
              <ul>
                <li>Contributed to building an events management web application using Silex.</li>
                <li>Rebuilt the front-end design of africa24.com.</li>
                <li>Managed the media tech server for Africa24 channel.</li>
              </ul>
            </div>

            <div class="resume-item">
              <h4>PHP Developer — TRACOM-INT</h4>
              <h5>2015 – 2016</h5>
              <p><em>Dakar, Senegal</em></p>
              <ul>
                <li>Rebuilt the company website with WordPress, including a fully custom theme.</li>
                <li>Redesigned the web interface of the GIM-Online payment gateway.</li>
              </ul>
            </div>

            <div class="resume-item">
              <h4>Co-Founder — Elmadeal.com</h4>
              <h5>2014 – 2018</h5>
              <p><em>Dakar, Senegal</em></p>
              <ul>
                <li>Created and managed a web platform for booking beauty salons and spas in Dakar.</li>
              </ul>
            </div>

            <div class="resume-item">
              <h4>PHP Developer — SUNTELECOM</h4>
              <h5>2013 – 2014</h5>
              <p><em>Dakar, Senegal</em></p>
              <ul>
                <li>Built an internal order management application for Nestlé Senegal.</li>
                <li>Participated in building a real estate management web application.</li>
              </ul>
            </div>

            <div class="resume-item">
              <h4>Front-End Developer Intern</h4>
              <h5>2012 – 2013</h5>
              <p><em>Dakar, Senegal</em></p>
              <ul>
                <li>Converted PSD designs into HTML/CSS and built a custom WordPress theme.</li>
                <li>Developed the front end of on-umami.com using Ruby on Rails.</li>
              </ul>
            </div>

          </div>
        </div>
      </div>
    </section>
    <!-- /Resume Section -->

    <!-- Portfolio Section -->
    <section id="portfolio" class="portfolio section">
      <div class="container section-title" data-aos="fade-up">
        <h2>Portfolio</h2>
        <p>A selection of projects I have built or contributed to as a developer and consultant.</p>
      </div>

      <div class="container" data-aos="fade-up" data-aos-delay="100">
        <div class="row gy-4">

          <!-- Comparek -->
          <div class="col-lg-4 col-md-6" data-aos="fade-up" data-aos-delay="100">
            <div class="card h-100" style="border:none; box-shadow: 0 4px 24px rgba(0,0,0,0.09); border-radius: 8px; overflow: hidden;">
              <div style="background: #149ddd; padding: 1.8rem 1.5rem;">
                <h4 style="color:#fff; margin:0; font-size:1.2rem; font-weight:700;">Comparek</h4>
                <p style="color:rgba(255,255,255,0.8); margin:0.4rem 0 0; font-size:0.82rem;">Comparison Platform · Laravel · Livewire</p>
              </div>
              <div class="card-body p-4">
                <p class="mb-3" style="font-size:0.93rem;">A comparison platform for essential services in Senegal, helping users compare schools, banks and telecom offers.</p>
                <ul style="font-size:0.88rem; padding-left:1.2rem; color:#555;">
                  <li>Built and structured a multi-sector comparison platform.</li>
                  <li>Developed back-office features for managing banks, schools, telecom offers and comparison criteria.</li>
                  <li>Integrated SEO, analytics and monitoring tools.</li>
                  <li>Added an AI-powered chatbot for user assistance.</li>
                </ul>
                <p class="mt-3 mb-0" style="font-size:0.8rem; color:#888;"><strong>Stack:</strong> Laravel · Livewire · Bootstrap · MySQL · AI integration</p>
              </div>
            </div>
          </div>

          <!-- KYOS SaaS -->
          <div class="col-lg-4 col-md-6" data-aos="fade-up" data-aos-delay="200">
            <div class="card h-100" style="border:none; box-shadow: 0 4px 24px rgba(0,0,0,0.09); border-radius: 8px; overflow: hidden;">
              <div style="background: #0d6e8e; padding: 1.8rem 1.5rem;">
                <h4 style="color:#fff; margin:0; font-size:1.2rem; font-weight:700;">KYOS Energy SaaS</h4>
                <p style="color:rgba(255,255,255,0.8); margin:0.4rem 0 0; font-size:0.82rem;">SaaS Platform · PHP · Laravel · APIs</p>
              </div>
              <div class="card-body p-4">
                <p class="mb-3" style="font-size:0.93rem;">Professional contribution to SaaS products in the energy sector, serving international clients.</p>
                <ul style="font-size:0.88rem; padding-left:1.2rem; color:#555;">
                  <li>Built and maintained backend features for energy-sector SaaS products.</li>
                  <li>Integrated APIs and business data workflows.</li>
                  <li>Contributed to the modernization of legacy systems.</li>
                  <li>Improved application reliability and maintainability.</li>
                </ul>
                <p class="mt-3 mb-0" style="font-size:0.8rem; color:#888;"><strong>Stack:</strong> PHP · Laravel · MySQL · REST APIs · JavaScript</p>
              </div>
            </div>
          </div>

          <!-- Ndawli -->
          <div class="col-lg-4 col-md-6" data-aos="fade-up" data-aos-delay="300">
            <div class="card h-100" style="border:none; box-shadow: 0 4px 24px rgba(0,0,0,0.09); border-radius: 8px; overflow: hidden;">
              <div style="background: #1a6b46; padding: 1.8rem 1.5rem;">
                <h4 style="color:#fff; margin:0; font-size:1.2rem; font-weight:700;">Ndawli</h4>
                <p style="color:rgba(255,255,255,0.8); margin:0.4rem 0 0; font-size:0.82rem;">SaaS Chatbot · Laravel · Vue.js · Inertia</p>
              </div>
              <div class="card-body p-4">
                <p class="mb-3" style="font-size:0.93rem;">A SaaS chatbot designed to help businesses answer customer questions, qualify leads and improve customer communication.</p>
                <ul style="font-size:0.88rem; padding-left:1.2rem; color:#555;">
                  <li>Multi-tenant SaaS architecture.</li>
                  <li>Business knowledge base with AI fallback integration.</li>
                  <li>Lead qualification and conversation management.</li>
                </ul>
                <p class="mt-3 mb-0" style="font-size:0.8rem; color:#888;"><strong>Stack:</strong> Laravel · Inertia · Vue.js · MySQL · AI integration</p>
              </div>
            </div>
          </div>

        </div>
      </div>
    </section>
    <!-- /Portfolio Section -->

    <!-- Contact Section -->
    <section id="contact" class="contact section">

      <div class="container section-title" data-aos="fade-up">
        <h2>Contact</h2>
        <p>Interested in working together? I am available for remote Laravel / PHP development, SaaS projects, API integrations and technical consulting.</p>
      </div>

      <div class="container" data-aos="fade-up" data-aos-delay="100">

        <div class="row gy-4">

          <div class="col-lg-8 offset-2">

            <div class="info-wrap">
              <div class="info-item d-flex" data-aos="fade-up" data-aos-delay="200">
                <i class="bi bi-geo-alt flex-shrink-0"></i>
                <div>
                  <h3>Location</h3>
                  <p>Dakar, Senegal — available remotely worldwide</p>
                </div>
              </div>

              <div class="info-item d-flex" data-aos="fade-up" data-aos-delay="300">
                <i class="bi bi-telephone flex-shrink-0"></i>
                <div>
                  <h3>Phone</h3>
                  <p>+221 77 269 35 16</p>
                </div>
              </div>

              <div class="info-item d-flex" data-aos="fade-up" data-aos-delay="400">
                <i class="bi bi-envelope flex-shrink-0"></i>
                <div>
                  <h3>Email</h3>
                  <p>paab26@live.fr</p>
                </div>
              </div>

              <div class="info-item d-flex" data-aos="fade-up" data-aos-delay="500">
                <i class="bi bi-linkedin flex-shrink-0"></i>
                <div>
                  <h3>LinkedIn</h3>
                  <p><a href="https://linkedin.com/in/webamadou" target="_blank" style="color:inherit;">linkedin.com/in/webamadou</a></p>
                </div>
              </div>

              <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d978.6892855618461!2d-17.49354638004789!3d14.733389164543492!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e0!3m2!1sen!2ssn!4v1735237318278!5m2!1sen!2ssn" frameborder="0" style="border:0; width: 100%; height: 270px;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
            </div>
          </div>

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
/* styles are handled via src/assets/css/main.css */
</style>
