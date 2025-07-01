<script lang='ts'>
  import Footer from "./parts/Footer.svelte";
  import Header from "./parts/Header.svelte";
</script>

<Header />

<!--  Hero Section  -->
<section id="hero" class="hero sticked-header-offset">
  <div id="particles-js"></div>
  <div id="repulse-circle-div"></div>
  <div class="container position-relative">
    <div class="row gy-5 aos-init aos-animate">
      <div
        class="col-lg-6 d-flex flex-column justify-content-center text-left caption"
      >
        <h1 data-aos="fade-up">
          Full-Service Business Development and digital growth — From Product
          Creation to Social Media
        </h1>
        <h2 data-aos="fade-up">
          We help you build your digital product, launch your brand, and manage
          your social media — all in one place.
        </h2>
        <div class="social" data-aos="fade-up">
          <!--<a href=""><i class="bi bi-twitter-x"></i></a>-->
          <!--<a href=""><i class="bi bi-facebook"></i></a> -->
          <a href="https://www.linkedin.com/in/liya-khatkova-062320364"
            ><i class="bi bi-linkedin"></i></a
          >
          <a
            href="https://www.instagram.com/keyscalelab?igsh=MTNqa2dtMWd5eG5rbA=="
            ><i class="bi bi-instagram"></i></a
          >
        </div>
        <div class="d-flex justify-content-start">
          <a class="default-theme-btn-one" href="mailto:lillu.ocean@gmail.com"
            >Contact Us<span></span></a
          >
          <a href="#pricing" class="default-theme-btn-two" data-aos="fade-up"
            >Start Your Project<span></span></a
          >
        </div>
      </div>
      <div class="col-lg-6 d-flex justify-content-center hero-photo">
        <img
          src="assets/images/LiyaHt.svg"
          class="img-fluid rounded-4"
          alt=""
        />
      </div>
    </div>
  </div>
</section>
<!-- End Hero Section -->

<!-- Start 1 Service Section -->
<div id="services" class="section">
  <div class="top-icon-box position-relative">
    <div class="container position-relative">
      <div class="row gy-4">
        <div class="section-header" data-aos="fade-up">
          <h2>
            If Your Goal Is Brand Awareness, Personal Brand Growth, and Reach —
            Here’s How We Help on Social Media
          </h2>
          <p>We create, publish and grow your brand across all platforms</p>
        </div>

        <div class="col-xl-4 col-md-6" data-aos="fade-right">
          <a href="single-service.html">
            <div class="icon-box">
              <div class="icon"><i class="flaticon-001-edit-tools"></i></div>
              <h4 class="title">Content Planning & Strategy</h4>
              <p>
                We analyze your existing social media (or build it from
                scratch), create a unified brand concept, design your profile,
                and prepare a content plan tailored to your goals.
              </p>
              <span></span>
            </div>
          </a>
        </div>
        <!--End Icon Box -->

        <div class="col-xl-4 col-md-6" data-aos="fade-left">
          <a href="single-service.html">
            <div class="icon-box">
              <div class="icon"><i class="flaticon-090-advertising"></i></div>
              <h4 class="title">Video Editing & Publishing</h4>
              <p>
                We edit videos with music, captions, and copywriting, prepare
                clear filming scripts, and support you through shooting. Daily
                publishing and revisions until the result meets your
                expectations.
              </p>
              <span></span>
            </div>
          </a>
        </div>
        <!--End Icon Box -->

        <div class="col-xl-4 col-md-6" data-aos="fade-right">
          <a href="single-service.html">
            <div class="icon-box">
              <div class="icon"><i class="flaticon-075-earth-globe"></i></div>
              <h4 class="title">Audience Engagement & Support</h4>
              <p>
                We handle comments, DMs, and audience questions to build real
                connections. Weekly performance reports keep you informed on
                growth and engagement.
              </p>
              <span></span>
            </div>
          </a>
        </div>
        <!--End Icon Box -->
        <!--<div class="d-flex justify-content-center mt-4">
            <a href="#services" class="default-theme-btn-two" data-aos="fade-up">Explore Packages<span></span></a>
          </div> -->
      </div>
    </div>
  </div>
</div>
<!-- End 1 Service Section -->

