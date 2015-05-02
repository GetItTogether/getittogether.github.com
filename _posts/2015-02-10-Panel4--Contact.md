---
layout: post
title: Contact
published: true
---

<!-- Contact Section -->
<section id="contact" class="container-fluid content-section text-center">
    <div class="row">
        <div class="col-lg-8 col-lg-offset-2">
            <h2>{{ page.title}} {{ site.name }}</h2>


<form class="form-horizontal" accept-charset="UTF-8" action="https://formkeep.com/f/7f25060beeec" method="POST">
<fieldset>

<!-- Form Name -->
<legend>Contact Us</legend>

<input type="hidden" name="utf8" value="✓">
<input type="hidden" name="url" placeholder="http://getittogether.us">
<!-- Text input-->
<div class="control-group">
  <label class="control-label" for="name">Your Name</label>
  <div class="controls">
    <input id="name" name="name" placeholder="" class="input-large" type="text">
    <p class="help-block">Enter Your Full Name</p>
  </div>
</div>

<!-- Text input-->
<div class="control-group">
  <label class="control-label" for="email">Your Email</label>
  <div class="controls">
    <input id="email" name="email" placeholder="" class="input-large" required="" type="email">
    <p class="help-block">Enter your email address</p>
  </div>
</div>

<!-- Text input-->
<div class="control-group">
  <label class="control-label" for="phone">Phone</label>
  <div class="controls">
    <input id="phone" name="phone" placeholder="415-333-4444" class="input-large" type="text">
    <p class="help-block">(optional, enter your phone number)</p>
  </div>
</div>

<!-- Textarea -->
<div class="control-group">
  <label class="control-label" for="textarea">Message</label>
  <div class="controls">
    <textarea id="textarea" name="textarea"></textarea>
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
