---
layout: default
title: Welcome to AxOps
permalink: /
description: AxOps is a Technology, Consulting, and Training Services company. We expedite your journey from idea to execution 🎯
og_image_url: /assets/img/photos/opengraph/axops-technologies-og-image-v1.jpg
---
{% assign content_config = site.data.content.config %}
{% assign current_page = site.data.pageconfig %}
{% assign config = current_page.index %}

  <div class="content-wrapper">
    <!-- .content-wrapper -->
    {% if config.mode == "live" %}
    <section class="wrapper bg-soft-primary">
      <div class="container pt-10 pb-12 pt-md-14 pb-md-17">
        <div class="row gx-lg-8 gx-xl-12 gy-10 align-items-center">
          <div class="col-md-10 offset-md-1 offset-lg-0 col-lg-5 mt-lg-n2 text-center text-lg-start order-2 order-lg-0" data-cues="slideInDown" data-group="page-title" data-delay="300">
            <h1 class="display-2 mb-5 mx-md-10 mx-lg-0">{{ config.tagline_main }} <span class="typer text-primary text-nowrap" data-delay="{{ config.tagline_dynamic_delay }}" data-words="{{ config.tagline_dynamic }}"></span><span class="cursor text-primary" data-owner="typer"></span></h1>
            <p class="lead fs-lg mb-7">{{ config.tagline_cta }}</p>
            <div class="d-flex justify-content-center justify-content-lg-start" data-cues="slideInDown" data-group="page-title-buttons" data-delay="300">
              <span><a href="{{ config.button_cta1_url }}" class="btn btn-lg btn-primary rounded me-2">{{ config.button_cta1_text }}</a></span>
              <span><a href="{{ config.button_cta2_url }}" class="btn btn-lg btn-green rounded" style="margin-right: 0.6em; margin-bottom: 0.6em;">{{ config.button_cta2_text }}</a></span>
              <!-- <span><a href="{{ config.button_cta3_url }}" class="btn btn-lg btn-soft-ash rounded">{{ config.button_cta3_text }}</a></span> -->
            </div>
          </div>
          <!-- /column -->
          <div class="col-lg-7">
            <div class="row">
              <div class="col-3 offset-1 offset-lg-0 col-lg-4 d-flex flex-column" data-cues="zoomIn" data-group="col-start" data-delay="300">
                <div class="ms-auto mt-auto"><a href="{{ site.url }}/about-us/meet-the-team"><img class="img-fluid rounded shadow-lg" src="{{ config.above_the_fold_images.left-top-2 }}" srcset="{{ config.above_the_fold_images.left-top-2-srcset }}" alt="" /></a></div>
                <div class="ms-auto mt-5"><a href="{{ site.url }}/about-us/meet-the-team"><img class="img-fluid rounded shadow-lg" src="{{ config.above_the_fold_images.left-top }}" srcset="{{ config.above_the_fold_images.left-top-srcset }}" alt="" /></a></div>
                <div class="ms-auto mt-5 mb-10"><a href="{{ site.url }}/about-us/meet-the-team"><img class="img-fluid rounded shadow-lg" src="{{ config.above_the_fold_images.left-bottom }}" srcset="{{ config.above_the_fold_images.left-bottom-srcset }}" alt="" /></a></div>
              </div>
              <!-- /column -->
              <div class="col-4 col-lg-5" data-cue="zoomIn">
                <div><a href="{{ site.url }}/about-us/meet-the-team"><img class="w-100 img-fluid rounded shadow-lg" src="{{ config.above_the_fold_images.middle }}" srcset="{{ config.above_the_fold_images.middle-srcset }}" alt="" /></a></div>
              </div>
              <!-- /column -->
              <div class="col-3 d-flex flex-column" data-cues="zoomIn" data-group="col-end" data-delay="300">
                <div class="mt-auto"><a href="{{ site.url }}/about-us/meet-the-team"><img class="img-fluid rounded shadow-lg" src="{{ config.above_the_fold_images.right-top }}" srcset="{{ config.above_the_fold_images.right-top-srcset }}" alt="" /></a></div>
                <div class="mt-5"><a href="{{ site.url }}/about-us/meet-the-team"><img class="img-fluid rounded shadow-lg" src="{{ config.above_the_fold_images.right-middle }}" srcset="{{ config.above_the_fold_images.right-middle-srcset }}" alt="" /></a></div>
                <div class="mt-5 mb-10"><a href="{{ site.url }}/about-us/meet-the-team"><img class="img-fluid rounded shadow-lg" src="{{ config.above_the_fold_images.right-bottom }}" srcset="{{ config.above_the_fold_images.right-bottom-srcset }}" alt="" /></a></div>
              </div>
              <!-- /column -->
            </div>
            <!-- /.row -->
          </div>
          <!-- /column -->
        </div>
        <!-- /.row -->
      </div>
      <!-- /.container -->
    </section>
    <!-- /section -->
    <section class="wrapper bg-light">
      <!-- <div class="container py-14 pt-md-17 pb-md-25"> -->
      <div class="container py-14">
        {% if config.client_logos_section.enabled %}
        <h2 class="fs-15 text-uppercase text-muted text-center mb-8">Trusted by Over 5000 Clients</h2>
        <div class="px-lg-5 mb-14 mb-md-19">
          <div class="row gx-0 gx-md-8 gx-xl-12 gy-8 align-items-center">
            <div class="col-4 col-md-2">
              <figure class="px-5 px-md-0 px-lg-2 px-xl-3 px-xxl-4"><img src="./assets/img/brands/c1.png" alt="" /></figure>
            </div>
            <!--/column -->
            <div class="col-4 col-md-2">
              <figure class="px-5 px-md-0 px-lg-2 px-xl-3 px-xxl-4"><img src="./assets/img/brands/c2.png" alt="" /></figure>
            </div>
            <!--/column -->
            <div class="col-4 col-md-2">
              <figure class="px-5 px-md-0 px-lg-2 px-xl-3 px-xxl-4"><img src="./assets/img/brands/c3.png" alt="" /></figure>
            </div>
            <!--/column -->
            <div class="col-4 col-md-2">
              <figure class="px-5 px-md-0 px-lg-2 px-xl-3 px-xxl-4"><img src="./assets/img/brands/c4.png" alt="" /></figure>
            </div>
            <!--/column -->
            <div class="col-4 col-md-2">
              <figure class="px-5 px-md-0 px-lg-2 px-xl-3 px-xxl-4"><img src="./assets/img/brands/c5.png" alt="" /></figure>
            </div>
            <!--/column -->
            <div class="col-4 col-md-2">
              <figure class="px-5 px-md-0 px-lg-2 px-xl-3 px-xxl-4"><img src="./assets/img/brands/c6.png" alt="" /></figure>
            </div>
            <!--/column -->
          </div>
          <!--/.row -->
        </div>
        {% endif %}
        <!-- /div -->
        {% if config.why_choose_us_section.enabled %}
        <div class="row">
          <div class="col-md-10 offset-md-1 col-lg-8 offset-lg-2 mx-auto text-center">
            <h2 class="fs-15 text-uppercase text-muted mb-3">{{ config.why_choose_us_section.intro_tagline }}</h2>
            <h3 class="display-4 mb-10 px-xl-10 px-xxl-15">{{ config.why_choose_us_section.main_tagline }}</h3>
            <h2 class="fs-15 text-uppercase text-muted mb-3">{{ config.why_choose_us_section.outro_tagline }}</h2>
          </div>
          <!-- /column -->
        </div>
        <!-- /.row -->
        <ul class="nav nav-tabs nav-tabs-bg nav-tabs-shadow-lg d-flex justify-content-between nav-justified flex-lg-row flex-column">
          {% for tab in config.why_choose_us_section.tabs %}
          <li class="nav-item"> <a class="{{ tab.a_class }}" data-bs-toggle="tab" href="#{{ tab.id }}">
              <div><img src="{{ tab.svg_src }}" class="{{ tab.svg_class }}" alt="" /></div>
              <div>
                <h4 class="mb-1">{{ tab.title }}</h4>
                <p>{{ tab.summary }}</p>
              </div>
            </a> </li>
          {% endfor %}
        </ul>
        <!-- /.nav-tabs -->
        <div class="tab-content mt-6 mt-lg-8 mb-md-9">
          {% for tab in config.why_choose_us_section.tabs %}
          <div class="{{ tab.div_class }}" id="{{ tab.id }}">
            <div class="row gx-lg-8 gx-xl-12 gy-10 align-items-center">
              <div class="col-lg-6 position-relative order-lg-2">
                <div class="shape bg-dot primary rellax w-16 h-20" data-rellax-speed="1" style="top: 3rem; left: 5.5rem"></div>
                <div class="overlap-grid overlap-grid-2">
                  <div class="item">
                    <figure class="rounded shadow"><img src="{{ tab.image1_src }}" srcset="{{ tab.image1_srcset }}" alt=""></figure>
                  </div>
                  <div class="item">
                    <figure class="rounded shadow"><img src="{{ tab.image2_src }}" srcset="{{ tab.image2_srcset }}" alt=""></figure>
                  </div>
                </div>
              </div>
              <!--/column -->
              <div class="col-lg-6">
                <img src="{{ tab.tabsvg_src }}" class="svg-inject icon-svg icon-svg-md mb-4" alt="" />
                <h2 class="display-4 mb-3">{{ tab.title }}</h2>
                <p class="lead fs-lg">{{ tab.tagline }}</p>
                <p class="mb-6">{{ tab.text }}</p>
                <div class="row gy-3 gx-xl-8">
                  {% for list in tab.bullets %}
                  <div class="col-xl-6">
                    <ul class="icon-list bullet-bg bullet-soft-primary mb-0">
                      {% for line in list %}
                      <li><span><i class="uil uil-check"></i></span><span>{{ line }}</span></li>
                      {% endfor %}
                    </ul>
                  </div>
                  <!--/column -->
                  {% endfor %}
                </div>
                <!--/.row -->
              </div>
              <!--/column -->
            </div>
            <!--/.row -->
          </div>
          <!--/.tab-pane -->
          {% endfor %}
        </div>
        {% endif %}
        <!-- /.tab-content -->
      </div>
      <!-- /.container -->
    </section>
    <!-- /section - CLIENTS -->
    {% else %}
    <section class="wrapper bg-light">
        <div class="container pt-12 pt-md-14 pb-14 pb-md-16">
          <div class="row">
            <div class="col-lg-9 col-xl-8 mx-auto">
              <figure class="mb-10"><img class="img-fluid" src="{{ site.url }}/assets/img/axops-640x448.png" alt=""></figure>
            </div>
            <!-- /column -->
            <div class="col-lg-8 col-xl-7 col-xxl-6 mx-auto text-center">
              <h1 class="mb-3">AxOps Technologies</h1>
              <p class="lead mb-7 px-md-12 px-lg-5 px-xl-7">“When done well, software is invisible.” - Bjarne Stroustrup</p>
              <a href="#" class="btn btn-primary rounded-pill">Website Under Maintenance - Hang Tight &#128578;</a>
            </div>
            <!-- /column -->
          </div>
          <!-- /.row -->
        </div>
        <!-- /.container -->
      </section>
      <!-- /section -->
    {% endif %}
  </div>
  <!-- /.content-wrapper -->
  