---
layout: default
title: Meet the Team
permalink: /about-us/meet-the-team
description: Our battle-tested, international, multi-disciplinary talent pool.
og_image_url: /assets/img/photos/opengraph/axops-technologies-og-image-v1.jpg
published: false
---
{% assign content_config = site.data.content.config %}
{% assign current_page = site.data.pageconfig %}
{% assign config = current_page.team %}

  <div class="content-wrapper">
    <!-- .content-wrapper -->
    <section class="wrapper bg-light wrapper-border">
        <div class="container py-14 py-md-16">
            <div class="row mb-3">
                <div class="col-md-10 col-lg-12 col-xl-10 col-xxl-9 mx-auto text-center" data-cues="slideInDown" data-group="page-title" data-delay="50">
                    <h2 class="fs-15 text-uppercase text-muted mb-3"><a href="{{ site.url }}">HOME</a> > ABOUT US > {{ config.tagline_intro }}</h2>
                    <h3 class="display-5 mb-7 px-lg-19 px-xl-18">{{ config.tagline_main }}</h3>
                </div>
                <!--/column -->
            </div>
            <!--/.row -->
            <div class="row grid-view gx-md-8 gx-xl-10 gy-8 gy-lg-8" data-cue="slideInDown" data-delay="500">
                {% for member in config.members %}
                {% if member.enabled %}
                <div class="col-md-6 col-lg-3">
                    <div class="position-relative">
                    <div class="shape rounded bg-soft-blue rellax d-md-block" data-rellax-speed="0" style="bottom: -0.75rem; right: -0.75rem; width: 98%; height: 98%; z-index:0"></div>
                    {% if member.bio %}
                    <a href="#{{ member.slug }}">
                    {% endif %}
                    <div class="card">
                        <figure class="card-img-top"><img class="img-fluid" src="{{ member.image_src }}" srcset="{{ member.image_src }}" alt="" /></figure>
                        <div class="card-body px-6 py-5">
                        <h4 class="mb-1">{{ member.name }}</h4>
                        <p class="mb-0">{{ member.role }}</p>
                        </div>
                        <!--/.card-body -->
                    </div>
                    {% if member.bio %}
                    </a>
                    {% endif %}
                    <!-- /.card -->
                    </div>
                    <!-- /div -->
                </div>
                {% endif %}
                {% endfor %}
                <!--/column -->
            </div>
            <!--/.row -->
        </div>
        <!-- /.container -->
    </section>
    <!-- /section -->
    <section class="wrapper bg-light wrapper-border">
      <div class="container py-14 py-md-16 align-items-center">
        {% assign loc = "right" %}
        {% for member in config.members %}
        {% if member.enabled %}
          {% if member.bio %}
          <div class="card" style="margin-bottom: 2em;">
            <a name="{{ member.slug }}" style="visibility: hidden;"></a>
            <div class="row card-body gx-lg-8 gx-xl-12 gy-10 mb-4 mb-md-4 align-items-center" data-cues="slideInDown" data-group="page-title" data-delay="10">
              {% if loc == "right" %}
              <div class="col-lg-4 order-lg-2 position-relative">
              {% else %}
              <div class="col-lg-4 position-relative">
              {% endif %}
                <figure class="rounded mb-0"><img class="img-fluid" style="max-width: 400px; max-height: 400px;" src="{{ member.image_src }}" srcset="{{ member.image_src }}" alt=""></figure>
              </div>
              <!--/column -->
              <div class="col-lg-8">
                <h3 class="display-5 mb-4">{{ member.name }} | {{ member.role }}</h3>
                <p class="mb-5" align="justify">{{ member.bio }}</p>
                {% if member.skills %}
                {% for skill in member.skills %}
                  <span class="btn btn-soft-blue btn-sm rounded" style="margin-bottom: 0.5em; margin-right: 0.2em;">{{ skill }}</span>
                {% endfor %}
                {% endif %}
              </div>
              <!--/column -->
            </div>
          </div><!-- <hr /> -->
          <!--/.row -->
          {% if loc == "right" %}
            {% assign loc = "left" %}
          {% else %}
            {% assign loc = "right" %}
          {% endif %}
          {% endif %}
        {% endif %}
        {% endfor %}
      </div>
      <!-- /.container -->
    </section>
    <!-- /section -->
    {% include contact-form-4.html %}
  </div>
  <!-- /.content-wrapper -->