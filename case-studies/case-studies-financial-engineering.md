---
layout: default
title: "Financial Engineering"
cs_slug: financial-engineering
permalink: /case-studies/financial-engineering
description: "Our Projects: Past & Present"
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
                    <h2 class="fs-15 text-uppercase text-muted mb-3"><a href="{{ site.url }}">HOME</a> > <a href="{{ config.page_slug }}">CASE STUDIES</a> > YOU ARE HERE</h2>
                    <h3 class="display-4 mb-7 px-lg-19 px-xl-18">{{ page.title }}</h3>
                    <p>
                      <ul class="list-inline mb-0">
                        <li class="list-inline-item me-1 mb-2">
                          <a href="{{ config.page_slug }}"><span class="btn btn-soft-ash btn-sm rounded text-blue">All</span></a>
                        </li>
                        {% for service in config.services %}
                        {% if service.enabled %}
                        <li class="list-inline-item me-1 mb-2">
                        {% if service.slug contains page.cs_slug %}
                          <a href="{{ service.slug }}"><span class="btn btn-soft-ash btn-sm rounded bg-blue text-white">{{ service.name }}</span></a>
                        {% else %}
                          <a href="{{ service.slug }}"><span class="btn btn-soft-ash btn-sm rounded text-blue">{{ service.name }}</span></a>
                        {% endif %}
                        </li>
                        {% endif %}
                        {% endfor %}
                      </ul>
                    </p>
                </div>
                <!--/column -->
            </div><!--/.row -->
            {% assign members = config.members | where_exp: "member", "member.service == 'Financial Engineering'" %}
            <div class="row grid-view gx-md-8 gx-xl-10 gy-8 gy-lg-8" data-cue="slideInDown" data-delay="700">
                {% for member in members %}
                {% if member.enabled %}
                <div class="col-md-6 col-lg-4">
                  <div class="position-relative">
                  <div class="shape rounded bg-soft-blue rellax d-md-block" data-rellax-speed="0" style="bottom: -0.75rem; right: -0.75rem; width: 98%; height: 98%; z-index:0"></div>
                  <div class="card">
                      <figure class="card-img-top"><a href="{{ site.url }}/case-studies/{{ member.slug }}"><img class="img-fluid" src="{{ member.image_src }}" srcset="{{ member.image_src }}" alt="" /></a></figure>
                      <div class="card-body px-6 py-5">
                      <h4 class="mb-1"><a href="{{ site.url }}/case-studies/{{ member.slug }}">{{ member.title }}</a></h4>
                      <p class="mb-0" style="color: inherit;">{{ member.subtitle }}</p>
                      <p>
                        <ul class="list-inline mb-0">
                          {% for tech in member.technologies %}
                          <li class="list-inline-item me-1 mb-2">
                            <span class="btn btn-soft-ash btn-sm rounded">{{ tech }}</span>
                          </li>
                          {% endfor %}
                        </ul>
                      </p>  
                      <p>
                        <div class="post-category text-line text-blue">SERVICE: {{ member.service }}</div><br />
                        <div class="post-category text-line text-green">INDUSTRY: {{ member.industry }}</div><br />
                        <div class="post-category text-line text-ash">SCALE: {{ member.scale }}</div>
                      </p>
                      </div>
                      <!--/.card-body -->
                  </div>
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
    {% include contact-form-2.html %}
  </div>
  <!-- /.content-wrapper -->