<!--  Testimonials Section  -->
<section id="testimonials" class="testimonials">
  <div class="container" data-aos="fade-up">
    <div class="section-header">
      <h2>See the Results of Our Work — Smart Social Growth</h2>
    </div>

    <div class="slides-3 swiper" data-aos="fade-up" data-aos-delay="100">
      <div class="swiper-wrapper">
        <div class="swiper-slide">
          <div class="testimonial-wrap">
            <div class="testimonial-item text-center">
              <img
                src="assets/images/testimonials/liyahttt.png"
                class="testimonial-img mb-3"
                alt="Liya HT"
              />
              <h3>@liya.ht</h3>
              <h4>TikTok</h4>
              <p>
                <i class="bi bi-quote quote-icon-left"></i>
                Built my personal TikTok to 200k+ in one year using our daily content
                strategy.
                <i class="bi bi-quote quote-icon-right"></i>
              </p>
            </div>
          </div>
        </div>
        <!-- End testimonial item -->

        <div class="swiper-slide">
          <div class="testimonial-wrap">
            <div class="testimonial-item text-center">
              <img
                src="assets/images/testimonials/investmentclubunic.png"
                class="testimonial-img mb-3"
                alt="Liya HT"
              />
              <h3>@investment.club.unic</h3>
              <h4>Instagram</h4>
              <div class="stars">
                <i class="bi bi-star-fill"></i><i class="bi bi-star-fill"></i><i
                  class="bi bi-star-fill"
                ></i><i class="bi bi-star-fill"></i><i class="bi bi-star-fill"
                ></i>
              </div>
              <p>
                <i class="bi bi-quote quote-icon-left"></i>
                Consistently high engagement in our niche investment community.
                <i class="bi bi-quote quote-icon-right"></i>
              </p>
            </div>
          </div>
        </div>
        <!-- End testimonial item -->

        <div class="swiper-slide">
          <div class="testimonial-wrap">
            <div class="testimonial-item text-center">
              <img
                src="assets/images/testimonials/liyahtinst.png"
                class="testimonial-img mb-3"
                alt="Liya HT"
              />
              <h3>@liya.ht</h3>
              <h4>Instagram</h4>
              <p>
                <i class="bi bi-quote quote-icon-left"></i>
                A well-crafted personal brand builds trust and drives product interest.
                Clients come through Instagram — with Reels reaching over 1M viewers.
                <i class="bi bi-quote quote-icon-right"></i>
              </p>
            </div>
          </div>
        </div>
        <!-- End testimonial item -->
      </div>
      <div class="swiper-pagination"></div>
    </div>
  </div>

  <!-- Featured -->
  <section id="featured" class="featured">
    <div class="container">
      <div class="section-header" data-aos="fade-up">
        <h2>🚀 What Happens After We Start Working Together:</h2>
        <p>Step-by-Step Execution by Our Team</p>
      </div>
      <div class="row">
        <!-- start  skills -->
        <div class="col-md-5 center">
          <div class="list-center-wrap" data-aos="fade-up">
            <div class="img-fluid">
              <img src="assets/images/liyanout.svg" alt="icon" />
            </div>
          </div>
        </div>
        <!-- end  skills -->

        <!-- start  left -->
        <div class="col-md-7 left">
          <div class="row">
            <div class="col-md-12">
              <p>
                Delegate your business <span class="big-text"
                  >and social media</span
                >
                to a dedicated team —
                <span class="small-text">we’ll take care of everything</span> from
                strategy to daily publishing.
              </p>
            </div>
            <div class="col-lg-6 left">
              <div class="list-wrap" data-aos="fade-up">
                <div class="icon">
                  <img src="assets/images/icons/icon-1.1.svg" alt="icon" />
                </div>
                <div class="description">
                  <h4>
                    Full-Service <span style="color: #c00113;">Launch</span>
                  </h4>
                  <p>We design your profile and brand identity from day one.</p>
                </div>
              </div>

              <div class="list-wrap" data-aos="fade-up">
                <div class="icon">
                  <img src="assets/images/icons/icon-2.svg" alt="icon" />
                </div>
                <div class="description">
                  <h4><span style="color: #c00113;">Content Plan</span></h4>
                  <p>
                    Unique ideas + links for TikTok, Instagram, and YouTube.
                  </p>
                </div>
              </div>

              <div class="list-wrap" data-aos="fade-up">
                <div class="icon">
                  <img src="assets/images/icons/icon-1.svg" alt="icon" />
                </div>
                <div class="description">
                  <h4>
                    Publishing <span style="color: #c00113;">Management</span>
                  </h4>
                  <p>
                    We take over daily posting across platforms. Daily posting
                    to Reels / Shorts / TikTok.
                  </p>
                </div>
              </div>
            </div>
            <!-- end  left -->

            <!-- start  right -->
            <div class="col-lg-6 right">
              <div class="list-wrap" data-aos="fade-up">
                <div class="icon">
                  <img src="assets/images/icons/icon-3.svg" alt="icon" />
                </div>
                <div class="description">
                  <h4>
                    <span style="color: #c00113;">Filming</span> Instructions
                  </h4>
                  <p>Clear scenarios and filming guides tailored to you.</p>
                </div>
              </div>

              <div class="list-wrap" data-aos="fade-up">
                <div class="icon">
                  <img src="assets/images/icons/icon-5.svg" alt="icon" />
                </div>
                <div class="description">
                  <h4>
                    <span style="color: #c00113;">Scripting & Editing</span>
                  </h4>
                  <p>
                    Video scripts, editing, text writing, and audio selection.
                  </p>
                </div>
              </div>

              <div class="list-wrap" data-aos="fade-up">
                <div class="icon">
                  <img src="assets/images/icons/icon-6.svg" alt="icon" />
                </div>
                <div class="description">
                  <h4><span style="color: #c00113;">Weekly</span> Reporting</h4>
                  <p>
                    Progress reports in a dedicated team chat. Results,
                    insights, and next steps to keep going.
                  </p>
                </div>
              </div>
            </div>
            <!-- end  right -->
          </div>
        </div>
      </div>
    </div>
    <div class="d-flex justify-content-center mt-4">
      <a href="#pricing" class="default-theme-btn-two" data-aos="fade-up"
        >Let’s Build Yours → View Plans<span></span></a
      >
    </div>
  </section>
  <!-- Featured -->
