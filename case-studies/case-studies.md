---
layout: default
title: Case Studies
permalink: /case-studies
description: Learn more about our past projects
og_image_url: /assets/img/photos/opengraph/axops-technologies-og-image-v1.jpg
---
{% assign content_config = site.data.content.config %}
{% assign current_page = site.data.pageconfig %}
{% assign config = current_page.case-studies %}

  <div class="content-wrapper">
    <!-- .content-wrapper -->
    <section class="wrapper bg-light wrapper-border">
        <div class="container py-14 py-md-16">
            <div class="row mb-3">
                <div class="col-md-10 col-lg-12 col-xl-10 col-xxl-9 mx-auto text-center" data-cues="slideInDown" data-group="page-title" data-delay="50">
                    <h2 class="fs-15 text-uppercase text-muted mb-3"><a href="{{ site.url }}">HOME</a> > CASE STUDIES</h2>
                    <h3 class="display-4 mb-7 px-lg-19 px-xl-18">{{ config.tagline_main }}</h3>
                </div>
                <!--/column -->
            </div>
            <!--/.row -->
            <div class="row grid-view gx-md-8 gx-xl-10 gy-8 gy-lg-8" data-cue="slideInDown" data-delay="700">
                {% for member in config.members %}
                <div class="col-md-6 col-lg-4">
                    <div class="position-relative">
                    <div class="shape rounded bg-soft-blue rellax d-md-block" data-rellax-speed="0" style="bottom: -0.75rem; right: -0.75rem; width: 98%; height: 98%; z-index:0"></div>
                    <div class="card">
                        <figure class="card-img-top"><a href="{{ site.url }}/case-studies/{{ member[1].slug }}"><img class="img-fluid" src="{{ member[1].image_src }}" srcset="{{ member[1].image_src }}" alt="" /></a></figure>
                        <div class="card-body px-6 py-5">
                        <h4 class="mb-1"><a href="{{ site.url }}/case-studies/{{ member[1].slug }}">{{ member[1].title }}</a></h4>
                        <p class="mb-0" style="color: inherit;">{{ member[1].subtitle }}</p>
                        <p>
                          <ul class="list-inline mb-0">
                            {% for tech in member[1].technologies %}
                            <li class="list-inline-item me-1 mb-2">
                              <span class="btn btn-soft-ash btn-sm rounded">{{ tech }}</span>
                            </li>
                            {% endfor %}
                          </ul>
                        </p>
                        <p>
                          <div class="post-category text-line text-green">INDUSTRY: {{ member[1].industry }}</div>
                          <div class="post-category text-line text-blue">SERVICE: {{ member[1].service }}</div>
                        </p>
                        </div>
                        <!--/.card-body -->
                    </div>
                    <!-- /.card -->
                    </div>
                    <!-- /div -->
                </div>
                {% endfor %}
                <div class="col-md-6 col-lg-4">
                    <div class="position-relative">
                    <div class="shape rounded bg-soft-blue rellax d-md-block" data-rellax-speed="0" style="bottom: -0.75rem; right: -0.75rem; width: 98%; height: 98%; z-index:0"></div>
                    <div class="card">
                        <figure class="card-img-top"><img class="img-fluid" src="{{ site.url }}/assets/img/illustrations/custom/devops-automation.jpg" srcset="{{ site.url }}/assets/img/illustrations/custom/devops-automation.jpg" alt="" /></figure>
                        <div class="card-body px-6 py-5">
                        <h4 class="mb-1">More case studies enroute &#128077;</h4>
                        <p class="mb-0" style="color: inherit;">Thank you for your interest!</p>
                        </div>
                        <!--/.card-body -->
                    </div>
                    <!-- /.card -->
                    </div>
                    <!-- /div -->
                </div>
                <!--/column -->
            </div>
            <!--/.row -->
        </div>
        <!-- /.container -->
    </section>
    <!-- /section -->
  </div>
  <!-- /.content-wrapper -->