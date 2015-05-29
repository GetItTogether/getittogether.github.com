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
      {% if page.name %}{{ page.name }}<br>{% endif %}
      <div>
        <img class="phone" src="../img/red-phone.png" alt="telphone">
        {% if page.phone %}<a class="phonenumber" href="tel:{{ page.clickphone }}">{{ page.phone }}</a>{% endif %}
      </div>
      {% comment %}
        {% if site.links.email %}<a href="email:{{ site.links.email }}">{{ site.links.email }}</a>{% endif %}
      {% endcomment %}
      {% if site.display-footer == false %}
        {% include o_svg-icons.html %}
      {% endif %}
    </div>
  </div>
</section>