</section>
<!-- End Testimonials Section -->

<!-- Start 2 Service Section -->
<div id="services" class="section">
  <div class="top-icon-box position-relative">
    <div class="container position-relative">
      <div class="row gy-4">
        <div class="section-header" data-aos="fade-up">
          <h2>
            If Your Goal Is Product Development, Packaging, and a Fast Launch —
            Here’s How We Help Digitally
          </h2>
          <p>
            We help you develop, package, and launch your digital product — fast
            and effectively
          </p>
        </div>

        <div class="col-xl-4 col-md-6" data-aos="fade-right">
          <a href="single-service.html">
            <div class="icon-box">
              <div class="icon"><i class="flaticon-001-edit-tools"></i></div>
              <h4 class="title">Personal Brand Development</h4>
              <p>
                We guide you through product creation and branding via several
                strategic sessions, helping shape your offers and brand
                identity.
              </p>
              <span></span>
            </div>
          </a>
        </div>
        <!--End Icon Box -->

        <div class="col-xl-4 col-md-6" data-aos="fade-up">
          <a href="single-service.html">
            <div class="icon-box">
              <div class="icon"><i class="flaticon-031-database"></i></div>
              <h4 class="title">Website Creation & Product Launch</h4>
              <p>
                We build your website in just a few days with full payment
                integration and mobile adaptation — using HTML, Svelte, or, on
                request, builders like Wix or Tilda. Ready to launch your
                product fast.
              </p>
              <span></span>
            </div>
          </a>
        </div>
        <!--End Icon Box -->

        <div class="col-xl-4 col-md-6" data-aos="fade-up">
          <a href="single-service.html">
            <div class="icon-box">
              <div class="icon"><i class="flaticon-132-edit-tools"></i></div>
              <h4 class="title">Strategy Development</h4>
              <p>
                We create a clear, step-by-step strategy for your goals and
                product launch, designed to cover up to six months of execution.
              </p>
              <span></span>
            </div>
          </a>
        </div>
        <!--End Icon Box -->
      </div>
    </div>
  </div>
</div>
<!-- End 2 Service Section -->

