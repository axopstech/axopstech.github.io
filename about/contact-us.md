---
layout: default
title: Contact Us
permalink: /about-us/contact
description: Get in touch via the form below - we'll write back within 1 business day 🎯
og_image_url: /assets/img/photos/opengraph/axops-technologies-og-image-v1.jpg
---

  <div class="content-wrapper">
  <!-- .content-wrapper -->
  <!--
  <section class="wrapper bg-light">
    <div class="container py-14 py-md-12">
      <div class="row" data-cues="slideInDown" data-group="page-title" data-delay="0">
        <div class="text-center col-md-10 offset-md-1 col-lg-8 offset-lg-2">
            <h3 class="display-4 mb-9 px-xl-11">Need help with a <span class="underline-3 style-2 yellow">Data</span> or <span class="underline-3 style-2 green">Cloud</span> use-case? Get in touch today 🤝</h3>
        </div>
      </div>
      <div class="row" data-cues="slideInDown" data-group="page-title" data-delay="0">
        <div class="text-center col-md-10 offset-md-1 col-lg-8 offset-lg-2">
          <a href="&#109;&#97;&#105;&#108;&#116;&#111;&#58;&#115;&#101;&#114;&#118;&#105;&#99;&#101;&#115;&#64;&#97;&#120;&#111;&#112;&#115;&#46;&#116;&#101;&#99;&#104;" class="btn btn-sm btn-primary rounded-pill">
            Contact Us (<span>&#115;&#101;&#114;&#118;&#105;&#99;&#101;&#115;&#64;&#97;&#120;&#111;&#112;&#115;&#46;&#116;&#101;&#99;&#104;</span>)
          </a>
        </div>
      </div>
    </div>
  </section>
  -->
  <!-- /section -->
  <section class="wrapper bg-light text-black">
    <div class="container pt-18 pt-md-16 pb-21 pb-md-21 text-center">
      <div class="row">
        <div class="col-sm-10 col-md-8 col-lg-6 col-xl-6 col-xxl-5 mx-auto">
          <h1 class="display-6 text-black mb-9 px-xl-0"><span class="underline-3 style-2 yellow">"Great</span> things in business are never done by <span class="underline grey">one</span> person. They're done by a <span class="underline-3 style-2 green">team</span> of people." <i>- Steve Jobs</i></h1>
        </div>
        <!-- /column -->
      </div>
      <!-- /.row -->
    </div>
    <!-- /.container -->
  </section>
  <!-- /section -->
  <section class="wrapper bg-light">
    <div class="container pb-14 pb-md-0">
      <div class="row">
        <div class="col mt-n19 mb-16">
          <div class="card shadow-lg">
            <div class="row gx-0">
              <div class="col-lg-6 image-wrapper bg-image bg-cover rounded-top rounded-lg-start d-none d-md-block" data-image-src="{{ site.url }}/assets/img/misc/tm1.webp">
              </div>
              <!--/column -->
              <div class="col-lg-6">
                <div class="p-10 p-md-11 p-lg-13">
                  <h2 class="display-4 mb-3">Let’s Connect</h2>
                  <p class="lead fs-lg">Need help with a <span class="underline-3 style-2 yellow">Data</span> or <span class="underline-3 style-2 green">Cloud</span> use-case?</p>
                  <p class="lead fs-lg">Reach out via the contact form below and we'll be in touch within 24 hours.</p> 
                  <p class="lead fs-lg">Who knows, we might just <a target="_blank" href="{{ site.url }}/case-studies" aria-label="{{ site.data.pageconfig.index.button_cta2_aria_label }}">make something great together!</a> 🤝</p>
                  <a href="#" class="btn btn-primary rounded-pill mt-2">Join Us</a>
                </div>
                <!--/div -->
              </div>
              <!--/column -->
            </div>
            <!--/.row -->
          </div>
          <!-- /.card -->
        </div>
        <!-- /column -->
      </div>
      <!-- /.row -->
    </div>
    <!-- /.container -->
  </section>
  <!-- /section -->
  <section class="wrapper bg-light angled upper-end">
      <div class="container pb-11">
        <div class="row">
          <div class="col-lg-10 offset-lg-1 col-xl-8 offset-xl-2">
            <form class="contact-form needs-validation" method="post" action="./assets/php/contact.php" novalidate>
              <div class="messages"></div>
              <div class="row gx-4">
                <div class="col-md-6">
                  <div class="form-floating mb-4">
                    <input id="form_name" type="text" name="name" class="form-control" placeholder="Jane" required>
                    <label for="form_name">First Name *</label>
                    <div class="valid-feedback"> Looks good! </div>
                    <div class="invalid-feedback"> Please enter your first name. </div>
                  </div>
                </div>
                <!-- /column -->
                <div class="col-md-6">
                  <div class="form-floating mb-4">
                    <input id="form_lastname" type="text" name="surname" class="form-control" placeholder="Doe" required>
                    <label for="form_lastname">Last Name *</label>
                    <div class="valid-feedback"> Looks good! </div>
                    <div class="invalid-feedback"> Please enter your last name. </div>
                  </div>
                </div>
                <!-- /column -->
                <div class="col-md-6">
                  <div class="form-floating mb-4">
                    <input id="form_email" type="email" name="email" class="form-control" placeholder="jane.doe@example.com" required>
                    <label for="form_email">Email *</label>
                    <div class="valid-feedback"> Looks good! </div>
                    <div class="invalid-feedback"> Please provide a valid email address. </div>
                  </div>
                </div>
                <!-- /column -->
                <div class="col-md-6">
                  <div class="form-select-wrapper mb-4">
                    <select class="form-select" id="form-select" name="department" required>
                      <option selected disabled value="">Select a department</option>
                      <option value="Sales">Sales</option>
                      <option value="Marketing">Marketing</option>
                      <option value="Customer Support">Customer Support</option>
                    </select>
                    <div class="valid-feedback"> Looks good! </div>
                    <div class="invalid-feedback"> Please select a department. </div>
                  </div>
                </div>
                <!-- /column -->
                <div class="col-12">
                  <div class="form-floating mb-4">
                    <textarea id="form_message" name="message" class="form-control" placeholder="Your message" style="height: 150px" required></textarea>
                    <label for="form_message">Message *</label>
                    <div class="valid-feedback"> Looks good! </div>
                    <div class="invalid-feedback"> Please enter your messsage. </div>
                  </div>
                </div>
                <!-- /column -->
                <div class="col-12 text-center">
                  <input type="submit" class="btn btn-primary rounded-pill btn-send mb-3" value="Send message">
                  <p class="text-muted"><strong>*</strong> These fields are required.</p>
                </div>
                <!-- /column -->
              </div>
              <!-- /.row -->
            </form>
            <!-- /form -->
          </div>
          <!-- /column -->
        </div>
        <!-- /.row -->
      </div>
      <!-- /.container -->
    </section>
  <!-- /.content-wrapper -->