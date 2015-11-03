---
layout: post
title:
quotes:
  - author: Kim Goodhope
    title: Principal Glenwood Elementary School
    quote: Lori's work in our community furthers my belief that a well organized home is directly linked to kids doing well in class.
  - author: Elizabeth Scheuring
    title: PR and Marketing Consultant
    quote: Our house was OUT OF CONTROL! Thanks to Lori, even our kids' rooms are tidy and easy to keep organized.
  - author: Amie B.
    title: Acupuncturist
    quote: As a newly single mom I desperately wanted to be “out with the old”. Thanks to Get It Together, a huge weight has been lifted and it’s “on with new” beginnings.
  - author: Rhea Stewart
    title: Sales and Marketing Manager
    quote: On the day of our move, I was completely overwhelmed. Lori was able to navigate the entire “moving experience” calmly, efficently, and most important, effectively.
published: true
---

<section id="testamonials" class="testamonials content-section text-center">
  <div class="container-fluid">
    <div class="row">
      <div class="col-md-12">
          <h2>{{ page.title }}</h2>
      </div>
    </div>
      <div class="art row">
        <img src="../img/testamonials-yes.svg" class="img-responsive" alt="Responsive image">
        <span class="quotes">
        {% for item in page.quotes %}
          <p class="quote">{{ item.quote }}</p><p class="author">{{ item.author }} - {{ item.title }}</p>
        {% endfor %}
        </span>
      </div>
      <div class="row">
          <div class="col-sm-10 col-sm-offset-1 text-center">
              <a href="#about" class="btn btn-circle page-scroll">
                <i class="fa fa-angle-double-down animated"></i>
              </a>
          </div>
      </div>
  </div>
</section>