<!--  Testimonials Digital Section  -->
<section id="testimonialsdigital" class="testimonialsdigital">
  <div class="container" data-aos="fade-up">
    <div class="section-header">
      <h2>Web Projects Delivered Fast — Full Sites in Days</h2>
    </div>

    <div class="slides-digital swiper" data-aos="fade-up" data-aos-delay="100">
      <div class="swiper-wrapper">
        <div class="swiper-slide">
          <div class="testimonial-wrap">
            <div class="testimonial-item text-center">
              <img
                src="assets/images/testimonials/simvai.png"
                class="testimonial-img mb-3"
                alt="Liya HT"
              />
              <h3>simvai.com</h3>
              <div class="stars">
                <i class="bi bi-star-fill"></i><i class="bi bi-star-fill"></i><i
                  class="bi bi-star-fill"
                ></i><i class="bi bi-star-fill"></i><i class="bi bi-star-fill"
                ></i>
              </div>
              <p>
                <i class="bi bi-quote quote-icon-left"></i>
                A clean, 3-page website with a fully integrated payment system delivered
                in just 3 days. <i class="bi bi-quote quote-icon-right"></i>
              </p>
            </div>
          </div>
        </div>
        <!-- End testimonial item -->

        <div class="swiper-slide">
          <div class="testimonial-wrap">
            <div class="testimonial-item text-center">
              <img
                src="assets/images/testimonials/fintechme.png"
                class="testimonial-img mb-3"
                alt="Liya HT"
              />
              <h3>fintechme.pro</h3>
              <div class="stars">
                <i class="bi bi-star-fill"></i><i class="bi bi-star-fill"></i><i
                  class="bi bi-star-fill"
                ></i><i class="bi bi-star-fill"></i><i class="bi bi-star-fill"
                ></i>
              </div>
              <p>
                <i class="bi bi-quote quote-icon-left"></i>
                From design to full content writing. The 8-page site was built and
                launched in just one week.
              </p>
            </div>
          </div>
        </div>
        <!-- End testimonial item -->
      </div>
      <div class="swiper-pagination"></div>
    </div>
  </div>
  <div class="d-flex justify-content-center mt-4">
    <a href="#pricing" class="default-theme-btn-two" data-aos="fade-up"
      >See How We Can Full Your Services<span></span></a
    >
  </div>
</section>
<!-- End Testimonials Digital Section -->

<!--  Call To Action Section  -->
<section id="call-to-action" class="call-to-action">
  <div class="container text-left aos-init aos-animate" data-aos="zoom-out">
    <div class="row align-items-center">
      <div class="col-lg-9">
        <h3>
          Still Have Questions? Book a free consultation with our team — we’ll
          help you find the best solution for your project.
        </h3>
        <!-- <p>We pride ourselves with our ability to perform and deliver results. Use the form below to discuss your project needs with our team, we will get back asap</p>-->
      </div>
      <div class="col-lg-3 text-right">
        <a class="default-theme-btn-one" href="mailto:lillu.ocean@gmail.com"
          >Conatct Us <span></span></a
        >
      </div>
    </div>
  </div>
</section>
<!-- End Call To Action Section -->
<!--  
<section id="team" class="team sections-bg">
  <div class="container aos-init aos-animate" data-aos="fade-up">
    <div class="row gy-4">
      <div
        class="col-xl-3 col-md-6 d-flex aos-init aos-animate"
        data-aos="fade-up"
        data-aos-delay="100"
      >
        <div class="member">
          <img src="assets/images/team/team-1.jpg" class="img-fluid" alt="" />
          <h4>Jhone Bi</h4>
          <span>Application Manager</span>
          <div class="social">
            <a href=""><i class="bi bi-twitter-x"></i></a>
            <a href=""><i class="bi bi-facebook"></i></a>
            <a href=""><i class="bi bi-linkedin"></i></a>
            <a href=""><i class="bi bi-instagram"></i></a>
          </div>
        </div>
      </div>

      <div
        class="col-xl-3 col-md-6 d-flex aos-init aos-animate"
        data-aos="fade-up"
        data-aos-delay="200"
      >
        <div class="member">
          <img src="assets/images/team/team-2.jpg" class="img-fluid" alt="" />
          <h4>Sani Awesome</h4>
          <span>Social Media</span>
          <div class="social">
            <a href=""><i class="bi bi-twitter-x"></i></a>
            <a href=""><i class="bi bi-facebook"></i></a>
            <a href=""><i class="bi bi-linkedin"></i></a>
            <a href=""><i class="bi bi-instagram"></i></a>
          </div>
        </div>
      </div>

      <div
        class="col-xl-3 col-md-6 d-flex aos-init aos-animate"
        data-aos="fade-up"
        data-aos-delay="300"
      >
        <div class="member">
          <img src="assets/images/team/team-3.jpg" class="img-fluid" alt="" />
          <h4>Andrio Willi</h4>
          <span>Content Writer</span>
          <div class="social">
            <a href=""><i class="bi bi-twitter-x"></i></a>
            <a href=""><i class="bi bi-facebook"></i></a>
            <a href=""><i class="bi bi-linkedin"></i></a>
            <a href=""><i class="bi bi-instagram"></i></a>
          </div>
        </div>
      </div>

      <div
        class="col-xl-3 col-md-6 d-flex aos-init aos-animate"
        data-aos="fade-up"
        data-aos-delay="400"
      >
        <div class="member">
          <img src="assets/images/team/team-4.jpg" class="img-fluid" alt="" />
          <h4>Afa Jonson</h4>
          <span>Business Manager</span>
          <div class="social">
            <a href=""><i class="bi bi-twitter-x"></i></a>
            <a href=""><i class="bi bi-facebook"></i></a>
            <a href=""><i class="bi bi-linkedin"></i></a>
            <a href=""><i class="bi bi-instagram"></i></a>
          </div>
        </div>
      </div>
    </div>
  </div>
