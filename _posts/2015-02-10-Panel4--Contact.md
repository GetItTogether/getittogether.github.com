---
layout: post
title:
name:
phone: "415.259.9595"
clickphone: "+14152599595"
published: true
---

<section id="contact" class="contact container-fluid">
  <div class="row">
    <div class="col-sm-12 text-center">
      <div class="foo">
        <img class="phone" src="../img/red-phone.png" alt="telphone">
        <a class="phonenumber" href="tel:{{ page.clickphone }}">{{ page.phone }}</a>
      </div>
    </div>
  </div>
  <div class="row social">
    <div class="col-sm-12 text-center">
      <div class="social-links">
        {% include o_svg-icons.html %}
      </div>
    </div>
  </div>
  <div class="row">
    <div class="col-sm-10 col-sm-offset-1 text-center">
        <a href="#header" class="btn btn-circle page-scroll">
          <i class="fa fa-angle-double-up animated"></i>
        </a>
  </div>
</section>
