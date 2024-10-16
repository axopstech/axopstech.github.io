---
layout: default
title: Contact Us
permalink: /about-us/contact-temp0x0d
description: Would you like to learn more about our services? Reach out via the contact form below and we'll be in touch within 24 hours. Who knows.. we might just make something great together! 🤝
og_image_url: /assets/img/photos/opengraph/axops-technologies-og-image-v1.jpg
published: false
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
        <!-- <div class="col-sm-10 col-md-8 col-lg-6 col-xl-6 col-xxl-5 mx-auto"> -->
        <div class="col-md-10 offset-md-1 col-lg-8 offset-lg-2 mx-auto text-center">
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
                  <h2 class="display-4 mb-3">Let’s Talk</h2>
                  <p class="lead fs-lg">Would you like to learn more about our services?</p>
                  <p>Reach out via the contact form below and we'll be in touch within 24 hours.</p> 
                  <p>Who knows.. we might just <a target="_blank" href="{{ site.url }}/case-studies" aria-label="{{ site.data.pageconfig.index.button_cta2_aria_label }}">make something great together!</a> 🤝</p>
                  <a href="#contactform" aria-label="Contact Us" class="btn btn-primary rounded-pill mt-2">Complete The Form Below</a>
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
            <!-- <h2 class="display-6 lead fs-lg mb-3 text-center">Please complete the form below to proceed:</h2> -->
            <form id="contact-form" class="contact-form needs-validation" method="post" action="https://5hkpmrb523.execute-api.eu-west-2.amazonaws.com/dev/contact" novalidate>
              <div class="messages"></div>
              <div class="row gx-4">
                <a name="contactform" style="visibility: hidden;"></a>
                <div class="col-md-6">
                  <div class="form-floating mb-4">
                    <input id="form_name" type="text" name="form_name" class="form-control" placeholder="Jane" required>
                    <label for="form_name">First Name *</label>
                    <div class="valid-feedback"> Looks good! </div>
                    <div class="invalid-feedback"> Please enter your first name. </div>
                  </div>
                </div>
                <!-- /column -->
                <div class="col-md-6">
                  <div class="form-floating mb-4">
                    <input id="form_company" type="text" name="form_company" class="form-control" placeholder="Company Ltd" required>
                    <label for="form_company">Company *</label>
                    <div class="valid-feedback"> Looks good! </div>
                    <div class="invalid-feedback"> Please provide your company name or enter "Individual" if you don't have one to hand. </div>
                  </div>
                </div>
                <!-- /column -->
                <div class="col-md-6">
                  <div class="form-floating mb-4">
                    <input id="form_email" type="email" name="form_email" class="form-control" placeholder="jane.doe@example.com" required>
                    <label for="form_email">Work Email Address *</label>
                    <div class="valid-feedback"> Looks good! </div>
                    <div class="invalid-feedback"> Please provide a valid work email address. </div>
                  </div>
                </div>
                <!-- /column -->
                <div class="col-md-6">
                  <div class="form-select-wrapper mb-4">
                    <select class="form-select" id="form_service" name="form_service" required>
                      <option selected disabled value="">Service of Interest *</option>
                      <option value="Systems Integration">Systems Integration</option>
                      <option value="Data Lake Solutions">Data Lake Solutions</option>
                      <option value="Disaster Recovery">Disaster Recovery</option>
                      <option value="Data or Cloud Migration">Data or Cloud Migration</option>
                      <option value="Hybrid Cloud Architecture">Hybrid Cloud Architecture</option>
                      <option disabled value="">--</option>
                      <option value="FinTech Solutions">FinTech Solutions</option>
                      <option value="Data Intelligence">Data Intelligence</option>
                      <option disabled value="">--</option>
                      <option value="Enterprise AI">Enterprise AI</option>
                      <option value="SaaS Development">SaaS Development</option>
                      <option value="Technology Consulting">Technology Consulting</option>
                      <option value="CTO Services">Interim / Fractional CTO Services</option>
                      <option disabled value="">--</option>
                      <option value="Technical Training">Technical Training</option>
                      <option value="Quant R&D Training">Quant R&D Training</option>
                      <option disabled value="">--</option>
                      <option value="Other">Other / Not Sure</option>
                    </select>
                    <div class="valid-feedback"> Looks good! </div>
                    <div class="invalid-feedback"> Please select a service. </div>
                  </div>
                </div>
                <!-- /column -->
                <div class="col-12">
                  <div class="form-floating mb-4">
                    <textarea id="form_message" name="form_message" class="form-control" placeholder="Your message" style="height: 150px" required></textarea>
                    <label for="form_message">To help us assist you as best as we can, please describe your query in as much detail as possible. *</label>
                    <div class="valid-feedback"> Looks good! </div>
                    <div class="invalid-feedback"> Please enter your messsage. </div>
                  </div>
                </div>
                <!-- /column -->
                <div class="col-12">
                  <div class="form-check mb-4">
                    <input class="form-check-input" type="checkbox" value="" id="invalidCheck" required>
                    <label class="form-check-label" for="invalidCheck"> I consent to being contacted via email, and have read and understood our <a href="{{ site.url }}/about-us/privacy-policy" class="hover" aria-label="AxOps Privacy Policy">Privacy Policy</a>. </label>
                    <div class="invalid-feedback"> You must provide your consent to being contacted via email by AxOps by checking this box. </div>
                  </div>
                </div>
                <!-- /column -->
                <div class="col-12 text-center">
                  <script src="https://www.google.com/recaptcha/api.js" async defer></script>
                  <div class="form-group">
                    <input class="form-control d-none" data-recaptcha="true" required>
                    <div class="g-recaptcha" data-sitekey="{{ site.google_recaptcha.site_key }}" data-callback="verifyRecaptchaCallback" data-expired-callback="expiredRecaptchaCallback"></div>
                    <!-- <div class="g-recaptcha" data-sitekey="{{ site.google_recaptcha.site_key }}" data-action="SIGNUP"></div> -->
                    <div class="valid-feedback">
                      Looks good!
                    </div>
                    <div class="invalid-feedback">
                      Please complete the Captcha
                    </div>
                  </div>
                </div>
                <!-- /column -->
                <div class="col-12 text-center">
                  <input type="submit" class="btn btn-primary rounded-pill btn-send mb-3" value="Send Message">
                  <p class="text-muted"><strong>*</strong> denotes <b>required fields</b> that must be completed.</p>
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