</section> -->
<!-- Pricing Plans Section -->
<section id="pricing" class="section">
  <div class="container text-center">
    <div class="section-header" data-aos="fade-up">
      <h2>Social Media Management Plans</h2>
    </div>
    <div class="row g-4">
      <!-- Plan 1 -->
      <div class="col-lg-3 col-md-6">
        <div class="card shadow-sm p-4 h-100">
          <h4 class="text-danger mb-3"><span class="price-tag">€500</span></h4>
          <ul class="list-unstyled text-start">
            <li>✔ 30 videos per month with captions & audio</li>
            <li>✔ Content plan with ideas & links</li>
            <li>✔ Personal brand strategy</li>
            <li>✔ Profile design & setup</li>
            <li>✔ Scripting, Editing, Uploading</li>
            <li>✔ Posting management</li>
            <li>✔ You choose one main platform we actively manage</li>
            <li>✔ Monthly reporting & strategy</li>
          </ul>
          <a href="#" class="btn btn-danger mt-3 w-100 fw-bold">Purchase</a>
        </div>
      </div>
      <!-- Plan 3 -->
      <div class="col-lg-3 col-md-6">
        <div class="card shadow-sm p-4 h-100">
          <h4 class="text-danger mb-3"><span class="price-tag">€1000</span></h4>
          <ul class="list-unstyled text-start">
            <ul class="list-unstyled text-start">
              <li>✔ 60 videos per month with captions & audio</li>
              <li>✔ Content plan with ideas & links</li>
              <li>✔ Personal brand strategy</li>
              <li>✔ Profile design & setup</li>
              <li>✔ Scripting, Editing, Uploading</li>
              <li>✔ Posting management</li>
              <li>✔ You choose one main platform we actively manage</li>
              <li>✔ Monthly reporting & strategy</li>
            </ul>
            <a href="#" class="btn btn-danger mt-3 w-100 fw-bold">Purchase</a>
          </ul>
        </div>
      </div>

      <!-- Plan 2 -->
      <div class="col-lg-3 col-md-6">
        <div class="card shadow-sm p-4 h-100">
          <h4 class="text-danger mb-3"><span class="price-tag">€600</span></h4>
          <ul class="list-unstyled text-start">
            <li>✔ All in €500 plan</li>
            <li>✔ Auto cross-posting to a second platform of your choice</li>
            <li>✔ Advanced audience relationship building</li>
            <li>✔ Comment & DM management</li>
            <li>✔ Weekly performance report</li>
            <li>✔ Same-day brief updates on request</li>
          </ul>
          <a href="#" class="btn btn-danger mt-3 w-100 fw-bold">Purchase</a>
        </div>
      </div>

      <!-- Plan 4 -->
      <div class="col-lg-3 col-md-6">
        <div class="card shadow-sm p-4 h-100">
          <h4 class="text-danger mb-3"><span class="price-tag">€1100</span></h4>
          <ul class="list-unstyled text-start">
            <li>✔ All in €1000 plan</li>
            <li>✔ Auto cross-posting to a second platform of your choice</li>
            <li>✔ Advanced audience relationship building</li>
            <li>✔ Comment & DM management</li>
            <li>✔ Weekly performance report</li>
            <li>✔ Same-day brief updates on request</li>
          </ul>
          <a href="#" class="btn btn-danger mt-3 w-100 fw-bold">Purchase</a>
        </div>
      </div>
    </div>
  </div>
</section>
<!-- End Pricing Plans Section -->

