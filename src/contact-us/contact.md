---
layout: base.njk
title: Contact Us
permalink: /contact-us/
---

<!-- Contact Section -->
<section id="contact" class="contact">
  <div class="header-top">
    <div class="container">
      <div class="page-header__content">
      </div>
    </div>
  </div>

  <div class="header-bottom">
    <div class="container">
      <p class="section-description text-center">
        We’d love to hear from you! Whether you want to adopt, volunteer, or simply get involved, we're here to help.
      </p>
    </div>
  </div>

  <div class="container flow">
    <form action="/submit-contact-form" method="POST" class="contact-form">
      <div class="form-group">
        <label for="name">Your Name</label>
        <input type="text" id="name" name="name" required class="form-control" placeholder="Enter your name">
      </div>

      <div class="form-group">
        <label for="email">Your Email</label>
        <input type="email" id="email" name="email" required class="form-control" placeholder="Enter your email">
      </div>

      <div class="form-group">
        <label for="message">Your Message</label>
        <textarea id="message" name="message" required class="form-control" placeholder="Tell us how you’d like to get involved."></textarea>
      </div>

      <button type="submit" class="btn btn--primary">Submit</button>
    </form>
  </div>
</section>
