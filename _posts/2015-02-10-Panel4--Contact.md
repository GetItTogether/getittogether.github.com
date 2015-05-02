---
layout: post
title: Contact
published: true
---

<!-- Contact Section -->
<section id="contact" class="container-fluid content-section text-center">
    <div class="row">
        <div class="col-lg-8 col-lg-offset-2">
            <h2>{{ page.title}}</h2>
            <img class="logo" src="../img/logo-image.svg" alt="logo">

<form class="form-horizontal" accept-charset="UTF-8" action="https://formkeep.com/f/7f25060beeec" method="POST">
<fieldset>

<!-- Form Name -->
<!-- legend>Contact Us</legend -->

<input type="hidden" name="utf8" value="✓">
<input type="hidden" name="url" placeholder="http://getittogether.us">
<!-- Text input-->
<div class="control-group">
  <label class="control-label col-md-4" for="name"></label>
  <div class="controls">
    <input id="name" name="name" placeholder="Your Name" class="input-lg col-md-6" type="text">
    <!-- p class="help-block col-md-4">Enter Your Full Name</p -->
  </div>
</div>

<!-- Text input-->
<div class="control-group">
  <label class="control-label col-md-4" for="email"></label>
  <div class="controls">
    <input id="email" name="email" placeholder="Your Email" class="input-lg col-md-6" required="" type="email">
    <!-- p class="help-block">Enter your email address</p -->
  </div>
</div>

<!-- Text input-->
<div class="control-group">
  <label class="control-label col-md-4" for="phone"></label>
  <div class="controls">
    <input id="phone" name="phone" placeholder="415-333-4444" class="input-lg col-md-6" type="text">
    <!-- p class="help-block">(optional, enter your phone number)</p -->
  </div>
</div>

<!-- Textarea -->
<div class="control-group">
  <label class="control-label col-md-4" for="textarea"></label>
  <div class="controls">
    <textarea id="textarea" name="textarea" rows="5" class="col-md-6"></textarea>
  </div>
</div>

<!-- Button -->
<div class="control-group">
  <label class="control-label" for="singlebutton"></label>
  <div class="controls">
    <button id="singlebutton" name="singlebutton" class="btn btn-primary" type="submit">Send</button>
  </div>
</div>

</fieldset>
</form>
            <p><a href="mailto:{{ site.links.email }}">{{ site.links.email }}</a></p>
              <p>Other contact info and social site accounts are in the footer.</p>
        </div>
    </div>
</section>