<!-- About
  <section id="about" class="about">
    <div class="container">
      <div class="section-header" data-aos="fade-up">
        <h2>About Our Company</h2>
        <p>We're Passionate About Helping Businesses Thrive with Technology</p>
      </div>
      <div class="row">-->

<!-- start  skills -->
<!--<div class="col-md-6 center">
          <p>At <span class="big-text">RedTheme</span> <span class="small-text">we are passionate about providing
              businesses with the IT solutions they need to succeed</span> in today's competitive marketplace. We
            offer a comprehensive suite of services, from IT infrastructure and security to cloud computing and
            business applications, all delivered with the expertise and dedication you deserve.</p>
          <div data-aos="fade-up"> -->
<!-- <ul id="skills">
              <li>
                HTML
                <div class="bar-container">
                  <span class="bar" data-bar='{ "color": "rgb(192 1 19)" }'>
                    <span class="pct">82%</span>
                  </span>
                </div>
              </li>
              <li>
                CSS
                <div class="bar-container">
                  <span class="bar" data-bar='{ "color": "rgb(192 1 19)", "delay": 600 }'>
                    <span class="pct">100%</span>
                  </span>
                </div>
              </li>
              <li>
                PHP
                <div class="bar-container">
                  <span class="bar" data-bar='{ "color": "rgb(192 1 19)", "delay": 1200 }'>
                    <span class="pct">60%</span>
                  </span>
                </div>
              </li>
              <li>
                IOS
                <div class="bar-container">
                  <span class="bar" data-bar='{ "color": "rgb(192 1 19)", "delay": 2000 }'>
                    <span class="pct">80%</span>
                  </span>
                </div>
              </li>
            </ul> 
          </div>
          <a href="#contact" class="default-theme-btn-two">Contact Us <span></span></a>
        </div>
        end  skills

        start  left 
        <div class="col-md-6">
          <div class="list-center-wrap">
            <img src="assets/images/skills.jpg" alt="icon">
          </div>
        </div>

      </div>

    </div>
  </section>
  About -->

<!--  Start Counter Section 
  <div id="stats-counter" class="stats-counter section">
    <div class="container" data-aos="fade-up">
      <div class="row gy-4 align-items-center">
        <div class="col-lg-4">
          <div class="stats-item d-flex flex-column align-items-center">
            <div class="icon"><i class="flaticon-102-avatar"></i></div>
            <span data-purecounter-start="0" data-purecounter-end="232" data-purecounter-duration="1"
              class="purecounter"></span>
            <p>Happy Clients</p>
          </div> End Stats Item -->
<!-- </div>
        <div class="col-lg-4">
          <div class="stats-item d-flex flex-column align-items-center">
            <div class="icon"><i class="flaticon-060-award"></i></div>
            <span data-purecounter-start="0" data-purecounter-end="521" data-purecounter-duration="1"
              class="purecounter"></span>
            <p>Completed Projects</p>
          </div>End Stats Item -->
<!-- </div>
        <div class="col-lg-4">
          <div class="stats-item d-flex flex-column align-items-center">
            <div class="icon"><i class="flaticon-122-circular-clock"></i></div>
            <span data-purecounter-start="0" data-purecounter-end="453" data-purecounter-duration="1"
              class="purecounter"></span>
            <p>Hours Of Support</p>
          </div> End Stats Item -->
<!-- </div>
      </div>
    </div>
  </div>
  End Counter Section  -->

