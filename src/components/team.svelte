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
            <h2>Expert Team</h2>
            <p>Our team of experienced professionals is committed to understanding your unique business needs</p>
          </div>
        </div>
      </div>
    </div>
    <nav>
      <div class="container">
        <ol>
          <li><a href="index.html">Home</a></li>
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
              <img src="assets/images/team/team-1.jpg" class="img-fluid" alt="">
              <h4>Jhone Bi</h4>
              <span>Application Manager</span>
              <div class="social">
                <a href=""><i class="bi bi-twitter-x"></i></a>
                <a href=""><i class="bi bi-facebook"></i></a>
                <a href=""><i class="bi bi-linkedin"></i></a>
                <a href=""><i class="bi bi-instagram"></i></a>
              </div>
            </div>
          </div><!-- End Team Member -->

          <div class="col-xl-3 col-md-6 d-flex aos-init aos-animate" data-aos="fade-up" data-aos-delay="200">
            <div class="member">
              <img src="assets/images/team/team-2.jpg" class="img-fluid" alt="">
              <h4>Sani Awesome</h4>
              <span>Social Media</span>
              <div class="social">
                <a href=""><i class="bi bi-twitter-x"></i></a>
                <a href=""><i class="bi bi-facebook"></i></a>
                <a href=""><i class="bi bi-linkedin"></i></a>
                <a href=""><i class="bi bi-instagram"></i></a>
              </div>
            </div>
          </div><!-- End Team Member -->

          <div class="col-xl-3 col-md-6 d-flex aos-init aos-animate" data-aos="fade-up" data-aos-delay="300">
            <div class="member">
              <img src="assets/images/team/team-3.jpg" class="img-fluid" alt="">
              <h4>Andrio Willi</h4>
              <span>Content Writer</span>
              <div class="social">
                <a href=""><i class="bi bi-twitter-x"></i></a>
                <a href=""><i class="bi bi-facebook"></i></a>
                <a href=""><i class="bi bi-linkedin"></i></a>
                <a href=""><i class="bi bi-instagram"></i></a>
              </div>
            </div>
          </div><!-- End Team Member -->

          <div class="col-xl-3 col-md-6 d-flex aos-init aos-animate" data-aos="fade-up" data-aos-delay="400">
            <div class="member">
              <img src="assets/images/team/team-4.jpg" class="img-fluid" alt="">
              <h4>Afa Jonson</h4>
              <span>Business Manager</span>
              <div class="social">
                <a href=""><i class="bi bi-twitter-x"></i></a>
                <a href=""><i class="bi bi-facebook"></i></a>
                <a href=""><i class="bi bi-linkedin"></i></a>
                <a href=""><i class="bi bi-instagram"></i></a>
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

  <a href="#" class="scroll-top d-flex align-items-center justify-content-center active">
    <i class="bi bi-arrow-up-short"></i>
  </a>
