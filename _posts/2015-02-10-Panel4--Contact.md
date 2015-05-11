---
layout: post
title: Contact
name: ""
phone: "__Phone:__ 415.847.0694"
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
      {% if page.name %}{{ page.name | markdownify }}{% endif %}
      {% if page.phone %}{{ page.phone | markdownify }}{% endif %}
      {% include o_svg-icons.html %}
    </div>
      <div class="col-sm-4">
        <form class="form-horizontal" accept-charset="UTF-8" action="https://formkeep.com/f/7f25060beeec" method="POST">

            <!-- Form Name -->
            <input type="hidden" name="utf8" value="✓">
            <input type="hidden" name="url" placeholder="http://getittogether.us">
            <!-- Text input -->
            <div class="form-group">
              <!-- label class="control-label col-md-4" for="name"></label -->
              <!-- div class="controls" -->
                <input id="name" name="name" placeholder="Your Name" class="form-control" type="text">
              <!-- /div -->
            </div>
            <!-- Text input-->
            <div class="form-group">
              <!-- label class="control-label col-md-4" for="email"></label -->
              <!-- div class="controls" -->
                <input id="email" name="email" placeholder="Your Email" class="form-control" required="" type="email">
              <!-- /div -->
            </div>
            <!-- Text input-->
            <div class="form-group" >
              <!-- label class="control-label col-md-4" for="phone"></label -->
              <!-- div class="controls" -->
                <input id="phone" name="phone" placeholder="Phone: 415-333-4444" class="form-control" type="text">
              <!-- /div -->
            </div >
            <!-- Textarea -->
            <div class="form-group">
              <!-- label class="control-label col-md-4" for="textarea"></label -->
              <!-- div class="controls" -->
                <textarea id="textarea" name="textarea" rows="5" class="form-control"></textarea>
              <!-- /div -->
            </div>
            <!-- Button -->
            <!-- div class="form-group" -->
              <!-- label class="control-label col-md-4" for="singlebutton"></label -->
              <!-- div class="controls" -->
                <button id="singlebutton" name="singlebutton" class="btn btn-primary" type="submit">Send</button>
              <!-- /div -->
            <!-- /div -->
        </form>
      </div>
  </div>
</section>
