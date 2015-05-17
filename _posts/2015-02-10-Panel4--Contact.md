---
layout: post
title: Contact
name: "Lori Roudebush"
phone: "415.259.9595"
clickphone: "+14152599595"
published: true
---

<!-- Contact Section -->
<section id="contact" class="contact container-fluid">
  <div class="row text-center">
    <div class="col-sm-12">
      <h2>{{ page.title }}</h2>
      <img class="logo" src="../img/logo-image.svg" alt="logo">
    </div>
  </div>
  <div class="row">
    <div class="col-sm-4 col-sm-offset-2">
      {% if page.name %}<p>{{ page.name }}</p>{% endif %}
      {% if page.phone %}<p>Phone: <a href="tel:{{ page.clickphone }}">{{ page.phone }}</a></p>{% endif %}
      <p>{% include o_svg-icons.html %}</p>
    </div>
      <div class="col-sm-4">
        <form class="form-horizontal" accept-charset="UTF-8" action="https://formkeep.com/f/7f25060beeec" method="POST">
            <!-- Form Name -->
            <input type="hidden" name="utf8" value="✓">
            <input type="hidden" name="url" placeholder="http://getittogether.us">
            <!-- Text input -->
            <div class="form-group">
              <input id="name" name="name" placeholder="Your Name" class="form-control" type="text">
            </div>
            <!-- Text input-->
            <div class="form-group">
              <input id="email" name="email" placeholder="Your Email" class="form-control" required="" type="email">
            </div>
            <!-- Text input-->
            <div class="form-group" >
              <input id="phone" name="phone" placeholder="Phone: 415-333-4444" class="form-control" type="text">
            </div >
            <!-- Textarea -->
            <div class="form-group">
              <textarea id="textarea" name="textarea" rows="5" class="form-control"></textarea>
            </div>
            <!-- Button -->
            <button id="singlebutton" name="singlebutton" class="btn btn-primary" type="submit">Send</button>
        </form>
      </div>
  </div>
</section>
