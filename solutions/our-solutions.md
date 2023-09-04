---
layout: default
title: Our Solutions
permalink: /solutions-old
description: Unlock Your Business's Full Potential with AxOps
og_image_url: /assets/img/photos/opengraph/axops-technologies-og-image-v1.jpg
published: false
---
{% assign content_config = site.data.content.config %}
{% assign current_page = site.data.pageconfig %}
{% assign config = current_page.our-solutions %}

  <div class="content-wrapper">
    <!-- .content-wrapper -->
    <section class="wrapper bg-light">
        <div class="container py-14 py-md-16">
            <div class="row mb-3">
            <div class="col-md-10 col-lg-12 col-xl-10 col-xxl-9 mx-auto text-center" data-cues="slideInDown" data-group="page-title" data-delay="100">
                <h2 class="fs-15 text-uppercase text-muted mb-3"><a href="{{ site.url }}">HOME</a> > {{ config.tagline_here }}</h2>
                <h3 class="display-4 mb-7 px-lg-19 px-xl-18">{{ config.tagline_main }}</h3>
            </div>
            <!--/column -->
            </div>
            <!--/.row -->
            <div class="row grid-view gx-md-8 gx-xl-10 gy-8 gy-lg-8" data-cue="slideInDown" data-delay="700">
                {% for member in config.members %}
                <div class="col-md-6 col-lg-3">
                    <div class="position-relative">
                    <div class="shape rounded bg-soft-blue rellax d-md-block" data-rellax-speed="0" style="bottom: -0.75rem; right: -0.75rem; width: 98%; height: 98%; z-index:0"></div>
                    <div class="card">
                        <a href="{{ member.url }}"><figure class="card-img-top"><img class="img-fluid" src="{{ member.image_src }}" srcset="{{ member.image_src }}" alt="" /></figure></a>
                        <div class="card-body px-6 py-5">
                        <h4 class="mb-1"><a href="{{ member.url }}">{{ member.name }}</a></h4>
                        <p class="mb-0">{{ member.role }}</p>
                        </div>
                        <!--/.card-body -->
                    </div>
                    <!-- /.card -->
                    </div>
                    <!-- /div -->
                </div>
                {% endfor %}
                <!--/column -->
            </div>
            <!--/.row -->
        </div>
        <!-- /.container -->
    </section>
    <!-- /section -->
  </div>
  <!-- /.content-wrapper -->