<!--  Testimonials Section
  <section id="testimonials" class="testimonials">
    <div class="container" data-aos="fade-up">

      <div class="section-header">
        <h2>Testimonials</h2>
        <p>Our testimonials are a testament to the satisfaction of our clients</p>
      </div>

      <div class="slides-3 swiper" data-aos="fade-up" data-aos-delay="100">
        <div class="swiper-wrapper">

          <div class="swiper-slide">
            <div class="testimonial-wrap">
              <div class="testimonial-item">
                <div class="d-flex align-items-center info-box">
                  <img src="assets/images/testimonials/testimonial-1.jpg" class="testimonial-img flex-shrink-0" alt="">
                  <div>
                    <h3>Jhone Doe</h3>
                    <h4>CFO</h4>
                    <div class="stars">
                      <i class="bi bi-star-fill"></i><i class="bi bi-star-fill"></i><i class="bi bi-star-fill"></i><i
                        class="bi bi-star-fill"></i><i class="bi bi-star-fill"></i>
                    </div>
                  </div>
                </div>
                <p>
                  <i class="bi bi-quote quote-icon-left"></i>
                  Proin iaculis purus consequat sem cure digni ssim donec porttitora entum suscipit rhoncus.
                  Accusantium quam, ultricies eget id, aliquam eget nibh et. Maecen aliquam.
                  <i class="bi bi-quote quote-icon-right"></i>
                </p>
              </div>
            </div>
          </div>

          <div class="swiper-slide">
            <div class="testimonial-wrap">
              <div class="testimonial-item">
                <div class="d-flex align-items-center info-box">
                  <img src="assets/images/testimonials/testimonial-2.jpg" class="testimonial-img flex-shrink-0" alt="">
                  <div>
                    <h3>Afa Rose</h3>
                    <h4>Web Designer</h4>
                    <div class="stars">
                      <i class="bi bi-star-fill"></i><i class="bi bi-star-fill"></i><i class="bi bi-star-fill"></i><i
                        class="bi bi-star-fill"></i><i class="bi bi-star-fill"></i>
                    </div>
                  </div>
                </div>
                <p>
                  <i class="bi bi-quote quote-icon-left"></i>
                  Proin iaculis purus consequat sem cure digni ssim donec porttitora entum suscipit rhoncus.
                  Accusantium quam, ultricies eget id, aliquam eget nibh et. Maecen aliquam.
                  <i class="bi bi-quote quote-icon-right"></i>
                </p>
              </div>
            </div>
          </div>

          <div class="swiper-slide">
            <div class="testimonial-wrap">
              <div class="testimonial-item">
                <div class="d-flex align-items-center info-box">
                  <img src="assets/images/testimonials/testimonial-3.jpg" class="testimonial-img flex-shrink-0" alt="">
                  <div>
                    <h3>Keena Lara</h3>
                    <h4>Store Owner</h4>
                    <div class="stars">
                      <i class="bi bi-star-fill"></i><i class="bi bi-star-fill"></i><i class="bi bi-star-fill"></i><i
                        class="bi bi-star-fill"></i><i class="bi bi-star-fill"></i>
                    </div>
                  </div>
                </div>
                <p>
                  <i class="bi bi-quote quote-icon-left"></i>
                  Proin iaculis purus consequat sem cure digni ssim donec porttitora entum suscipit rhoncus.
                  Accusantium quam, ultricies eget id, aliquam eget nibh et. Maecen aliquam.
                  <i class="bi bi-quote quote-icon-right"></i>
                </p>
              </div>
            </div>
          </div>

          <div class="swiper-slide">
            <div class="testimonial-wrap">
              <div class="testimonial-item">
                <div class="d-flex align-items-center info-box">
                  <img src="assets/images/testimonials/testimonial-4.jpg" class="testimonial-img flex-shrink-0" alt="">
                  <div>
                    <h3>Fizzi Brandon</h3>
                    <h4>Freelancer</h4>
                    <div class="stars">
                      <i class="bi bi-star-fill"></i><i class="bi bi-star-fill"></i><i class="bi bi-star-fill"></i><i
                        class="bi bi-star-fill"></i><i class="bi bi-star-fill"></i>
                    </div>
                  </div>
                </div>
                <p>
                  <i class="bi bi-quote quote-icon-left"></i>
                  Proin iaculis purus consequat sem cure digni ssim donec porttitora entum suscipit rhoncus.
                  Accusantium quam, ultricies eget id, aliquam eget nibh et. Maecen aliquam.
                  <i class="bi bi-quote quote-icon-right"></i>
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="swiper-pagination"></div>
      </div>
    </div>
  </section>
 End Testimonials Section -->

<!--  Recent Blog Posts Section 
  <section id="recent-posts" class="recent-posts sections-bg">
    <div class="container" data-aos="fade-up">
      <div class="section-header">
        <h2>Blogs</h2>
        <p>Our latest blog posts, featuring images and videos to enhance your reading experience</p>
      </div>
      <div class="row gy-4">
        <div class="col-lg-4">
          <article>
            <div class="post-img">
              <img src="assets/images/blog/blog-1.jpg" alt="" class="img-fluid">
            </div>
            <p class="post-category">Domain & Hosting</p>
            <h2 class="title">
              <a href="single-blog.html">How to host website on any hosting provider?</a>
            </h2>
            <div class="d-flex align-items-center">
              <div class="post-meta">
                <p class="post-author">William Smith</p>
                <p class="post-date">
                  <time datetime="2022-01-01">Feb 1, 2022</time>
                </p>
              </div>
            </div>
            <p class="text-4-line">To host a website on any hosting provider, you need to follow these steps: 1 Choose a hosting provider and sign up for a hosting plan. 2 Register a domain name </p>
          </article>
        </div> End post list item -->

