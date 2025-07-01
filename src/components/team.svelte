<script lang='ts'>
  import Footer from "./parts/Footer.svelte";
  import Header from "./parts/Header.svelte";
</script>

<Header />

  <!--  Breadcrumbs  -->
  <div class="breadcrumbs">
    <div class="page-header d-flex align-items-center">
      <div class="container position-relative">
        <div class="row d-flex justify-content-start">
          <div class="col-lg-8 text-left">
            <h2>Full-Team Expertise — From Strategy to Execution</h2>
            <p>Our dedicated team works together to build digital products, create content, and grow your business.</p>
          </div>
        </div>
      </div>
    </div>
    <nav>
      <div class="container">
        <ol>
          <li><a href="/">Home</a></li>
          <li>Expert Team</li>
        </ol>
      </div>
    </nav>
  </div><!-- End Breadcrumbs -->

  <!-- Page Main -->
  <div class="single-page">
    <!--  Our Team Section  -->
    <section id="team" class="team sections-bg">
      <div class="container aos-init aos-animate" data-aos="fade-up">
        <div class="row gy-4">
          <div class="col-xl-3 col-md-6 d-flex aos-init aos-animate" data-aos="fade-up" data-aos-delay="100">
            <div class="member">
              <img src="assets/images/team/team-liya.png" class="img-fluid" alt="">
              <h4>Liya</h4>
              <span>CEO & Project Coordinator</span>
              <div class="social">
                <a href="https://www.instagram.com/liya.ht?igsh=Y3pjNWliM3l1NjBk"><i class="bi bi-instagram"></i></a>
                <a href="https://t.me/liyaht"><i class="bi bi-telegram"></i></a>
                <a href="https://www.tiktok.com/@liya.ht?_t=ZS-8xfVhXLLWeQ&_r=1"><i class="bi bi-tiktok"></i></a>
                <a href="https://www.linkedin.com/in/liya-khatkova-062320364/"><i class="bi bi-linkedin"></i></a>
              </div>
            </div>
          </div><!-- End Team Member -->

          <div class="col-xl-3 col-md-6 d-flex aos-init aos-animate" data-aos="fade-up" data-aos-delay="200">
            <div class="member">
              <img src="assets/images/team/team-vova.png" class="img-fluid" alt="">
              <h4>Vladimir</h4>
              <span>Full Stack Developer</span>
              <div class="social">
                <a href="https://www.instagram.com/_vovchickkk_?igsh=MWY2eXhsNm8xdWFwNA=="><i class="bi bi-instagram"></i></a>
                <a href="https://t.me/v_gatsko"><i class="bi bi-telegram"></i></a>
                <a href="https://www.linkedin.com/in/vladimir-gatsko-1571902ab/"><i class="bi bi-linkedin"></i></a>
              </div>
            </div>
          </div><!-- End Team Member -->

          <div class="col-xl-3 col-md-6 d-flex aos-init aos-animate" data-aos="fade-up" data-aos-delay="300">
            <div class="member">
              <img src="assets/images/team/team-oleg.png" class="img-fluid" alt="">
              <h4>Oleg</h4>
              <span>ML Engineer & Web Developer</span>
              <div class="social">
                <a href="https://www.instagram.com/hip_oleg?igsh=bG01Z2h5YXlsMDVy"><i class="bi bi-instagram"></i></a>
                <a href="https://t.me/OlegRubenchik"><i class="bi bi-telegram"></i></a>
                <a href="https://www.linkedin.com/in/oleg-rubenchik-905955296/"><i class="bi bi-linkedin"></i></a>
              </div>
            </div>
          </div><!-- End Team Member -->

          <div class="col-xl-3 col-md-6 d-flex aos-init aos-animate" data-aos="fade-up" data-aos-delay="400">
            <div class="member">
              <img src="assets/images/team/team-sergo.png" class="img-fluid" alt="">
              <h4>Sergey</h4>
              <span>Content Creator & Video Editor</span>
              <div class="social">
                <a href="https://www.instagram.com/__gatsko__?igsh=MXZ5NGZ0eXB0czV0Zg%3D%3D&utm_source=qr"><i class="bi bi-instagram"></i></a>
                <a href="https://t.me/GATSKOO"><i class="bi bi-telegram"></i></a>
                <a href="https://www.tiktok.com/@_gatsko__?_t=ZS-8xfW5R6snBK&_r=1"><i class="bi bi-tiktok"></i></a>
              </div>
            </div>
          </div><!-- End Team Member -->

          <div class="col-xl-3 col-md-6 d-flex aos-init aos-animate" data-aos="fade-up" data-aos-delay="400">
            <div class="member">
              <img src="assets/images/team/team-nastya.png" class="img-fluid" alt="">
              <h4>Anastasia</h4>
              <span>Video Editor</span>
              <div class="social">
                <a href="https://www.instagram.com/just__human__?igsh=aml5dnJnZ2pzMW1v"><i class="bi bi-instagram"></i></a>
                <a href="https://t.me/goodmushroom"><i class="bi bi-telegram"></i></a>
                <a href="https://www.linkedin.com/in/anastasiia-smirnova-9b0200333/"><i class="bi bi-linkedin"></i></a>
              </div>
            </div>
          </div><!-- End Team Member -->

        
        </div>

      </div>
    </section>
    <!-- End Our Team Section -->
  </div>
  <!-- Page Main -->

  <Footer />

  <!-- svelte-ignore a11y_consider_explicit_label -->
  <!-- svelte-ignore a11y_invalid_attribute -->
  <a href="#" class="scroll-top d-flex align-items-center justify-content-center active">
    <i class="bi bi-arrow-up-short"></i>
  </a>