<!-- <div class="col-lg-4">
          <article>
            <div class="post-img">
              <img src="assets/images/blog/blog-2.jpg" alt="" class="img-fluid">
            </div>
            <p class="post-category">Advertisement</p>
            <h2 class="title">
              <a href="single-blog.html">How to create add on google adwords?</a>
            </h2>
            <div class="d-flex align-items-center">
              <div class="post-meta">
                <p class="post-author">Ana Will</p>
                <p class="post-date">
                  <time datetime="2022-01-01">Oct 5, 2022</time>
                </p>
              </div>
            </div>
            <p class="text-4-line">Google AdWords add-ons are third-party tools and services that can extend the functionality of the AdWords platform. They can help you with tasks such as managing your campaigns, tracking your performance,</p>
          </article>
           End post list item -->

<!--<div class="col-lg-4">
          <article>
            <div class="post-img">
              <img src="assets/images/blog/blog-3.jpg" alt="" class="img-fluid">
            </div>
            <p class="post-category">Marketing</p>
            <h2 class="title">
              <a href="single-blog.html">What is digital marketing and why is important?</a>
            </h2>
            <div class="d-flex align-items-center">
              <div class="post-meta">
                <p class="post-author">Jhoni</p>
                <p class="post-date">
                  <time datetime="2022-01-01">Dec 22, 2022</time>
                </p>
              </div>
            </div>
            <p class="text-4-line">Digital marketing is the use of digital channels to promote or market products or services to consumers and businesses. It includes a wide range of activities, such as search engine optimization (SEO), pay-per-click (PPC) advertising, social media marketing, content marketing, and email marketing.</p>
          </article>
        </div>End post list item -->

<!--</div> End recent posts list -->

<!-- </div>
  </section>
  End Recent Blog Posts Section -->

<!-- Downloadd App Start 
  <div id="download-app" class="download-app-promo">
    <div class="download-app-promo-text">
      <div class="download-app-promo-text__tagline">The best way to get news on the go</div>
      <div class="download-app-promo-text__download">Download Our App Free.</div>
    </div>
    <div class="download-app-promo__section">
      <div class="download-app-promo-subsection">
        <a class="download-app-promo-subsection--link download-app-promo-subsection--playstore" href="#"
          target="_parent">
          <img class="download-app-promo__play-store" src="assets/images/google_play_store.svg" alt="google play">
        </a>
        <a class="download-app-promo-subsection--link download-app-promo-subsection--appstore" href="#"
          target="_parent">
          <img class="download-app-promo__app-store" src="assets/images/ios_app_store.svg" alt="ios app store">
        </a>
      </div>
    </div>
  </div>
  Downloadd App End -->

<!--  Clients Section 
  <div id="clients" class="clients section">
    <div class="container" data-aos="zoom-out">

      <div class="clients-slider swiper">
        <div class="swiper-wrapper align-items-center">
          <div class="swiper-slide"><img src="assets/images/clients/c-1.jpg" class="img-fluid" alt=""></div>
          <div class="swiper-slide"><img src="assets/images/clients/c-2.jpg" class="img-fluid" alt=""></div>
          <div class="swiper-slide"><img src="assets/images/clients/c-3.jpg" class="img-fluid" alt=""></div>
          <div class="swiper-slide"><img src="assets/images/clients/c-4.jpg" class="img-fluid" alt=""></div>
          <div class="swiper-slide"><img src="assets/images/clients/c-5.jpg" class="img-fluid" alt=""></div>
          <div class="swiper-slide"><img src="assets/images/clients/c-6.jpg" class="img-fluid" alt=""></div>
          <div class="swiper-slide"><img src="assets/images/clients/c-7.jpg" class="img-fluid" alt=""></div>
          <div class="swiper-slide"><img src="assets/images/clients/c-8.jpg" class="img-fluid" alt=""></div>
        </div>
      </div>

    </div>
  </div>
 End Clients Section -->

<Footer />

<!-- svelte-ignore a11y_consider_explicit_label -->
<!-- svelte-ignore a11y_invalid_attribute -->
<a
  href="#"
  class="scroll-top d-flex align-items-center justify-content-center active"
>
  <i class="bi bi-arrow-up-short"></i>
</a>
